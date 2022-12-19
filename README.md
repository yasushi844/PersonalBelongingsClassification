# PersonalBelongingsClassification
CNNを用いた日用品画像分類


# データセットについて

- データ一覧

　1.book、　2.pen、　3.scissors、　4.amulet、　5.earphone、　6.mask、　7.mahjongtile

![0000](https://user-images.githubusercontent.com/81167956/208385258-5d2038dd-1328-4b04-9375-53c79fe60272.jpeg)
![0110](https://user-images.githubusercontent.com/81167956/208385306-f6e75c29-cf39-4f9d-b3d3-ec8e0ff52206.jpeg)
![0182](https://user-images.githubusercontent.com/81167956/208385678-a61c4936-07d7-4cbb-af1a-ab0d1f452543.jpeg)
![0278](https://user-images.githubusercontent.com/81167956/208385725-ea256e0e-fcfe-410e-a946-1ebd4e5c33d4.jpeg)
![0370](https://user-images.githubusercontent.com/81167956/208385392-e326c3aa-8a44-4ae0-977e-6b81543f5047.jpeg)
![0482](https://user-images.githubusercontent.com/81167956/208385435-690e28c4-833f-465d-a40a-28d3f872a4dd.jpeg)
![0547](https://user-images.githubusercontent.com/81167956/208385462-891d0e7f-37d3-407a-ba85-26e4e478a8c0.jpeg)

- データセット詳細
  
  - 画像枚数は 7種類 × 90枚 = 630枚
  - 画像サイズは 縦 80pixel × 横 60pixel
 
# データの水増しについて

- データの水増の手法
  - 画像を360*(±0.2)の範囲でランダムに回転
  - 画像を(±0.3)の範囲でランダムに拡大(縮小)させる

keras.layersから RandomRotation, RandomZoomの2つを使用した
