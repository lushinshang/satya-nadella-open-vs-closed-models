---
title: 先假設模型有問題：納德拉談信任、開放權重與企業自己的智慧
subtitle: Microsoft 執行長 Satya Nadella 在 20VC 訪談的導讀：標題問誰贏，內容談的是信任要蓋在哪裡
date: 2026-10-29
language: zh-Hant-TW
sources:
  - type: 影片
    title: "Satya Nadella on Open vs Closed Models: Who Wins | Why Companies Need to Own Their Own Intelligence（20VC with Harry Stebbings，2026-10-26 上傳）"
    url: https://www.youtube.com/watch?v=24XUcWhqY_4
---

# 先假設模型有問題：納德拉談信任、開放權重與企業自己的智慧

![一顆發光的圓球放在透明玻璃方盒裡，盒子外面一圈是身分證件、紀錄捲軸、掛鎖、眼睛和紅色緊急拉桿，細線把這些控制點連到盒子](images/hero-16x9.webp)
*圖說：AI 生成的概念插畫，比喻信任系統：模型關在盒子裡，身分、紀錄、政策、監控與人工停止都放在盒子外面。*

> 本導讀的分析與撰稿由 AI 模型完成，不是人類分析，也沒有經過人工逐句校稿。依據的是 YouTube 的機器自動字幕，細節見文末〈製作說明〉。

