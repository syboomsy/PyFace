# PyFace
A B/S structured face recognizing app based on Springboot(for server development) and face_recognition module.

The app is mainly based on Springboot to build a online face recognizing server; 
Besides, the subsidiary AI modules(in Python) uses face_recognition(facebook's open source project)
's api to support critical recognition function.

In light of simplicity, I cut off dataBase design and instead, I replace it with a special dirctory for label figures' storage.
Maybe in the future, I will add new features such as using Redis as the label cache to speed up procedure.
