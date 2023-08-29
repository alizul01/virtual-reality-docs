# Controller

## Controller

​

| Nama              | Deskripsi                                                                                                                                                                                                                                                                                                                  | Value |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Velocity Tracking | Memindahkan objek yang bersifat _Interactable_ dengan mengatur kecepatan dan kecepatan sudut Rigidbody.​Pake ini kalau kamu gamau objek bisa melewati Collider lain tanpa Rigidbody saat mengikuti Interactor. Tapi, ada masalah yaitu objek bisa tampak seperti tertinggal dan nggak bisa bergerak semulus Instantaneous. | 0     |
| Kinematic         | Memindahkan objek Interactable dengan memindahkan Rigidbody kinematic menuju posisi dan orientasi target.​Pake ini kalau kamu pengen tampilan visual selalu sinkron dengan keadaan fisiknya, dan kalau kamu ingin objek bisa melewati Collider lain tanpa Rigidbody saat mengikuti Interactor.                             | 1     |
| Instantaneous     | Memindahkan objek Interactable dengan mengatur posisi dan rotasi Transform setiap frame.​Pake ini kalo kamu ingin tampilan visual terupdate setiap frame, sehingga minim latency. Tapi perlu diingat, masalahnya adalah objek akan bisa melewati Collider lain tanpa Rigidbody saat mengikuti Interactor.                  | 2     |
