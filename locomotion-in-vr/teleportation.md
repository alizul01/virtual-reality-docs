# Teleportation

Selain continous movement, player juga dapat bergerak dengan cara teleportasi.

1. 1.Pada hierarki, klik XR Origin dan tambahkan komponen **Teleportation Provider**.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FCefIuyqEE3MPGTxPLQKK%2Fimage.png?alt=media\&token=827f1039-d96f-466c-a28b-ef8df071d765)
2. 2.Kemudian _drag and drop_ komponen locomotion system pada teleportation provider.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FuuxTzVcV7lOkQoGoZayW%2Fimage.png?alt=media\&token=963c2d2c-da61-4fd8-a37a-50c9b6f3c9bd)
3. 3.Teleportasi telah tersedia, namu perlu ditambahkan beberapa komponen lagi agar dapat bekerja. Sekarang, create an empty object di dalam camera offset dan beri nama **RightHand Parent**.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FnQ9hD7xxEEQnFfKFkFrJ%2Fimage.png?alt=media\&token=023fe8bc-c12e-4ed8-89bf-f3f38f9c58ac)
4. 4.Kemudian pindahkan RightHand Controller ke dalam right hand parent dan ubah namanya menjadi **RightHand Teleport Controller**.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F7GMvYToPIMMnPse5eJxl%2Fimage.png?alt=media\&token=fa408a74-14b4-4ebf-9516-b29176c09b47)
5. 5.Setelah itu klik kanan pada right hand parent dan buat objek baru dengan nama **RightHand Base Controller**.
