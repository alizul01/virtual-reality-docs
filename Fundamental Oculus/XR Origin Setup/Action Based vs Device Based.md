# Action Based vs Device Based Behaviours

Ada dua jenis perilaku (behavior) yang bisa kamu pilih dalam Unity XR Interaction Toolkit, yaitu 'Action-based' dan 'Device-based'.

'Action-based' itu perilakunya bekerja menggunakan 'Actions'. 'Actions' ini kerjanya tidak langsung baca input dari kontrol, tapi lewat perantara dulu. Jadi, misalnya kamu punya joystick dan tombol A, kamu bisa buat satu 'Action' yang namanya 'Loncat', dan tombol A atau joystick bisa dipakai untuk aksi 'Loncat' itu. Jadi lebih fleksibel gitu, satu 'Action' bisa dilakukan oleh banyak kontrol.

Sementara 'Device-based', perilakunya langsung baca input dari suatu kontrol di suatu perangkat. Jadi misalnya kamu mau tombol A di joystick kamu buat loncat, ya tombol A itu langsung diset buat loncat. Lebih simpel sih, tapi kurang fleksibel dibanding 'Action-based'.

Rekomendasinya sih, mendingan pakai 'Action-based'. Selain lebih fleksibel, ada juga fitur-fitur tambahan keren dari paket Input System Unity. Misalnya, kamu bisa pisahin antara input logis (misal 'Loncat') dan input fisik (misal tombol A), bisa gonta-ganti aksi yang sudah kamu buat, bisa pasang banyak input kontrol dari berbagai perangkat ke satu aksi, dan masih banyak lagi. Beberapa fitur di XR Interaction Toolkit juga cuma bisa dipakai kalau kamu pakai 'Action-based', seperti XR Device Simulator.

Jadi, singkatnya, 'Action-based' itu lebih fleksibel dan punya lebih banyak fitur dibanding 'Device-based'. Tapi kalau proyekmu simpel dan kamu gak butuh semua fitur tambahan itu, 'Device-based' bisa jadi pilihan yang lebih simpel.