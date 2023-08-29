# Setting up

Setup agar map ini dapat

1. Pertama, Hapus GameObject **Camera.**

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2Fcj645zrYZbGqEwO8SiBQ%2Fimage.png?alt=media\&token=66e0e133-00d9-4d6f-adf3-ec6d07d9807f)

1. 2.jika anda klik kanan pada _Hierarcy_ pilih XR Disini akan muncul beberapa hal yang kita perlukan, salah satunya **XR origin**.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F0FHbbQ52u9dYysrZe7Es%2Fimage.png?alt=media\&token=ba942b17-6367-453a-a991-1de0f260290f)Sebelum lanjut klik kanan lagi, pilih XR>Device based, terdapat kompnen serupa, yaitu **XR origin**. Perbedanya adalah pada _Device Based_, input dikelola berdasarkan perangkat tertentu yang digunakan. Misalnya, jika yang digunakan adalah Meta Quest 2, input akan dikelola berdasarkan spesifikasi pengontrol Meta Quest.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F1NMPigrRjZRK9TLQEWI7%2Fimage.png?alt=media\&token=09f8596c-6e5a-4830-a02d-33c4775d05d5)

1. 3.Disini karena _Unity Input System_ mendukung berbagai perangkat, yang digunakan adlaah yang pertama atau disebut action based silahkan buat dengan klik kanan pada hirarki, pilih xr>xr origin

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FKoqEgxB8rLqyKwdvZyvv%2Fimage.png?alt=media\&token=b70ab107-16a4-44a5-9227-a49aeb4a8d11)Pada saat XR origin dibuat akan ada 2 GameObject baru, yaitu **XR origin** dan **XR interaction manager**. **XR Interaction Manager** seperti jembatan antar _Interactors_ dan _Interactables_. **Interactors**, contohnya dapat dianggap sebagai tangan. Karena dalam berinteraksi controller pada tangan akan digunakan untuk berinteraksi dengan suatu GameObject pada scene. Dan **Interactables** akan menjadi GameObject yang berinteraksi dengan Interactors, misalnya diambil atau disentuh atau bahkan diklik jika itu adalah GameObject UI. Interaction Manager diperlukan untuk komunikasi antara Interactors dan Interactables. Kemudian **XR origin** pada dasarnya adalah GameObject yang mengatur posisi headset dan controller VR. Didalamnya terdapat skrip XR Origin yang harus dilampirkan. GameObject ini akan lebih berguna ketika implementasi komponen movement. Disini juga terdapat kamera baru yang memiliki tracked driver pose script yang hadir dengan Input System yang akan melacak posisi vr headset. selain itu terdapat juga controller kanan dan kiri.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FZWDDqVw0LwOXVGrVlHAY%2Fimage.png?alt=media\&token=a0ba0374-af24-4698-9086-5e70cc466572)

1. 4.Jika kita lihat pada XR Origin> Left Controller terdapat beberapa _tracking type_ untuk input, Dengan unity input system akan lebih mudah untuk mengatur input yang diperlukan.