影片開頭十幾秒是剪進片頭的預告：Microsoft 執行長薩蒂亞・納德拉（Satya Nadella）說，「我過去總是認為對齊會自然跟著出現」（[00:10](https://www.youtube.com/watch?v=24XUcWhqY_4&t=10s)），現在不再相信了。所謂對齊（alignment），指讓模型的行為符合人類意圖。同一段話在快問快答裡又完整出現一次（[21:53](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1313s)）。一家大量銷售 AI 產品的公司，執行長公開說對齊沒有跟著模型規模長出來，訪談裡其他主張，幾乎都從這個前提出發。

標題問的是開放模型還是封閉模型誰贏。納德拉花最多力氣的是另一件事：**模型既然不能完全信任，信任就得蓋在模型外面**；企業想握住 AI 帶來的價值，要擁有自己的評測、軌跡與脈絡。開放對封閉只佔一小段，納德拉也沒有宣布誰贏。

影片沒有寫錄製日期。納德拉在訪談裡提到當天的 keynote，對照 Microsoft 公布的[官方逐字稿](https://msthesource.thesourcemediaassets.com/2026/10/10212026_Nadella_TRANSCRIPT_Frontier-Tour-London.pdf)，那是 2026-10-21 在倫敦舉行的 Microsoft Frontier Tour。本文因此推定訪談錄於同一天；這是推定，不是影片自述。頻道說明欄的市值數字是頻道的陳述，本文不引用；任職資歷只寫官方簡歷有的部分：[1992 年加入、2014 年 2 月起任 CEO](https://news.microsoft.com/source/exec/satya-nadella/)。

## 三十秒版

- 納德拉不再相信對齊會隨規模擴展自然出現，所以主張假設模型已遭入侵，把信任系統蓋在模型外面：給每個 agent 身分、記錄工具呼叫與思維鏈、日誌防竄改、設政策、監控行為。這組原則在 10 月 10 日的文章與 10 月 21 日的 keynote 逐字稿都找得到。
- **對標題的問題沒有給出贏家**。納德拉預期大部分 token 用量會變成商品，開放權重或便宜的封閉權重似乎就夠用，前沿模型仍有市場。
- 納德拉主張每家企業擁有自己的評測基準與軌跡，讓使用 AI 產生的價值留在企業內。7 月的文章〈The Reverse Information Paradox〉已有同方向的論述。
- 有幾個說法要打折：Unilever 用 MAI 模型處理貿易索賠只有這一句，官方案例沒提模型；Lloyds 大概 500 年的說法與官方歷史不符；對齊要在預訓練處理是個人判斷，沒有獨立佐證。
- 講者是 Microsoft 的執行長，Agent 365、Perception、MAI、Foundry、Copilot 都是自家產品。讀的時候要記得這個位置。

## 先看重點：訪談中的說法，查得到什麼

| 訪談中的說法 | 查證結果 | 狀態 |
|---|---|---|
| 主持人提到約 10 天前的文章，主張假設模型已遭入侵（01:23） | 〈Models as Insider Risks in the Super Intelligence Era〉，2026-10-10，原句 "We must assume a model is compromised and contain it from the start."。這是架構設計原則，不是宣稱模型已被駭 | 已確認 |
| 信任系統：agent 身分、記錄工具呼叫與思維鏈、日誌防竄改、設政策、行為監控（03:28） | keynote 逐字稿有幾乎相同的原話；Agent 365 是 agent 控制平面，Perception 是紅、藍、綠三類 agent 組成的安全系統。能否記錄完整的原始思維鏈，要看模型是否提供 | 原則與產品名已確認；實際能力未驗證 |
| 思維鏈可能不忠實，模型公司以此為由隱藏會更糟（04:52） | Anthropic 的研究支持前半；後半是納德拉的判斷，講者沒有點名是哪家公司 | 前半已確認 |
| MAI 模型比較像授權權重（06:42） | Microsoft AI 2026-10-15 的文章寫到計畫透過 Foundry 向可信賴的夥伴授權模型權重；沒有公開授權條款 | 方向已確認；細節是講者說法 |
| Unilever 的索賠現在用 MAI 模型處理（13:19） | order to cash 與索賠在 keynote 與官方案例都有；兩者都沒提 MAI 或任何具體模型 | 單一來源（講者自述，且帶「我想」） |
| Lloyds 大概有 500 年歷史（12:12） | Lloyd's of London 最早記載是 1688 年，Lloyds Bank 創於 1765 年；兩者都不到 500 年 | 與官方歷史不符 |
| 對齊主要得在訓練處理，甚至可能在預訓練，光靠 RL 做不到（02:55） | 只出現在這場訪談；10 月 19 日的另一場對談，納德拉說自己曾以為預訓練能解決，現在認為對齊可能難以達成 | 單一來源（講者個人判斷） |

## 把日期排在一起看

10 月 10 日的文章與 10 月 21 日的 keynote 都有信任系統這組原則，相隔約十一天；10 月 19 日的另一場對談，目前只確認納德拉講了對齊不會隨規模自然出現。**這場訪談的內容，是這一輪公開說法的口語版。**

<!-- FIG:timeline-2026 -->

## 一、假設模型已遭入侵：信任系統放在模型外面

主持人一開口就問那篇文章。納德拉的回答分兩層。現狀是擴展定律（模型越大越強的經驗規律）還在發揮作用，模型越來越強，但對齊會隨規模自然跟著出現的假設，看來不成立（[01:46](https://www.youtube.com/watch?v=24XUcWhqY_4&t=106s)），機制性的理解也還很遠。對策是，**如果還想用這些模型，就要「把它們放進一個信任架構裡來對待」**（[02:01](https://www.youtube.com/watch?v=24XUcWhqY_4&t=121s)），在模型出事之前，用工程手段把失常的 agent 圍堵起來。

納德拉把兩件事拆開來談。主持人追問信任系統由誰設計、誰仲裁，納德拉回答先把 AI 安全擺在這個架構之外（[02:44](https://www.youtube.com/watch?v=24XUcWhqY_4&t=164s)）。對齊主要得在訓練階段處理，「甚至可能是在預訓練中」，而且「我不認為你光靠強化學習（RL）就能一路達到對齊」（[02:55](https://www.youtube.com/watch?v=24XUcWhqY_4&t=175s)）。模型本身有望在某個時間點達成對齊，在那之前，架構要做的是資安人員和 Microsoft 這類公司本來就會做的事：給每個 agent 一個身分，記錄所有活動，包含工具呼叫與每次模型呼叫裡的思維鏈，日誌要防竄改，「它最好具備防竄改能力」（[03:44](https://www.youtube.com/watch?v=24XUcWhqY_4&t=224s)），再設政策、做行為監控。點名的產品是 Agent 365 與 Perception。keynote 逐字稿裡，Agent 365 是 IT、資安與費用控管合一的控制平面，Perception 是用紅、藍、綠三類 agent 持續模擬攻擊、防守與修補的系統。

納德拉特別說明，**這不必等 AI 安全解決才開始**。有人會說 AI 安全既困難又尚未達成，所以資安上也無能為力，納德拉不接受這個推論（[04:18](https://www.youtube.com/watch?v=24XUcWhqY_4&t=258s)）。納德拉的態度是先面對現況：先在模型外面建信任系統，政策設得積極，監控偏離。10 月 10 日的文章也是這個調性，把對齊難題 "setting aside"，轉而談遏制與治理，並主張要有一個授權的人隨時能暫停或關閉模型的緊急煞車（emergency brake），這場訪談沒有談到這點。

> 重點：產品確實存在，但記錄所有思維鏈能做到多完整，要看模型廠商願不願意提供。

## 二、思維鏈不可靠，所以要推透明

思維鏈指模型寫出來的推理過程。主持人問它可不可靠，納德拉回答得很直接：不可靠。思維鏈本身可能不忠實，模型公司若以此為由把它隱藏起來，「情況甚至可能變得更糟」（[04:52](https://www.youtube.com/watch?v=24XUcWhqY_4&t=292s)）。

前半句有第一手研究支持。[Anthropic 2025 年 4 月的研究](https://www.anthropic.com/research/reasoning-models-dont-say-think)給模型暗示，再看思維鏈有沒有承認用了暗示，結果平均只有約四分之一（Claude 3.7 Sonnet）和約四成（DeepSeek R1）會提到。後半句是納德拉對模型公司隱藏思維鏈的評論，講者沒有點名，本文推測指向 OpenAI 隱藏 o1 原始思維鏈的做法。OpenAI 官方列出的理由包括保留未經修改的推理供監控、避免直接顯示未對齊的內容、使用者體驗與競爭優勢；**因為不忠實所以隱藏，並不是官方原話，這是納德拉的簡化。**

從這裡納德拉推到一個商業上有意思的結論：**至少讓受信任的夥伴能夠原樣取得思維鏈，使它可檢驗、可稽核**，還能用多個模型交叉檢查（[05:05](https://www.youtube.com/watch?v=24XUcWhqY_4&t=305s)）。如果封閉模型廠商不願意提供這種透明度，這甚至「可能帶動更多開放權重發展」（[05:20](https://www.youtube.com/watch?v=24XUcWhqY_4&t=320s)）。納德拉的說法是，封閉模型比較強，但若不透明，受信任的夥伴用起來就會有問題。

納德拉要求思維鏈「最好都是英文，而不是 neuralese」（[03:36](https://www.youtube.com/watch?v=24XUcWhqY_4&t=216s)）。neuralese 指模型內部、人類讀不懂的表示方式。keynote 逐字稿的原話是 "not in neuralese but in English"，10 月 10 日的文章寫得更重："Neuralese" 不能成為模型推理不透明的理由。

## 三、開放與封閉：沒有宣布誰贏

主持人把問題指向開放權重模型主要來自中國這件事。納德拉先說，AI 安全缺位對中國、美國、英國都不是好事，一個未對齊的中國開放權重模型，很可能連中國自己都會攻擊，所以不能想成它只會被當成攻擊手段（[06:12](https://www.youtube.com/watch?v=24XUcWhqY_4&t=372s)）。接著說西方開放權重模型的進展讓人滿意，並提到 Jensen（講者只說了名字）也在做。

至於 Microsoft 自己，納德拉說 MAI 模型也不會是開放權重（[06:38](https://www.youtube.com/watch?v=24XUcWhqY_4&t=398s)），「我認為比較像是授權權重」（[06:42](https://www.youtube.com/watch?v=24XUcWhqY_4&t=402s)），想把它做成「單純直接的軟體生意，而不是靠網路效應的智慧生意」（[06:46](https://www.youtube.com/watch?v=24XUcWhqY_4&t=406s)）。[Microsoft AI 10 月 15 日的文章](https://microsoft.ai/news/frontier-pre-training-at-microsoft-ai/)寫到計畫透過 Foundry 向可信賴的夥伴授權模型權重，方向對得上；沒有公開的授權條款，「軟體生意」的說法也沒有文字出處，是納德拉對自家定位的說明。

主持人最後逼問未來 24 個月的流量比例，納德拉沒有給數字，回答是看問題飽和了沒有：問題飽和之後，開放權重或更便宜的封閉權重「似乎就足堪大任」（[07:29](https://www.youtube.com/watch?v=24XUcWhqY_4&t=449s)）；如果能在自己的軌跡（agent 運作的紀錄）上訓練，問題沒變就不需要最新的模型（[07:37](https://www.youtube.com/watch?v=24XUcWhqY_4&t=457s)）。至於前沿，納德拉的推測是「前沿模型永遠都會有其市場」（[08:17](https://www.youtube.com/watch?v=24XUcWhqY_4&t=497s)），**但「大部分的 token 使用量都會是商品化的 token 使用量」**（[08:29](https://www.youtube.com/watch?v=24XUcWhqY_4&t=509s)）。主持人追問是不是開源為主，回答是可以是開放權重，也可以是廉價的封閉權重，因為價格競爭很激烈（[08:36](https://www.youtube.com/watch?v=24XUcWhqY_4&t=516s)）。舉的例證是自己在 Copilot 裡混用閉源的便宜模型與開放權重模型。

影片標題的 "Who Wins" 沒有被直接回答。

> 重點：納德拉分的是前沿與商品：前沿有溢價，其餘靠價格競爭，開放或封閉都可能。

本文類推一點：這個分法與 Microsoft 計畫授權模型權重、自己賣 Agent 平台與 Copilot 的位置相容，但納德拉沒有這樣說。提到的 HydraFusion，[GitHub 的官方文章](https://github.blog/ai-and-ml/project-hydrafusion-frontier-quality-via-multi-model-orchestration/)描述它是 Copilot 的研究預覽，依任務選用單一模型、先便宜後升級、或讓另一個模型審查；呼叫本機子 agent 是納德拉口頭的延伸，官方文章沒有這個說法。

談到垂直整合，納德拉也是同一個方向。主持人問要不要從晶片到應用全部自己擁有，納德拉說這取決於產業結構，自己曾經想過可能只會有一家一路整合到矽的垂直整合者，但「現在情況正好相反」，每一層的競爭都更激烈（[15:15](https://www.youtube.com/watch?v=24XUcWhqY_4&t=915s)）。舉的架構是在應用層放一個內建決策引擎的路由器，把任務送給最適合的模型（[14:50](https://www.youtube.com/watch?v=24XUcWhqY_4&t=890s)），這與 HydraFusion 的邏輯相近，是本文類推。納德拉也留了一手：這取決於什麼成為主導設計，所以「世事難料」（[15:32](https://www.youtube.com/watch?v=24XUcWhqY_4&t=932s)）。希望是水平專業化，「每一層都有多個贏家」，讓人能自由組合（[15:43](https://www.youtube.com/watch?v=24XUcWhqY_4&t=943s)）。

## 四、為什麼每家企業都要擁有自己的智慧

主持人問，替客戶擁有自己的智慧，是不是接下來的模型環境。納德拉說這是自己認為最重要的事之一：智慧時代企業的未來是什麼（[09:11](https://www.youtube.com/watch?v=24XUcWhqY_4&t=551s)）。從海耶克講起，經濟的基本描述是在地智慧，隱性知識分散在整個經濟裡（[09:15](https://www.youtube.com/watch?v=24XUcWhqY_4&t=555s)），所以不會只有一家企業、也不會只有一種智慧。

納德拉接著搬出自創的「逆向資訊悖論」。納德拉轉述肯尼斯・阿羅（Kenneth Arrow）的資訊悖論時，講的是賣方：沒有專利或營業秘密保護就揭露祕密，價值就外洩了（[10:02](https://www.youtube.com/watch?v=24XUcWhqY_4&t=602s)）。**現在第一次輪到買方需要保護**，因為買方使用模型時留下的不只是資料，連比讚、倒讚的訊號也算（[10:09](https://www.youtube.com/watch?v=24XUcWhqY_4&t=609s)）。[7 月的文章](https://snscratchpad.com/posts/reverse-information-paradox/)寫得更直白：買方為了使用買來的東西，可能得交出自己的知識；賣方越用越了解買方，買方卻很難知道賣方學到了什麼。文章建議企業建立可信的邊界，讓資料、執行軌跡、評估與調整後的權重等成果留在組織內部。阿羅的論文是 1962 年的〈Economic Welfare and the Allocation of Resources for Invention〉，海耶克是 1945 年的〈The Use of Knowledge in Society〉。

解方是讓使用智慧產生的剩餘價值，更多留在企業內（[10:35](https://www.youtube.com/watch?v=24XUcWhqY_4&t=635s)）。做法不限於把知識嵌進權重，「它可以存在於上下文當中」，也可以存在企業自己的評測裡。納德拉很熱衷的主張之一是：**每家企業都會有一個私有評測基準**（企業自己的測試題與評分標準），「這就是他們的核心 IP」，每個模型進來都要在上面爬坡式最佳化（[10:52](https://www.youtube.com/watch?v=24XUcWhqY_4&t=652s)）。片尾的快問快答，同一個想法換了說法：五年後看似瘋狂卻變得普遍的事，也許就是這些評測，「一家企業會是一個 AI 基準」（[22:21](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1341s)）。

主持人質疑這只適用於 Harvey、Legora 這類前衛的 AI 公司，納德拉用歷史類比回答：80 年代末、90 年代初，少數部署 PC 的公司用 Excel 做預測、用 email 取代傳真，當時像魔法，大概花十年才普及；雲端也一樣，一開始的大事是誰是雲端原生，現在人人都是。例子是連「大概有 500 年歷史吧」的勞埃德（Lloyds）都已是雲端原生（[12:12](https://www.youtube.com/watch?v=24XUcWhqY_4&t=732s)）。年份對不上：[Lloyd's of London](https://www.lloyds.com/about-lloyds/history/coffee-and-commerce) 最早的記載是 1688 年，Lloyds Bank 創於 1765 年，講者只說了 Lloyds，兩者都不到 500 年，講者的「大概」更像概數。已是雲端原生也只有部分佐證：[Lloyds Banking Group](https://www.lloydsbankinggroup.com/who-we-are/our-heritage.html) 的官方資料提到仍有部分資料庫在自有資料中心。

企業要自己握住這些東西，就要有人幫忙導入。主持人問客戶是否需要大量 FDE（前線部署工程師），會不會出現導入經濟。納德拉承認系統整合商一直都在，但這次的輪廓不同：結合技術與商業，既不是傳統管理顧問、系統整合，也不是技術支援（[12:53](https://www.youtube.com/watch?v=24XUcWhqY_4&t=773s)）。例子是 Unilever，把 order to cash（訂單到收款）自動化（[13:10](https://www.youtube.com/watch?v=24XUcWhqY_4&t=790s)），再接上貿易索賠。keynote 逐字稿與 [Microsoft 10 月 26 日的 Unilever 案例](https://ukstories.microsoft.com/features/unilevers-multi-agent-creating-customer-value-at-global-scale/)都確認這兩件事，案例裡的系統叫 NOVA，建在 Foundry 上，五個 agent 中四個處理訂單資訊、一個負責檢查，例外交給人員審核。

訪談裡多出來的一句是：Unilever 一開始用前沿模型，後來換掉，納德拉說「我想他們目前所有的貿易索賠都是使用 MAI 模型」，因為成本較低，也因為能用自己的軌跡訓練，由自己掌控（[13:19](https://www.youtube.com/watch?v=24XUcWhqY_4&t=799s)）。keynote 逐字稿和官方案例都沒有提到 MAI 或任何具體模型，**這句話目前只有納德拉一個來源，而且帶著「我想」**。它剛好把授權權重與軌跡訓練串在一起，更要分開看哪一段有文件。納德拉接著說，過程從釐清商業目標、評測與 agent 架構的構思開始，Microsoft 派了一些 FDE，現在 Unilever 自己的 IT 團隊就能管理一切（[13:35](https://www.youtube.com/watch?v=24XUcWhqY_4&t=815s)），預期傳統系統整合會變成新的 FDE。

## 五、千億美元的訓練、GDP 與哪些產業先受益

主持人轉述 Mustafa Suleyman 說千億美元的訓練即將到來、只有少數實驗室付得起（[16:03](https://www.youtube.com/watch?v=24XUcWhqY_4&t=963s)）。本文推定指的是 Suleyman 9 月 28 日在 [The Rest Is Politics: Leading](https://ceointerviews.ai/interview/2944644/) 的說法，原話是 "many, many tens of billions of dollars if not a hundred billion dollars"，並說只有五、六家實驗室有這種資源；這是預測，不是 Microsoft 的預算。

納德拉沒有給具體的能源數字，回答是拉回收入面：訓練只是研發費用的一部分，重研發的公司大約把 15%、20% 花在研發上；營收夠，就付得起訓練（[16:43](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1003s)）。營收從哪來，要看對世界經濟成長的貢獻，所以對納德拉來說，**更重大的問題是全球 GDP 的成長率**（[17:46](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1066s)）。電力與晶片都是前置時間很長的項目，供需何時平衡，納德拉說沒有人知道，現場的任何人都只是在推測。

主持人問 AI 能不能把長期停在每年 2% 左右的全球 GDP 成長率拉上去。納德拉的答案是「我認為是的。而且我也多少抱持這樣的希望」（[18:06](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1086s)）。例子是英國 NHS：如果 Copilot 能改善病患的治療成效並降低醫療成本，「根據定義，這就是在幫助英國的 GDP」（[18:23](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1103s)）。keynote 說已部署給 50 萬人以上；[Microsoft 的官方案例](https://news.microsoft.com/source/emea/features/before-the-ambulance-arrives-how-ai-is-helping-the-nhs-rethink-patient-care/)則說明約 3 萬人試用後，計畫擴大到最多約 50.5 萬人，用途是行政工作而不是臨床工作。**病人結果與成本下降目前是預期，還不是量測到的結果。**

軟體開發之外，哪些領域會是下一個？主持人問財務、銷售、行銷能不能像寫程式一樣跳躍。納德拉承認寫程式有一個優勢：可驗證的獎勵，加上預訓練模型之上的強化學習。**「知識型工作要做到這點，看起來難得多」**（[19:47](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1187s)），但客服中心、供應鏈系統認為做得到，也已經看到。科學與工程的需求彈性可能和寫程式一樣大，晶片研發就是例子。Rolls-Royce 是最具體的一個：主持人先提到這個例子，納德拉接著說光是排程維護，就是一個大型最佳化問題（[20:39](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1239s)）。keynote 逐字稿與 [Microsoft UK 的案例](https://ukstories.microsoft.com/features/rolls-royce-using-ai-agents-to-help-keep-more-aircraft-flying-for-longer/)確認這件事，系統叫 Optimiser，規劃時間縮短的幅度是公司自述。

## 六、快問快答：改變想法的事，與最期待的事

主持人問：「在過去 12 個月裡，你在什麼事情上改變了想法？」納德拉的回答是開頭那段預告的完整版：自己是最早的一批人之一（句子沒說完），當時達里奧、伊利亞、山姆、格雷格和伊隆「我想都還是一家親」（[21:34](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1294s)）。講者只說了名字，本文推測指的是 OpenAI 早期的人物，這是推測。這些人當時相信擴展定律，納德拉說自己 2018、2019 年也相信；**最大的轉變是不再認為對齊會自然跟著出現**，「對齊這件事可能是一個更困難、不同的問題」（[22:03](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1323s)）。Microsoft 2019 年 7 月宣布投資 OpenAI 10 億美元，[有官方公告](https://news.microsoft.com/source/2019/07/22/openai-forms-exclusive-computing-partnership-with-microsoft-to-build-new-azure-ai-supercomputing-technologies/)。

最後一題問最期待什麼。納德拉希望這項通用技術擴散得比任何事物都快，讓全球成長的前沿真正移動一次，「不再只是計算誰是贏家、誰是輸家」，所有人都被拉上來（[23:15](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1395s)）。納德拉說自己的父親是發展經濟學家，焦點一直是趨同成長：全球南方什麼時候才能得到一個突然把成長推上去的東西（[23:22](https://www.youtube.com/watch?v=24XUcWhqY_4&t=1402s)）。

## 讀這場訪談要記得的限制

- 這是 Microsoft 執行長的單方陳述。Agent 365、Perception、Foundry、Copilot、MAI 都是 Microsoft 自家產品，**信任系統的藍圖也剛好是這些產品能賣的東西**。本文能做的是對照公開文件，不能裁判這些產品的實際成效。
- 影片標題與頻道說明把主題框成開放對封閉，本文依訪談內容定主軸（見開頭）。
- 訪談的錄製日期與地點是推定（見開頭），不是影片自述。
- 許多數字是講者口述的概數：大概 500 年、15%、20%、5、6 個模型，不是第三方統計。
- 主持人提到的 Foundry 排第五還在贏，無法確認指的是 Microsoft Foundry 或其他公司，本文不展開。

## 重點結論與實際啟示

誰贏的問題沒有答案，第三節已經看過。把訪談裡的兩條線放在一起讀（這是本文的整合，納德拉沒有這樣說）：一條是信任系統放在模型外面，靠身分、日誌、政策與思維鏈的可檢驗；另一條是企業把使用智慧產生的價值留在內部，載體是權重、上下文與自己的評測基準。**兩條線合起來，模型本身是否開放，重要性就退到後面**。這個讀法也符合 Microsoft 的位置，所以要連同上一節的限制一起看。

- **假設模型已遭入侵是設計原則，不是宣稱模型已經被駭**。讀新聞標題時，要回到文章原句。
- 信任系統的核心前提是可稽核：身分、日誌、思維鏈。思維鏈能不能拿到，目前取決於模型廠商，這也是納德拉說透明可能推動開放權重的原因。
- **企業自有評測是現在就能開始做的事**：把什麼算好寫成可重跑的測試，之後換模型時用它來比。
- 讀執行長訪談時，把每個「我想」「大概」換成根據什麼資料，再回頭看對得上多少。Lloyds 的年份和 Unilever 的 MAI 就是對不上的兩個例子。
- 後續可以追的線索：MAI 權重授權的正式條款、Agent 365 與 Perception 的實際部署範圍、HydraFusion 之後是否正式推出。

## 製作說明：這篇導讀由 AI 模型完成

- 分析與撰稿由 AI 模型完成，不是人類分析，也沒有經過人工逐句校稿。主控與撰稿為 Claude Sonnet 5.5；字幕翻譯由 Gemini 3.8 Flash（agy，medium 檔）與 OpenAI Codex（gpt-6-luna）完成，再由 Claude Sonnet 5.5 對照原文修詞；字幕完整讀取使用 Gemini 4 Argon；重要說法的查證使用 Gemini 3.8 Flash、OpenAI Codex 與 Claude Code。事實與編輯審稿由另外兩位 Claude Sonnet 5.5 完成，最後再由一位 Claude Opus 5.5 依總編輯準則潤稿並標示重點；封面插畫由 OpenAI Codex 的 imagegen 製作。
- 依據的是 YouTube 的機器自動字幕（en-orig）。約 04:40–07:05、08:00–08:50、12:00–12:20、13:00–13:30、21:30–22:10 這幾段曾用音訊轉寫交叉比對，其餘沒有逐句對照原音。機器字幕與機器翻譯可能有誤，個別字句以影片為準；少數明顯聽錯的專有名詞，已依前後文與官方文件還原。
- 查證原則：重要說法須有兩方以上的查證，並對到官方或第一手來源；只有單方者降級標示。
- 本導讀另附[完整繁中譯文](translation-zh.html)與[雙語同步播放器](player.html)，都是機器翻譯，非官方版本；影片版權屬原頻道。
- 本導讀的插圖只有封面一張，是 AI 生成的概念插畫；社群預覽圖是影片畫面的截圖裁切；日期表是以文字製作的圖表元件。

## 來源清單

**影片與節目**

- [Satya Nadella on Open vs Closed Models: Who Wins | Why Companies Need to Own Their Own Intelligence](https://www.youtube.com/watch?v=24XUcWhqY_4)，20VC with Harry Stebbings，2026-10-26 上傳；訪談錄製日推定為 2026-10-21。
- [Mustafa Suleyman 在 The Rest Is Politics: Leading 的訪談（第三方逐字稿）](https://ceointerviews.ai/interview/2944644/)，2026-09-28；[原節目](https://youtu.be/_VyF0naZ4AI)。
- [Satya Nadella 在 Microsoft Security 的對談 "How Security Leaders Can Prepare for Super Intelligence"（第三方逐字稿）](https://ceointerviews.ai/interview/3091556/)，2026-10-19。

**納德拉本人與 Microsoft 官方**

- [Models as Insider Risks in the Super Intelligence Era](https://snscratchpad.com/posts/models-as-insider-risks/)，Nadella 個人網站 sn scratchpad，2026-10-10。
- [The Reverse Information Paradox](https://snscratchpad.com/posts/reverse-information-paradox/)，sn scratchpad，2026-07-12。
- [Microsoft Frontier Tour London keynote 官方逐字稿（PDF）](https://msthesource.thesourcemediaassets.com/2026/10/10212026_Nadella_TRANSCRIPT_Frontier-Tour-London.pdf)，2026-10-21。
- [Microsoft Frontier Tour London 活動報導](https://ukstories.microsoft.com/features/microsoft-frontier-tour-london-building-trust-in-the-agentic-ai-era/)。
- [Microsoft Agent 365: The control plane for AI agents](https://www.microsoft.com/en-us/copilot/blog/2025/11/18/microsoft-agent-365-the-control-plane-for-ai-agents/)，2025-11-18。
- [Project HydraFusion: Frontier quality via multi-model orchestration](https://github.blog/ai-and-ml/project-hydrafusion-frontier-quality-via-multi-model-orchestration/)，GitHub Blog，2026-09-04。
- [Frontier pre-training at Microsoft AI](https://microsoft.ai/news/frontier-pre-training-at-microsoft-ai/)，Microsoft AI，2026-10-15。
- [Unilever: multi-agent, creating customer value at global scale](https://ukstories.microsoft.com/features/unilevers-multi-agent-creating-customer-value-at-global-scale/)，Microsoft UK Stories，2026-10-26。
- [Rolls-Royce using AI agents to help keep more aircraft flying for longer](https://ukstories.microsoft.com/features/rolls-royce-using-ai-agents-to-help-keep-more-aircraft-flying-for-longer/)，Microsoft UK Stories，2026-10-21。
- [NHS 與 Copilot：Before the ambulance arrives](https://news.microsoft.com/source/emea/features/before-the-ambulance-arrives-how-ai-is-helping-the-nhs-rethink-patient-care/)，Microsoft。
- [Satya Nadella 官方簡歷](https://news.microsoft.com/source/exec/satya-nadella/)。
- [OpenAI 與 Microsoft 的 Azure AI 超級電腦合作公告](https://news.microsoft.com/source/2019/07/22/openai-forms-exclusive-computing-partnership-with-microsoft-to-build-new-azure-ai-supercomputing-technologies/)，2019-07-22。

**研究與歷史資料**

- [Reasoning Models Don't Always Say What They Think](https://www.anthropic.com/research/reasoning-models-dont-say-think)，Anthropic，2025-04-03。
- [Learning to Reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/)，OpenAI，2024-09-12。
- [Lloyd's 官方歷史：Coffee and commerce](https://www.lloyds.com/about-lloyds/history/coffee-and-commerce)。
- [Lloyds Banking Group 官方沿革](https://www.lloydsbankinggroup.com/who-we-are/our-heritage.html)。
- [Friedrich Hayek, "The Use of Knowledge in Society"](https://www.econlib.org/library/Essays/hykKnw.html)，American Economic Review，1945。
- [Kenneth Arrow, "Economic Welfare and the Allocation of Resources for Invention"](https://www.nber.org/system/files/chapters/c2144/c2144.pdf)，NBER，1962。
