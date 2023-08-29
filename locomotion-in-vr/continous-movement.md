# Continous Movement

memungkinkan kita untuk bergerak dengan kontroller

1. 1.buka Assets/Samples/XR Interaction Toolkit/2.4.1/Starter Assets pilih file XRI Default Continuous Move Kemudian Klik tombol add to action basedcontinuous move provider default![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2Fof38SEbz6Kz6e9VnSX0j%2Fimage.png?alt=media\&token=a4e19c35-13ae-47d8-9577-615ec707f654)
2. 2.selanjutnya pilih file XRI Default Continuous Turn Kemudian Klik tombol add to action basedcontinuous move provider default

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FZ3R0YYK0stAFV8Ww8YCt%2Fimage.png?alt=media\&token=765233f3-4d2b-474c-a973-76bc82e79caa)

1. 3.kemudian di hierarki klik XR origin kemudian add component locomotion system

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F9TrX0HN6a0fPxX5lZWqf%2Fimage.png?alt=media\&token=75cb2646-a9a8-43c5-8f46-b7a61ac36cec)

1. 4.pada locomotion system set variable xr origin ke gameobject xr origin

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FOLWqY7BMX72nQnokoVME%2Fimage.png?alt=media\&token=91969c3c-e008-4359-b572-fa5f0037f3ec)

1. 5.tambahkan component continuous move provider action based![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FaB5H5Dvf5e5CxrqxVHfG%2Fimage.png?alt=media\&token=b9ccd6c4-47a2-4d5e-854e-05cf6b710ae0)
2. 6.pada variable system pilih locomotion yang baru ditambahkan

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FDz9OTHSISMWmbObmriQt%2Fimage.png?alt=media\&token=3147bcdc-916c-4c54-a586-045c23618e8f)

1. 7.agar pergerakan tidak terlalu lambat ubah movement speed menjadi 3

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FSwDERsW1FAt1krheFk48%2Fimage.png?alt=media\&token=286f57d3-95e6-4643-90b7-e5bd01fc52be)

1. 8.kemudian agar hanya dapat bergerak dengan kontroller pada tangan kiri hilangkan centang pada use reference di right hand move action![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FM87eildKAUk9pQnFlEdo%2Fimage.png?alt=media\&token=dc1c3074-0914-457d-93a8-e5d348867cf3)
2. 9.kemudian untuk rotasi tambahkan component continuous move provider action based![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F0OCQd3eDW3MdF7mp2ILU%2Fimage.png?alt=media\&token=ebd8e830-bcd9-433a-a385-b2a962ebc4f0)
3. 10.kemudian agar hanya dapat rotate dengan kontroler kananuncheck centang pada use reference di left hand move action, dan set system ke xr origin
