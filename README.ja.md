# Aizume

Aizumeは、[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)を使用してリアルタイムなハンドトラッキングを行うウェブアプリケーションです。検出された各手の5本の指先を青い円で可視化し、その円のサイズはカメラから指までの推定距離に応じて動的に変化します。

## デモ

[**ライブデモ**](https://code4fukui.github.io/aizume/)

## 機能

-   MediaPipe Handsによるリアルタイムな手のランドマーク検出。
-   動的にサイズが変化する青いマーカーによる指先の可視化。
-   最大10本の手の同時トラッキングをサポート。
-   以下の切り替え可能なコントロール機能:
    -   オリジナルのカメラ映像の表示。
    -   映像の左右反転（ミラーリング）。
    -   デバイスの背面カメラへの切り替え。

## 使い方

1.  最新のウェブブラウザで[デモページ](https://code4fukui.github.io/aizume/)を開きます。
2.  プロンプトが表示されたら、カメラへのアクセスを許可します。
3.  アプリケーション上に、指先にマーカーが付いた状態の手が表示されます。
4.  チェックボックスを使用して表示を制御します:
    -   `show original image`: ライブカメラ映像の表示/非表示を切り替えます。
    -   `mirror mode`: 映像を左右反転します。
    -   `backcamera mode`: デバイスの前面カメラと背面カメラを切り替えます。

## クレジット

本プロジェクトは[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)ソリューションを利用しています。

## ライセンス

[MIT License](LICENSE)
