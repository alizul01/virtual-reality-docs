# Action-Based Controller Manager

To be able swap between base and teleportation controller we need a script/manager.

1. 1.Pada object right hand parent, tambah komponen Action-based Controller Manager.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F89v3OYnXZYv6iNy5cdyi%2Fimage.png?alt=media\&token=f811b90f-6218-4ec6-92a9-682f0fc6d8ac)
2. 2.Kemudian isi bagian kosong seperti gambar di bawah ini.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FNIx09uSWP3kLHfDqkpfM%2Fimage.png?alt=media\&token=3836e23a-aa0b-49a5-b022-dce90891078f)

* Untuk bagian ray interactor, pertama tambahkan XR>Ray Interactor.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FeTLtcbZa8ni5j9miW7oJ%2Fimage.png?alt=media\&token=3902883b-1adb-4f53-b60e-6b570f071892)
* Apabila sudah hilangkan centang pada semua komponen yang ada, lalu _drag and drop_ object pada bagian ray intercator (lihat gambar nomor 2).![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FuVicHJwJM1YkuGDOcgPx%2Fimage.png?alt=media\&token=edad25a0-956f-4127-a686-9417411dbb26)

1. 3.Selanjutnya add component XR Interaction Group.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FCFAUG9VEOSkZqkZiW4f9%2Fimage.png?alt=media\&token=5c147b8c-b001-45a7-9b92-b983386125d1)
2. 4.Tambahkan 2 list atau group member dengan base controller sebagai element pertama dan teleport controller dinomor kedua.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2Fk4E3DLs9jCykkuNCog3v%2Fimage.png?alt=media\&token=a855238c-ade0-4545-a9c1-e7708d9c83b1)
3. 5.Kemudian drag and drop XR Interaction Group pada Manipulation Intercation Group.
