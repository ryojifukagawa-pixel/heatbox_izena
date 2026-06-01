# heatbox_izena
# 🔥 保護熱箱シミュレーション（伊是名プロジェクト）

このリポジトリは、水を満たした「保護熱箱」の中で起こる  
**対流・伝導・熱貫流率（U値）の変化を直感的に理解できるシミュレーション** をまとめたものです。

- 下側加熱 → 対流が発生し、流れが循環する  
- 上側加熱 → 対流が抑制され、伝導が支配的になる  
- 水層の厚さによって U値がどう変わるか  
- 流線（ストリームライン）や等温線（アイソサーム）で可視化  

技術者だけでなく、初めて熱の世界に触れる方にも分かりやすい構成になっています。

---

## 📘 ノートブックを見る方法

GitHub はノートブックを正しく表示できないことがあります。  
そのため、以下の2つの方法を用意しています。

---

### 🔸 安定して閲覧できる（nbviewer）

GitHub がエラーになる場合でも、こちらなら確実に開けます。

[![View in nbviewer](https://img.shields.io/badge/View%20in-nbviewer-orange)](
https://nbviewer.org/github/ryojifukagawa-pixel/heatbox_izena/blob/main/Untitled12new.ipynb
)

---

### 🔹 インタラクティブ版（Google Colab）

ブラウザだけで動かせる体験版です。  
厚さ・温度差・係数をスライダーで動かしながら、  
対流や伝導の変化をリアルタイムで確認できます。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ryojifukagawa-pixel/heatbox_izena/blob/main/heatbox_nteractive.ipynb
)
)

---

## 🧪 このシミュレーションでできること

- **下側加熱（対流 ON）**  
  - レイリー数（Ra）  
  - ヌッセルト数（Nu）  
  - 流線（ストリームライン）  
  - U値の変化  

- **上側加熱（対流 OFF）**  
  - 伝導支配の温度分布  
  - 等温線（アイソサーム）  

- **水層の厚さと U値の関係をグラフ化**

---

## 📦 リポジトリ内のファイル

| ファイル名 | 説明 |
|------------|------|
| `Untitled12new.ipynb` | GitHub 用の英語版ノートブック（安定表示用） |
| `README.md` | この説明書 |
| （任意）`colab_version.ipynb` | Colab 用のウィジェット付きインタラクティブ版 |

---

## 🔤 英語 ↔ 日本語 対照表（初心者向け）

| 英語 | 日本語 |
|------|--------|
| Heatbox | 保護熱箱 |
| Convection | 対流 |
| Conduction | 伝導 |
| Streamlines | 流線 |
| Isotherms | 等温線 |
| Thickness | 厚さ |
| Temperature difference | 温度差 |
| U-value | 熱貫流率 |
| Rayleigh number | レイリー数 |
| Nusselt number | ヌッセルト数 |

---

## 🙌 このプロジェクトについて

このシミュレーションは、  
**「熱の世界を、誰でも直感的に楽しめるように」**  
という思いから作られました。

- 技術者  
- 営業の方  
- 高齢者  
- 学生  
- 初めて Python に触れる方  

どなたでも楽しめるように工夫しています。

 
## 🖼️ 説明図（イメージ）

### 1. 下側加熱（対流が発生する場合）
<img src="https://via.placeholder.com/1" alt="Convection diagram" />

### 2. 上側加熱（対流が抑制される場合）
<img src="https://via.placeholder.com/1" alt="Conduction diagram" />

### 3. 水層の厚さと U値の関係
<img src="https://via.placeholder.com/1" alt="U-value vs thickness diagram" />
