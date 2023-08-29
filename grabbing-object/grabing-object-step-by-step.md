# Grabing Object Step by Step

1. Pada hierarki pilih objek yang dapat diambil, disni **broomstick.**

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FxjDiGMyYfFBBfUGo9yoZ%2Fimage.png?alt=media\&token=e8808d51-1e04-4a47-8c9a-26860483de14)

2. Pada inspector scroll kebawah dan add component **XR Grab Interactable.**![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FPEerwHc3iEVsm0eNKDev%2Fimage.png?alt=media\&token=b2688ca3-ec7b-4186-9bde-301cd6d96ed5)​
3. 3.Pada component R_igidbody_, uncheck **usegravity** agar object tidak jatuh.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FIW1qp3r1EYH7i0YYATUb%2Fimage.png?alt=media\&token=53f4bf10-b278-43b2-a9f2-9a7112343fdd)​

4. Kemudian add component **capsule colider** agar dapat bersentuhan dengan objek lain.![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FMRfJatpTiFz5EdSIQkdN%2Fimage.png?alt=media\&token=b374748c-cff8-49e5-bbdd-4c662779d88e)
5. 5.kemudian agar tidak semua objek dapat diambil namun hanya objek tertentu, pada hirarki, pilih _left controller_ dan pada component _XR Ray Interactor_ terdapat **Interaction layer mask**, pilih add layer,![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2F8mwACyzxQhJqNSTMk4ck%2Fimage.png?alt=media\&token=39c88b07-06d7-4a7c-9684-a74e59218ab3)kemudian buat layer dengan nama **Interactable,**

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2Fm3L5aqktrmNBEzh3kLjS%2Fimage.png?alt=media\&token=c9c56e49-9de5-49f1-bfce-1d90a1b91bb3)ubah Interaction layer mask pada _left controller_ dan _right controller_ menjadi **interactable,**![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FcWqfdhPchrLIKnhzJ24B%2Fimage.png?alt=media\&token=41c5b445-f6f4-4089-ad94-2d00c938ea61)terakhir pada _interaction manager_ pilih **XR interaction manager.**![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FC7kCMHrmwZsruTks1WIU%2Fimage.png?alt=media\&token=c28e5728-444d-4886-b44c-904069a3ca67)​

6. Pada _Broomstick_, pilih _Interaction layer mask_ menjadi I**nteractable**, dengan ini controller hanya akan mengikutsertakan gameobject dengan layer interactable_._![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaqmFisaJr4K91KrM0Nhv%2Fuploads%2FwxvpHQRDq9ymt7RrAPbJ%2Fimage.png?alt=media\&token=bb536d2f-b9e3-4c87-96f9-e3bfb75215c0)
7. Agar broomstick tidak melayang, pada hierarki pilih objek _broomstick_, kemudian pada inspector untuk componen _rigidbody_ centang **is kinematic**.
