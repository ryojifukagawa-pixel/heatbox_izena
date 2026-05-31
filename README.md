# heatbox_izena
保護熱箱法の300㎜角厚さ90㎜の水が封入された試験体内部の挙動を事前に確認するシミュレーションプログラムをpythonでCopilotに作ってもらった。
# 🔥 Heatbox Simulation (Izena Project)

This repository provides a simple and intuitive simulation of heat transfer inside a water-filled heatbox.  
It visualizes:

- Convection (bottom heating)
- Pure conduction (top heating)
- U-value changes with water-layer thickness
- Flow fields (streamlines)
- Temperature fields (isotherms)

Designed for beginners, engineers, and anyone curious about heat transfer.

---

## 📘 View the Notebook

### 🔸 Static View (nbviewer — always works)
GitHub sometimes fails to render Jupyter notebooks.  
Use nbviewer for a stable view:

[![View in nbviewer](https://img.shields.io/badge/View%20in-nbviewer-orange)](
https://nbviewer.org/github/ryojifukagawa-pixel/heatbox_izena/blob/main/Untitled12new.ipynb
)

---

### 🔹 Interactive Version (Open in Colab)
Run the simulation interactively in your browser.  
Adjust thickness, temperature difference, and visualize convection.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ryojifukagawa-pixel/heatbox_izena/blob/main/Untitled12new.ipynb
)

---

## 🧪 Features

- **Bottom heating mode**  
  → Convection occurs, forming circulating flow patterns.

- **Top heating mode**  
  → Convection is suppressed, conduction dominates.

- **U-value calculation**  
  → Shows how heat transfer changes with water-layer thickness.

- **Flow visualization**  
  → Streamlines for convection.

- **Temperature visualization**  
  → Isotherms for conduction.

---

## 📦 Files in This Repository

| File | Description |
|------|-------------|
| `Untitled12new.ipynb` | Main notebook (English version, GitHub-safe) |
| `README.md` | This document |
| (Optional) `colab_version.ipynb` | Interactive version with widgets |

---

## 🌍 Background

This project was created to help people understand:

- Why bottom heating creates convection  
- Why top heating suppresses it  
- How Rayleigh and Nusselt numbers relate to heat transfer  
- How U-value depends on water-layer thickness  
- How visualization helps intuition

It is especially useful for:

- Students  
- Engineers  
- Sales teams  
- Anyone learning thermal engineering  

---

## 🔤 English–Japanese Glossary (for beginners)

| English | Japanese |
|--------|----------|
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

## 📄 License

This project is open for educational and research use.

---

## 🙌 Acknowledgment

This project was developed with the goal of making heat transfer intuitive and enjoyable for everyone.  
Special thanks to all who explore, learn, and share this simulation.
## 🖼️ 説明図（イメージ）

### 1. 下側加熱（対流が発生する場合）
<img src="https://via.placeholder.com/1" alt="Convection diagram" />

### 2. 上側加熱（対流が抑制される場合）
<img src="https://via.placeholder.com/1" alt="Conduction diagram" />

### 3. 水層の厚さと U値の関係
<img src="https://via.placeholder.com/1" alt="U-value vs thickness diagram" />
