# Explore XR Grab Interactable Types

Pada gameobject yang memiliki komponen XR grab interactable yang memiliki beberapa tipe, penjelasan detailnya dapat dilihat pada halaman controller.

1. 1.Untuk mencontohkan drag 2 prefab(**bludger, beater bat**) dari Assets/IRONHEADGames/Prefabs kedalam hierarki.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F6Xk7mpYxTJu9gtl05G01%2Fimage.png?alt=media\&token=5864b31a-bc82-461c-b7b6-ac234a5df41f)

1. 2.tambahkan komponen **capsule collider** dan **xr grab interactable.**

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F1Q5nvIUX0WRfqbSicypz%2Fimage.png?alt=media\&token=33635385-a4b8-4557-a6d1-4fcf265d7027)

1. 3.pada game object _beaterbat_, di component _XR Grab Interactable_ set _interaction layer mask_ ke **Interactable** dan _movement type_ ke **velocity tracking**, juga sesuaikan posisi dan ukuran collider dari beaterbat.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FnJUj0BSLDIBPFigRGx85%2Fimage.png?alt=media\&token=3d1b3618-d48c-4a75-940b-8f65ebda5ce8)
2. 4.Pada game Object _bludger_ berikan component **Xr Grab Interactable** dan S**phere Collider.**

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FomkuWh7gqtEnVnbZ8uFU%2Fimage.png?alt=media\&token=d503300e-06f9-4180-8023-94cf49d68624)

1. 5.di component _XR Grab Interactable_ set _Interaction layer mask_ ke **Interactable** dan _Movement Type_ ke **Instantaneous.**

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FmHBv0OlyAtfmpHuXYGAb%2Fimage.png?alt=media\&token=a87e2d94-074a-4ed6-b8fc-b705ead040d0)

1. 6.Jika di run sekarang 2 object tersebut akan jatuh menembus lantai, hal ini dikarenakan tidak ada collider pada lantai lapangan, jadi pergi ke hierarki pilih 4 object stadium floor dan tambahkan component mesh collider.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FBHL1LGX13sfx2tK6gH7L%2Fimage.png?alt=media\&token=c2340a60-63d8-4e55-be28-451563d03317)jalankan di vr, disini dapat dilihat perbedaan perilakunya, dimana singkatnya instantaneous tidak peduli dengan fisika, sedangkan velocity tracking mempedulikan fisika. disini dapat dipilih sesuai kebutuhan​
