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

名前　test block  
ファイル名　test block  
AO　オン  
UVモード　UV  
テクスチャ 16x16  

![image](https://user-images.githubusercontent.com/55620461/156300332-35020f15-0693-4064-ac72-13801f85d7c6.png)

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
![image](https://user-images.githubusercontent.com/55620461/156302772-948e7199-0635-44a2-bdd4-153ce5e03523.png)

### 作成したテクスチャを保存する

![image](https://user-images.githubusercontent.com/55620461/156302927-0b3e3c1e-a271-4c90-a798-2d9d2926ddd5.png)
  
このポップアップは無視でOK  

![image](https://user-images.githubusercontent.com/55620461/156302959-e910bd55-eafd-4aa6-bdb9-84540d924d56.png)

# Minecraft上での見え方を調整する

### 右上のDisplayを選択
![image](https://user-images.githubusercontent.com/55620461/156303289-2e1bf21d-e44f-428b-8c86-e358ca31084f.png)

### 左側のパラメーターをいじって持っているときやインベントリ上の画面の見え方を調整する

![image](https://user-images.githubusercontent.com/55620461/156303410-4b17674a-e3c4-4683-ac3f-493c1e146f0c.png)

# リソースパックに出力する

### File > エキスポート > Export Resouce Packを選択

![image](https://user-images.githubusercontent.com/55620461/156303618-dd1d77ad-89f9-4201-8aa5-c041b1fab568.png)

### 適当にリソースパックの名前を決めて出力する

![image](https://user-images.githubusercontent.com/55620461/156303719-8c5038b4-7542-49e4-ac21-6b02224eefac.png)

## この方法で出力したリソパには画像が入っていないため、画像を入れる

### できたzipを展開し、assets > minecraft > textures にさっき作った

