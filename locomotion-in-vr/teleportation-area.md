# Teleportation Area

Akhirnya sampai juga pada final part teleportation yaitu teleportation area. Agar sistem mengetahui dimana saja area teleportasi, dibutuhkan sebuah komponen bernama teleportation area.

1. 1.Pergi ke \_STADIUM>_\__STADIUM PLAY AREA child game object. Pastikan setiap anak game object memiliki mesh collider.\
   ![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F5nbXmuivZ6mWIjFyG8bY%2Fimage.png?alt=media\&token=acf7a079-4860-4d0a-a184-a0009e1d357f)
2. 2.Pada setiap child game object beri komponen Teleportation Area.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F7cibaYYT0cVEZMz2Uvre%2Fimage.png?alt=media\&token=b1d3639e-784f-4e51-96cd-55fa8059efda)
3. 3.Dalam teleportation area tambahkan new layer dan beri nama Teleport.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F8iTroZZizyDWELVzxNLU%2Fimage.png?alt=media\&token=01aa8333-82d1-4da3-810c-904983c1aee3)
4. 4.Lalu ubah interaction layer mask menjadi Teleport.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FsvdQlFHx9dj26FDamAmf%2Fimage.png?alt=media\&token=3ebb6b49-add5-4b25-8c23-26454851567b)
5. 5.Setelah itu pergi ke RightHand Teleport Controller dan ubah interaction layer menjadi teleport.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FcXhpnby6FdUNnjg7Og43%2Fimage.png?alt=media\&token=356acc4b-97bb-4949-b863-a344f6685f01)
6. 6.Agar tampilan laser saat menunjuk teleportation area semakin menarik, dapat menggunakan custom reticle. Kunjungi dan download asset packages recticle. Kemudian import asset tersebut.
7. 7.Setelah berhasil mengimport, pergi ke Asset>CustomReticles>Prefabs. Di sini terdapat satu object berupa reticles.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FnN7j8jWAvnahIZvyXsll%2FScreenshot%20\(1336\).png?alt=media\&token=58303578-9edc-4809-ada3-3aa4d21a5469)
8. 8.Lalu drag and drop object pada komponen Teleportation Area>Collider>Custom Reticle.
