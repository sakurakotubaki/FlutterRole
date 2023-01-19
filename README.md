# FlutterRole
roleをもたせて、先生か、生徒でログイン先の画面を変更する資料.

[参考にしたYouTube動画](https://www.youtube.com/watch?v=q5E8811Ut_8)<br>

- 使用するpackage
  - firebase_core
  - cloud_firestore
  - firebase_auth

## アプリの仕組み
usersコレクションをユーザー新規登録時に作成して、FireStoreにroleを設定する。
roleが、StudentかTeacherかで、判定して画面線先が変わる。
