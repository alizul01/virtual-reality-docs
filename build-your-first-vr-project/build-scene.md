# Build Scene

Build dilakukan untuk Meta QuestPada kiri atas unity klik File>Build Settings.​​​Untuk platform pilih Android kemudian klik Switch Platform.​​Di VR core template projek dioptimalkan untuk VR build, untuk setting lebih optimal pilih Add Open Scenes.​​Ubah Texture Compression menjadi ASTC.​​Klik Player Settings, pilih Other Settings, pada Color Space pilih Linear untuk rendering realistis.​​​pada other settings uncheck Auto Graphics API, kemudian pada Graphics API hapus Vulkan dengan pilih vulkan dan klik ikon -. Hal ini dikarenakan vulkan masih berada pada tahap eksperimental.​​​scroll kebawah pada minimum API Level pilih Android 10(API Level 29).​​​Kemudian ubah Package Name menjadi nama unik.​​​Yang terakhir, scroll pada bagian Configuration dan centang ARM64​​​Selanjutnya pada sidebar pilih XR Plug In Management, centang OpenXR. pada versi terbaru tidak muncul popup error.​​​OpenXR adalah standar yang memberikan akses kinerja tinggi ke platform dan perangkat XR. Berkat OpenXR, pengembangan XR akan memiliki dukungan lintas platform yang jauh lebih luas yang memungkinkan pengembang menargetkan berbagai perangkat XR. OpenXR diimplementasikan sebagai bagian dari Plugin framework XR Unity di sini. Artinya kita bisa menggunakan XR Interaction Toolkit atau AR Foundation untuk menargetkan berbagai perangkat XR yang diadopsi OpenXR. Dan hal yang baik untuk diketahui adalah bahwa OpenXR mendukung Meta Quest 2 melalui OpenXR Mobile SDK.Tapi meta menyarankan menggunakan Oculus XR​jadi kembali ke XR Plug In Management uncheck openXR dan centang Oculus.​​

1. 12.kemudian pada sidebar pilih _oculus_ dan pada _Stereo Rendering Mode_ pilih **Multiview** untuk performa lebih baik.

![](https://lh4.googleusercontent.com/-nlGqzOfw5NOblrflH1jIiiyXpsJv4JkplV\_U\_PwSHCzr\_eG9R0TCe5O7oZZT0Jrp374PS3RADXRrDd2l1hw1jmoPOMdF4kZ5Jt4IMo5defMjb7MvPqRpHFTrAI\_4klk0rPJjBhZQwOAz-f\_rSSG\_NY)

1. 13.masih pada Oculus centang **Quest2**, jika juga menargetkan perangkat quest pro, centang juga Quest Pro

![](https://lh3.googleusercontent.com/TA8zY2yp8Rgb80KNTPuZ6JBvoqyVCru\_IFKPgiPsXySxcsxgow13CzMtc4\_PFkBfbSi4-YCHJi2TxgLXp5Sa3GJFGfkOah6nemLUdX34tlSIK-dfEsJgu0LhivunsfeE46SzRJQVR5Luw488TdE5QeQ)

1. 14.Kemudian kembali pada halaman _Build Settings_ dan klik **Build**

​![](https://lh6.googleusercontent.com/a9pDmE4KHT-uWZbi3eQVDCh1I5Mic-rD7tfo6QAsEm5ZhByCLRN75DwW1ixXeWBzEdPKO9545yyoWXYLp6UIvRbybLTLbSCRx4LGROG5XXmSvfyQ3Lv6lwqJcomUA4E7GwlH4QjIrrb7qql9ulNjLc8)

1. 15.beri nama pada apk yang dibuild, dan klik **Save**

​![](https://lh6.googleusercontent.com/gZdkD\_Dfa-klnYGsiqqQFeko1tlff2cXMakT9-dLns1ERa4UD9RUOnQ\_5OUIOyEiusujwlyjFmb9tooehiGg5OkBXofz3T-UI7FGTLVjwwpBDg-WY97OJpQu4QxSaUpkGdzDsS35EoOsA7lYNgLUYV8)​untuk setup openXR dapat dilihat di:https://docs.unity3d.com/Packages/com.unity.xr.openxr@1.7/manual/index.html\
