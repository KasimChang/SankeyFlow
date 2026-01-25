Sankey Flow Pro - Professional Financial Visualization Engine | 專業財務視覺化引擎

Sankey Flow Pro is a high-precision data visualization tool designed for financial analysts and corporate planners. Based on the D3.js Sankey engine, it transforms complex balance sheets, P&L statements, and hierarchical revenue structures into intuitive, presentation-ready flow diagrams with multi-dimensional control.

Sankey Flow Pro 是一款專為財務分析師與企業規劃者設計的高精度視覺化工具。基於 D3.js Sankey 引擎開發，能將複雜的資產負債表、損益表及層級營收結構，轉化為直覺且具備簡報質感的流向圖，並提供多維度的排版控制功能。

🚀 核心功能 | Core Features

1. 多維度動態控制 | Multi-Dimensional Dynamic Controls

无段式垂直間距 (Vertical Spacing): Adjust node padding from 0 to 100px for optimal density.

階段水平跨度 (Horizontal Bar Gap): Expand or contract the distance between tiers (up to 200%) to prevent visual clutter.

標籤字體大小 (Label Font Size): Smoothly scale text from 6px to 24px for perfect legibility in any report format.

無段式垂直間距：自由調整節點間距（0~100px），優化排版密度。

階段水平跨度：可調整各階段 Bar 之間的距離（最大達 200%），有效應對多層級結構。

標籤字體大小：支援 6px 至 24px 的文字縮放，確保在不同解析度下的閱讀舒適度。

2. 進階互動管理 | Advanced Interactive Management

Cross-Platform Drag & Drop: A robust reordering system powered by elementFromPoint, ensuring smooth operation on both Desktop (Mouse) and Mobile (Touch).

Hierarchical Nesting: Organize data with intuitive indentation (up to 3 depths) for sub-item aggregation.

Real-Time Visual Editor: Click on any node to customize labels, accent colors, and opacity instantly.

跨平台拖移機制：採用 elementFromPoint 技術，確保在桌機（滑鼠）與手機（觸控）上皆具備流暢的排序與移動體驗。

層級縮排管理：支援多達三層的縮排結構，底層數據會自動向上彙總。

即時視覺編輯器：點擊圖表節點即可自訂名稱、主題色與透明度。

3. 專業級報告輸出 | Professional Export & Optimization

3x Resolution PNG: High-density rendering for sharp text and smooth curves, perfect for large-scale printing or HD presentations.

Smart Auto-Naming: Automatically names exported files with yyyymmdd_sankey.png for effortless version control.

RWD Adaptive Layout: Automatically switches to a vertical stacking mode on mobile devices for comfortable one-handed operation.

3 倍高解析導出：提供高品質 PNG 下載，確保文字與流向曲線在簡報或大圖輸出時依然銳利。

智慧自動命名：導出圖片自動採 yyyymmdd_sankey.png 格式命名，便於版本控管。

RWD 自適應佈局：手機用戶會自動切換為「垂直堆疊模式」，極大化單手操作空間。

📈 視覺模型 | Mathematical Concept

Sankey Flow Pro adheres to the principle of flow conservation, ensuring data integrity across financial tiers:
本工具遵循流向守恆定律，確保財務階段間的數據一致性：

$$\sum \text{Input} = \sum \text{Output}$$

Node (節點): Represents a financial entity or category. | 代表財務科目或分類。

Link (路徑): Visualizes the magnitude of flow between categories. | 視覺化呈現各科目間的資金規模。

🛠️ 技術棧 | Tech Stack

Frontend: React 18 (Hooks)

Visualization: D3.js v7 + d3-sankey

Styling: Tailwind CSS (Modern Glassmorphism Design)

Icons: Custom SVG + Lucide Icons

📖 如何使用 | Getting Started

Github page : https://kasimchang.github.io/SankeyFlow/ (直接開啟互動網頁)

Define Tiers: Add or remove financial stages using the streamlined "新增階段" button.

Input Values: Enter your raw data; use the Indent (縮排) feature to create sub-hierarchies.

Customize Layout: Use the three sliders (Spacing, Width, Font) to find the "Sweet Spot" for your diagram.

Download: Click "下載圖片" to save your work with professional naming and 3x resolution.

定義階段：使用精簡的「新增階段」按鈕建立財務流程。

輸入數據：填入數值，並利用縮排功能建立子科目層級。

優化排版：透過間距、寬度、字體三個拉桿，調整出最理想的視覺外觀。

下載儲存：點擊「下載圖片」獲得帶有日期命名的 3x 高清圖表。

✍️ 作者 | Author

kasimchang Precision Pricing Engine Creator GitHub Profile

📜 版權聲明 | Copyright & License

All Rights Reserved. This project is currently not open for licensing. No part of this software may be reproduced, modified, or distributed without written permission from the author.

版權所有，翻印必究。 本專案目前不開放授權使用。未經作者書面許可，請勿擅自轉載、修改、散佈或用於商業用途。
