# Limiting Area

In game we need to limit area that accessible by player, pada bagian sebelumnya player dapat bergerak, namun ini juga memungkinkan player bergerak menembus dinding. Untuk menegah player dapat pergi ke suatu area yang tidak diinginkan atau tidak menembus dinding, diperlukan collider.

1. 1.pertama tambahkan component character controller pada xr origin, ini akan membuat karakter memiliki collider tanpa harus berurusan dengan rigidbody

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FCEOcGqzmmVC1KpFPIFp9%2Fimage.png?alt=media\&token=d2e0d814-5589-4513-b61a-8f8aa0327156)

1. 2.kecilkan radius agar player dapat mendekat ke objek lain, dan set center y ke 1![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F2WSVcFEU40W1udmQyYC2%2Fimage.png?alt=media\&token=3b9d94f0-8e18-46de-bfde-676151e5a0a9)

​

1. 3.contohnya jika kita ingin menghalangi player dari menembus diding kita dapat memberi objek 3d, contohnya disini cube,![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FFhZ7SDu62bUXdRx5iTty%2Fimage.png?alt=media\&token=a6dd21bb-3737-4552-9167-a68cd2eae937)
2. 4.ubah ukuran, kemudian posisikan di posisi yang tepat, dan hilangkan centang dari komonen renderer

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2Ft0cqPGFa2jTHPCDDjnIK%2Fimage.png?alt=media\&token=5f5468f6-4bdc-4803-923b-ea17a296231e)coba di vr dan cek apakah tembok masih bisa ditembus
