# Agent Collaborative Workspace 🚀

歡迎來到整合專案工作區。本目錄是一個結合多代理人（Multi-Agent）協作的開發環境，涵蓋了物流、數據科學、自動化測試以及多項創意側寫專案。

## 🔗 核心快捷傳送門 (Quick Links)

*   **雲端同步中心**: [EcoReceipt 深度研究報告 (Notion)](https://www.notion.so/EcoReceipt-350b5c56a1bf81bb9196f5575fe31712)
*   **黑克松與商業提案**:
    *   [鼠光 PestAway 智慧病媒治理平台企劃書 (PDF)](file:///c:/Users/user/Desktop/Agent_Workspace/projects/side_projects/PestAway/docs/鼠光%20PestAway｜智慧病媒治理平台.pdf)
    *   [鼠光 PestAway 介面功能初稿 (PDF)](file:///c:/Users/user/Desktop/Agent_Workspace/projects/side_projects/PestAway/docs/介面功能初稿.pdf)
    *   [EcoReceipt MVP 核心規格文件 (Notion/Markdown)](file:///c:/Users/user/Desktop/Agent_Workspace/projects/side_projects/NCCU_Hackathon/docs/MVP_PRD.md)
*   **學術統計研究室**:
    *   [Project 4 信用評分實證研究報告 (Word)](file:///c:/Users/user/Desktop/Agent_Workspace/projects/academic_stats/Project4_Discriminant_Logistic/project4_report.docx)
    *   [Project 3 生活型態分析集群報告](file:///c:/Users/user/Desktop/Agent_Workspace/projects/academic_stats/Project3_Cluster_Analysis/)
    *   [IKEA 消費者行為分析報告](file:///c:/Users/user/Desktop/Agent_Workspace/projects/ikea/reports/)
*   **物流與自動化測試**:
    *   [Orbit TMS UAT 測試日誌](file:///c:/Users/user/Desktop/Agent_Workspace/projects/QA_Orbit_TMS/)
    *   [OMS CIO Portal 訓練手冊](file:///c:/Users/user/Desktop/Agent_Workspace/projects/OMS_CIO_Training_Manual/)

## 📅 重要里程碑 (Milestones & Roadmap)

| 預計日期 | 專案項目 | 目標與里程碑 | 狀態 |
| :--- | :--- | :--- | :--- |
| **2026-05** | **政大黑克松** | EcoReceipt & 鼠光 PestAway 智慧治理平台設計 | ✅ 已完賽 |
| **2026-06** | **雀巢專案** | 週期性物流數據優化報告產出 | ✅ 已完成 |
| **2026-06** | **IKEA 專案** | 消費者行為數據分析與儀表板 | ✅ 已完成 |
| **2026-08-01**| **幹部訓練** | 幹部訓練教材準備與實際授課 | ✅ 已完成 |
| **2026-08** | **ALP GIP 2026** | Global Internship Programme 畢業影片規劃 | 🚀 準備中 |
| **2026-08** | **全家專案** | 專案各流程功能交付與驗收 | 🚀 準備中 |
| **Ongoing** | **Orbit 專案** | QA UAT 測試與模組優化 | 🚀 持續進行中 |

---

## 📂 完整目錄結構 (Directory Structure)

```text
.
├── projects/                     # 核心專案目錄
│   ├── side_projects/            # 個人側寫、課程與競賽專案 (Side Projects & Competitions)
│   │   ├── PestAway/             # 鼠光 PestAway｜智慧病媒治理平台 (新整理 ✨)
│   │   │   └── docs/             # 包含系統介面功能初稿與完整企劃書 PDF
│   │   ├── NCCU_Hackathon/       # EcoReceipt (政大黑克松 - 永續生活 App)
│   │   ├── 永豐金競賽/           # 數位金融創新提案
│   │   ├── 雀巢物流優化專案/     # Nestle 供應鏈數據分析與優化
│   │   ├── elderly_karaoke_app/  # 樂齡族 KTV 應用程式
│   │   ├── kahoot_clone/         # 互動式教學測驗系統
│   │   ├── Group2_UX/            # 使用者體驗設計專案
│   │   ├── 多變量分析/           # 學術統計：多變量方法應用
│   │   ├── 資料庫系統/           # 資料庫設計與 SQL 實作
│   │   └── course_materials/     # 各類學術課程教材與作業
│   ├── academic_stats/           # 統計系專案 (Academic Statistics Laboratory)
│   │   ├── Project4_Discriminant_Logistic/ # Proj 4 信用風險評分實證專案 (新整理 ✨)
│   │   │   ├── data/             # SPSS SAV 原始與測試資料集
│   │   │   ├── Project 4報告繳交注意事項.docx
│   │   │   ├── Project4_羅吉斯迴歸分析報告.docx
│   │   │   └── project4_report.docx # 最終生成之 Word 實證研究報告
│   │   ├── Project3_Cluster_Analysis/     # Proj 3 集群分析生活型態研究
│   │   └── Project2_Factor_Analysis/      # Proj 2 因素分析研究
│   ├── Orbit3_Training_Reference_Center/  # Orbit 3.0 操作手冊自動化產出 (V3 強化版)
│   ├── OMS_CIO_Training_Manual/  # OMS CIO Portal 訓練手冊標準化專案
│   ├── QA_Orbit_TMS/             # Orbit TMS 全模組自動化測試 (核心)
│   │   └── scripts/              # 包含新增的 ADF 格式轉換工具 (gen_adf.js)
│   ├── Process_Driven_UAT/       # 業務流程驅動之 UAT 測試框架
│   ├── ikea/                     # IKEA 消費者行為數據分析
│   ├── logistics_intern/         # 永聯物流開發 (ALP) 實習相關業務
│   └── agent_dashboard/          # 代理人系統監控介面
├── orbit_reports/                # Orbit 報表與計畫 (集中存放 TMS 匯出 Excel)
├── data_analysis_scripts/        # 分析腳本與輸出結果 (Python 腳本、JSON/TXT 輸出)
├── documents/                    # 參考文件與簡報 (PDF, Docx)
├── scripts/                      # 通用開發工具與數據處理腳本
├── agents/                       # 代理人架構、角色與工作流定義
├── scratch/                      # 臨時草稿與模型實驗腳本 (Scratchpad & Experiments)
├── 幹部訓練教材/                 # 幹部訓練教材專區 (新建立 ✨)
│   ├── 01_Data/                  # 原始資料集 (CSV, Excel)
│   ├── 02_Notebooks/             # Jupyter Notebooks (教用與幹訓版)
│   └── 03_Presentations/         # 教學簡報與 HTML 匯出檔
└── README.md                     # 本說明文件
```

## 📈 專案進度看板 (Project Status)

### 🎯 當前核心專案 (Active Project)
*   **ALP Global Internship Programme**：🚀 **準備中**。2026 Cohort 1 畢業影片 (Graduation Video) 腳本企劃與製作。
*   **全家專案 (FamilyMart Project)**：🚀 **準備中**。追蹤全家專案各流程功能交付計畫 (v4.1)。

### 🚚 企業級物流開發 (Enterprise Logistics)
*   **QA Orbit TMS**：🚀 **持續進行中**。成熟運行中，持續追蹤 UAT 議題。
*   **Orbit 3.0 / OMS CIO Portal**：✅ 訓練手冊已發佈與完成。

### 🏆 競賽與專案歸檔 (Archived Projects)
*   **幹部訓練教材 (Cadre Training)**：✅ **已完成**。教材製作與實際授課已於 8/1 順利結束。
*   **EcoReceipt (政大黑克松)**：✅ **5月已完賽**。
*   **Nestle 物流優化**：✅ **6月初已完成**。
*   **IKEA WTP Analysis**：✅ **6月底已完成**。
*   **永豐金控競賽 & PestAway**：✅ 企劃完成/階段性結案。
*   **學術統計 Proj 3 & 4**：✅ 實證研究與報告皆已完成。

---

## 🤖 多代理人協作體系 (Agent Ecosystem)

本工作區採用層級化的代理人架構，確保從策略規劃到代碼實作都有專屬專家把關：

### 🏛️ 核心決策層 (L1 & L2)
| 代理人 | 角色 | 核心職責 |
| :--- | :--- | :--- |
| **[Orion (奧萊恩)]** | **系統架構師 (Architect)** | 負責系統全域設計、工作區結構維護與新代理人生成。 |
| **[Nova (諾娃)]** | **專案經理 (PM)** | 任務進度追蹤、上下文對齊、資源調度與 L3 代理人派發。 |
| **[Apollo (阿波羅)]** | **產品經理 (PdM)** | 產品探索、PRD 撰寫、ROI 評估與 MVP 範疇定義。 |

### 🛠️ 專業執行層 (L3)
| 代理人 | 角色 | 核心職責 |
| :--- | :--- | :--- |
| **[Athena (雅典娜)]** | **商業分析師 (BA)** | 商業邏輯分析、數據解讀、業務場景拆解。 |
| **[Neo (尼歐)]** | **開發工程師 (Dev)** | 撰寫代碼、Debug、功能實作與自動化腳本。 |
| **[Aegis (神盾)]** | **測試工程師 (QA)** | 測試計畫、UAT 執行、Bug 追蹤與質量報告。 |
| **[Lumen (露明)]** | **數據分析師 (DA)** | 數據清洗、統計分析、可視化呈現與洞察產出。 |
| **[Iris (艾莉絲)]** | **技術記者 (Reporter)** | 週報彙整、Notion 同步、模組簡報與教育訓練手冊。 |
| **[Lyra (萊拉)]** | **UX 設計師 (UX)** | 介面動線設計、視覺原型與使用者體驗優化。 |
| **[Atlas (阿特拉斯)]** | **資料工程師 (DE)** | 底層數據架構、ETL 腳本撰寫與資料庫 Schema 維護。 |

---

## 💡 使用指南 (Usage Guide)

為了發揮本工作區的最大效能，請參考以下協作建議：

### 1. 如何啟動代理人 (How to Interact)
*   **啟動特定專家**：當您有特定需求時，可以直接點名代理人。
    *   *範例：「Neo，幫我寫一個數據清洗腳本。」*
    *   *範例：「Lumen，這份統計資料的集群分析顯著性如何？」*
*   **跨代理人交接**：我 (Orion) 會負責監督大型任務的交接。例如當 Neo 完成代碼後，我會指示 Aegis 進行測試。

### 2. 專案導航與開發路徑 (Project Navigation)
*   **開發新功能**：請統一在 `projects/` 下對應的子目錄執行。
*   **資源引用**：若需參考物流業務邏輯，請查閱 `projects/Orbit3_Training_Center/`。
*   **數據處理**：原始資料存放於對應專案的 `data/` 目錄，臨時實驗腳本存放於 `scratch/`，確保開發與實驗環境整潔。

### 3. 標準工作流 (Standard Workflow Loop)
1.  **需求探索**：由 **Apollo (PdM)** 撰寫 PRD 或 MVP 規劃。
2.  **實作與開發**：由 **Neo (Dev)** 執行編碼。
3.  **質量驗證**：由 **Aegis (QA)** 執行 UAT 測試並產出報告。
4.  **同步與交付**：由 **Iris (Reporter)** 將成果同步至 Notion 並產出最終簡報或手冊。

### 4. 雲端同步機制 (Syncing with Notion)
*   所有競賽報告與週報，Iris 會自動同步至您指定的 Notion 頁面。
*   若需更新 Notion，請對 Iris 下達指令：「Iris，同步最新的 UAT 報告到 Notion。」

## 🛠️ 技能與工具箱 (Skills & Tools)

本系統整合了多項專門技能 (Skills) 與外部服務 (MCP)，以實現高度自動化。

### 🧩 核心技能庫 (Skills Library)
| 技能名稱 | 用途說明 | 適用代理人 |
| :--- | :--- | :--- |
| `data-analyst` | SQL、Pandas 數據分析與統計建模。 | Lumen (DA) |
| `notion-reporter` | 自動將工作日誌與報告同步至 Notion。 | Iris (Reporter) |
| `alp-presentation` | 依照 ALP 品牌規範自動生成專業簡報。 | Iris (Reporter) |
| `orbit-uat-sop` | Orbit TMS 系統專屬的自動化測試標準程序。 | Aegis (QA) |
| `senior-qa` | 通用軟體品質測試與 E2E 規劃策略。 | Aegis (QA) |
| `playwright-automation` | 網頁自動化操作與模擬用戶行為。 | Neo (Dev) |
| `business-analyst` | 商業邏輯拆解與 PRD 規格文件撰寫。 | Athena (BA) |
| `agile-product-management` | 產品優先級排序與 MVP 開發循環管理。 | Apollo (PdM) |

### 🔌 外部整合服務 (MCP Servers)
透過 Model Context Protocol (MCP)，代理人可以直接操作以下外部工具：
*   **Notion MCP**: 建立、讀取與更新您的 Notion 工作區。
*   **Atlassian MCP**: 操作 Jira 任務與 Confluence 文件（主要用於 Orbit 專案管理）。
*   **CloudRun MCP**: 快速部署 MVP 應用程式至 Google Cloud。

---

## 🏗️ 技術底層邏輯說明 (For Statistics Students)

*   **資料隔離性 (Data Isolation)**：本次整理將 `projects/academic_stats/Project4_Discriminant_Logistic/` 中的數據資料統一歸檔於 `data/` 子目錄，程式腳本和最終 Word 報告放在專案根部，這是軟體工程中「**關注點分離 (Separation of Concerns)**」的經典實踐。
*   **雙模型實證**：邏輯斯迴歸（Logistic Regression）使用最大概似估計（MLE）解出 $\beta$，而區別分析（Discriminant Analysis）則假設各組別之自變數呈多元正態分佈且共變異數矩陣相等，利用 Fisher 線性區別函數進行分類。本專案已產出完整檢定表。
*   **ADF 文件格式轉換**：`projects/QA_Orbit_TMS/scripts/gen_adf.js` 運用 Node.js 的檔案系統（`fs`）與正規表示式（Regex）將 Markdown / Jira 標記語法自動轉譯成 Atlassian Document Format (ADF) JSON 結構，這是對接 Confluence API 所需的底層資料交換格式。

## 📒 專案術語表 (Project Glossary)

| 術語 | 領域 | 定義與說明 |
| :--- | :--- | :--- |
| **TMS** | 物流 | **Transportation Management System** (運輸管理系統)。指 Orbit 3.0 等用於管理車輛、工單與回單的系統。 |
| **UAT** | 軟體測試 | **User Acceptance Testing** (使用者驗收測試)。模擬真實用戶操作以確認系統功能符合預期。 |
| **WTP** | 商業分析 | **Willingness to Pay** (支付意願)。在 IKEA 專案中指消費者對特定商品或服務願意支付的最高價格。 |
| **集群分析** | 統計學 | **Cluster Analysis**。多變量分析技術，將相似特徵的受訪者（如：年輕族群生活型態）歸類。 |
| **GTM** | 策略規劃 | **Go-To-Market Strategy**。市場進入策略，定義產品如何觸及目標客戶（常見於 EcoReceipt 報告）。 |
| **EDA** | 數據科學 | **Exploratory Data Analysis** (探索性數據分析)。在執行正式統計模型前的數據清洗與視覺化預檢。 |

## 🔄 文檔維護規範 (Maintenance Rules)

為了平衡資訊即時性與 Token 消耗，本 README 採「觸發式更新」，僅在以下情況由 **Orion (Architect)** 進行修訂：

1.  **結構性變動 (Structural Change)**：當 `projects/` 下新增或移除主要專案目錄時。
2.  **里程碑達成 (Milestone Reach)**：當重大專案（如黑克松、競賽）進入下一個階段（如從「規劃中」轉為「開發中」）時。
3.  **代理人異動 (Agent Update)**：代理人職責有重大調整或新增核心技能 (Skills) 時。
4.  **外部連結更動 (Link Update)**：Notion 儀表板或關鍵規格文檔的 URL 發生異動時。

> [!NOTE]
> 2026-06-24: 由 Orion (Architect) 執行工作區環境整理，統一歸檔 `projects/` (IKEA專案與學術素材), `orbit_reports/` (TMS相關報表), `data_analysis_scripts/` (分析腳本與輸出) 等零散檔案。
> 2026-07-28: 由 Orion (Architect) 執行工作區環境整理，建立 `幹部訓練教材/`，並歸檔零散文件至 `documents/`。
> 2026-08-03: 由 Orion (Architect) 更新 README，將「幹部訓練教材」專案標記為已完成，移至歸檔區。

---
*最後更新時間：2026-08-03*
