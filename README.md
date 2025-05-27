# YuhoReader: 有価証券報告書分析ツール

![JPHACKS2021_ogp](https://jphacks.com/wp-content/uploads/2021/07/JPHACKS2021_ogp.jpg)

## 概要

**YuhoReader**は、有価証券報告書（PDF）から連結貸借対照表（B/Sシート）を自動生成し、初心者でも簡単に企業分析ができるオープンソースツールです。

## 特長

- **簡単操作**: PDFをドラッグ＆ドロップ、またはファイル選択するだけでOK
- **自動解析**: Google Cloud Vision APIとOpenCVで高精度な文字認識
- **B/Sシート自動生成**: Pythonのopenpyxlでエクセル形式のB/Sシートを作成
- **用語解説・指標表示**: シート下部に用語の解説や財務指標を自動表示
- **モダンなUI**: グラスモーフィズムを取り入れた見やすいデザイン

## 使い方

1. 本リポジトリをクローンまたはダウンロード
2. 必要な依存パッケージをインストール
3. サーバーを起動
4. Webブラウザでアクセスし、PDFをアップロード

## インストール

1. このリポジトリをクローン
2. Python 3.7以上を用意
3. 依存パッケージを一括インストール

```bash
pip install -r requirements.txt
```

### 主な依存パッケージ
- Django==3.2.8（Webフレームワーク）
- mathfilters（Djangoテンプレート用フィルタ）
- pdf2image（PDF→画像変換）
- opencv-python, numpy（画像処理）
- Pillow（画像処理）
- pyocr（OCR処理）
- openpyxl（Excel出力）
- requests（API通信）

## 開発技術

- **フロントエンド**: JavaScript, HTML, CSS
- **バックエンド**: Python (Django)
- **OCR/画像処理**: Google Cloud Vision API, OpenCV, Tesseract
- **Excel出力**: openpyxl
- **その他**: jQuery

## API・データ
- Google Cloud Vision API

## 対応デバイス
- PCブラウザ

## コントリビュート

バグ報告・機能提案・プルリクエスト歓迎です！

## ライセンス

このプロジェクトはMITライセンスのもとで公開されています。


