# BlockBenchハンズオン

# 下準備

1. [BlockBenchのホームページ](https://www.blockbench.net/) からインストーラーをダウンロードし、BlockBenchをインストールする
2. BlockBenchを起動し、File > Preferences > Settings.. > Language から日本語を選択
3. BlockBenchを再起動する
4. File > プラグイン > 利用可能 を開き「Resource Pack Exporter」をインストールする

# 簡単なモデルの作成
こんな感じのモデルを作成します

# プロジェクトを作る

### 最初の画面から Java block/item を選択

もしくは File > 新規作成 > Java block/item
![image](https://user-images.githubusercontent.com/55620461/156299995-70572171-b365-4ae2-aaa5-ae5e7078b4c3.png)


### プロジェクトの詳細を決める

**この時名前にスペースを入れるとモデルが正しく認識されないため注意**
  
![image](https://user-images.githubusercontent.com/55620461/156333616-b07f73a5-c58b-441d-8a67-19f37bb5de9c.png)


# モデルを作る

### Cubeを作成
右のプラスボタンを押してCubeを追加する
![image](https://user-images.githubusercontent.com/55620461/156300535-7fce91cb-0c09-416c-bfe9-a8f5532a38d1.png)

### 移動ギズモを使ってキューブを真ん中に持ってくる
![image](https://user-images.githubusercontent.com/55620461/156300707-c8734931-e1db-4837-80f7-a5f440f7081c.png)

### サイズギズモを選択する
![image](https://user-images.githubusercontent.com/55620461/156300765-32eba382-492f-4bba-89e4-94a3af590d34.png)

### いい感じの大きさに調整する
![image](https://user-images.githubusercontent.com/55620461/156300848-5998271d-2447-4542-bc95-f5aebc023902.png)


### 右のELEMENTからピボットを押し、回転軸をキューブの中心にする
![image](https://user-images.githubusercontent.com/55620461/156300980-45a79c14-17a5-47f3-adfb-0e174ad8c410.png)

### 回転ギズモを選択する
![image](https://user-images.githubusercontent.com/55620461/156301077-07bcf698-9ddc-45ec-bffd-9803653eb2ec.png)

### 適当に角度を調整する
![image](https://user-images.githubusercontent.com/55620461/156301148-8ef958e4-259d-4e0b-a4d6-263538848f12.png)

# テクスチャを作成する

### テクスチャ作成ボタンを押す
![image](https://user-images.githubusercontent.com/55620461/156302301-376aa54c-1353-4335-b1a8-c4cd603221c0.png)

### テクスチャの詳細を決める

とりあえずデフォルトでOK  
![image](https://user-images.githubusercontent.com/55620461/156302378-103251a2-9125-41f9-a7d8-177da640cd8b.png)

### 右上のPaintボタンを押す

![image](https://user-images.githubusercontent.com/55620461/156302455-f03d8c60-4414-45ff-b98e-bbbdd52450bd.png)

### ツールバーのツールを使い適当に塗る

![image](https://user-images.githubusercontent.com/55620461/156302509-09ec0edf-7feb-4fbb-a0a7-64dc527c0cd1.png)



### 作成したテクスチャを保存する

このポップアップは無視でOK  

![image](https://user-images.githubusercontent.com/55620461/156302959-e910bd55-eafd-4aa6-bdb9-84540d924d56.png)
![image](https://user-images.githubusercontent.com/55620461/156340689-a5b2d8e2-87e2-4f6e-92e6-68203fb10c7c.png)


# Minecraft上での見え方を調整する

### 右上のDisplayを選択

![image](https://user-images.githubusercontent.com/55620461/156340725-df4201e3-7bf9-46ef-9ace-7a2ea06e2318.png)


### 左側のパラメーターをいじって持っているときやインベントリ上の画面の見え方を調整する

![image](https://user-images.githubusercontent.com/55620461/156340766-585d51df-9083-4996-a4fd-d4591c3f99d5.png)


# リソースパックに出力する

### File > エキスポート > Export Resouce Packを選択

![image](https://user-images.githubusercontent.com/55620461/156340857-42461de5-1249-4b54-b62d-59070653cb86.png)


### 適当にリソースパックの名前を決めて出力する

![image](https://user-images.githubusercontent.com/55620461/156340931-aba1c1bb-e9cb-4912-9048-258537c92fa2.png)

## この方法で出力したリソパには画像が入っていないため、画像を入れる

### できたzipを展開し、assets > minecraft > textures にさっき保存した画像を入れる

![image](https://user-images.githubusercontent.com/55620461/156341097-0717863d-7e6c-4741-bb8e-05619c4cc3a6.png)

### 展開したフォルダをリソースパックに入れ、ガラスブロックにテクスチャが適応されてればOK
![2022-03-02_19 11 20](https://user-images.githubusercontent.com/55620461/156341599-a2bdc0d5-7f98-4103-8364-2a87a15ec036.png)

# 既存のテクスチャを使う

画像は以下の物を使用します  
DLして使用してください  

![amazon](https://user-images.githubusercontent.com/55620461/156341684-0c526cb2-4bfb-48af-9b45-9a0942fe19dc.png)

### D&Dで画像を追加する

![image](https://user-images.githubusercontent.com/55620461/156342123-b4d84980-6b98-4cd4-9960-12295ef0b7b2.png)

### Cubeを選択し、テクスチャを右クリック > エレメントに適応 を押す

![image](https://user-images.githubusercontent.com/55620461/156342226-1cfb1e1d-655d-4f57-80b9-7fb3b155acc7.png)

### UVがずれているためUV座標を変更して自然な見栄えにする
![image](https://user-images.githubusercontent.com/55620461/156342415-15a5da3e-6e7f-4536-b555-0b01d917c835.png)
![image](https://user-images.githubusercontent.com/55620461/156342661-43cf955c-bd02-4dcb-9488-8c63f21c0aec.png)
![image](https://user-images.githubusercontent.com/55620461/156342728-16c3ffa0-0962-4de0-8268-f85686098729.png)


### 上記と同じ手順でリソパを作りMinecraft内で確認する

このような見た目になっていればOK

![2022-03-02_19 29 10](https://user-images.githubusercontent.com/55620461/156344394-47f4a86d-8b37-468c-a065-21899403bbc3.png)




