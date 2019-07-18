## 処理説明
  - コードの流れ
    - 1.パソコンのカメラを指で押さえ3秒程度の動画を撮る
    - 2.動画を1フレームごとに画像変換をする
    - 3.それぞれの画像の輝度値の平均値を出し、グラフにプロットする。  
また、OpenCV、OSの様々な機能を使うために"cv2","os"をimportしている。  
以上の流れで脈を測るようにした。

## 実行結果  
出力として出てきた画像から輝度値の変化がわかる。  
しかし、自分が期待していた脈が打ったと思われる輝度値の大きな変化が見られなかった。  
動画撮影の精度を上げるために試行錯誤が必要である。  
実行の様子はgifアニメーションでとして提出する。

## 参考にしたサイト  
  - Pythonでの動画の取り扱い（OpenCVで再生とキャプチャ生成) [https://www.tech-tech.xyz/opencv_video.html]  
    (動画を1フレームごとに画像へ変換)部分
  - ソースに絡まるエスカルゴ [http://rikoubou.hatenablog.com/entry/2019/01/15/174751]  
    (1:動画ファイルの読み込み)部分
