````markdown
# 電商銷售圖 AI Prompt：產品賣點分析與圖片生成指令產生器

這是一組用於電商銷售圖策劃的 AI Prompt，可根據產品頁內容，自動整理產品核心賣點，並產出適合 AI 圖像生成工具使用的英文圖片 Prompt。

此 Prompt 適合用於：

- 電商商品頁銷售圖
- 品牌社群廣告圖
- 商品主視覺 KV
- 功能展示圖
- 生活情境圖
- AI 圖像生成素材規劃

## 功能特色

此 Prompt 會根據指定產品資料，輸出 3 個最適合轉化成銷售圖片的核心優點，並針對每個優點提供：

- 優點標題
- 銷售角度分析
- 使用模擬情境
- 可直接用於 AI 圖像生成的英文 Prompt
- 繁體中文主標題
- 繁體中文副標題
- CTA 文字
- 視覺風格指示
- 品牌模板與產品包裝保護規範
- 建議銷售圖排序

## 適用場景

此 Prompt 適合用於需要快速產出電商銷售圖方向的工作流程，例如：

- 行銷企劃產出商品賣點
- 設計師製作廣告圖前的溝通稿
- AI 圖像生成前的 Prompt 準備
- 電商平台商品圖優化
- 社群廣告素材批次產出
- 品牌商品頁視覺規劃

## Prompt 目標

此 Prompt 的核心目標不是單純整理商品資料，而是將商品資訊轉化成：

```text
產品賣點 + 銷售角度 + 生活化使用情境 + AI 圖像生成指令
````

讓使用者可以直接將輸出的英文圖片 Prompt 複製到 AI 圖像生成工具中，用於製作電商銷售圖片。

## 使用方式

將以下資訊填入 Prompt：

```text
產品名稱：你的產品名稱
產品連結：商品頁 URL
CTA：行動呼籲文字
```

範例：

```text
產品名稱：提提研保濕金箔黑面膜(Plus) 6入
產品連結：https://www.watsons.com.tw/...
CTA：立即選購
```

AI 會根據商品頁內容，整理出 3 個最適合做成銷售圖的核心賣點。

## 輸出內容

輸出格式會嚴格依照以下結構：

```text
以下 3 個賣點係根據產品頁整理：

1）優點：{{優點標題}}
銷售角度：{{銷售角度說明}}
使用模擬情境：{{具體生活化畫面}}
圖片生成 Prompt：
[Prompt 1 開始] ... [Prompt 1 結束]

2）優點：{{優點標題}}
銷售角度：{{銷售角度說明}}
使用模擬情境：{{具體生活化畫面}}
圖片生成 Prompt：
[Prompt 2 開始] ... [Prompt 2 結束]

3）優點：{{優點標題}}
銷售角度：{{銷售角度說明}}
使用模擬情境：{{具體生活化畫面}}
圖片生成 Prompt：
[Prompt 3 開始] ... [Prompt 3 結束]

建議銷售圖排序
第一張：{{主 KV 說明}}
第二張：{{功能展示說明}}
第三張：{{生活情境說明}}
```

## 品牌與產品視覺保護規範

此 Prompt 已內建品牌模板保護要求，確保 AI 生成圖片時需遵守以下規則：

```text
Must respect and follow the brand's original visual style, layout framework and existing TEMPLATE; keep typography, spacing, logo placement and graphic structure consistent with the original brand template.

Do NOT alter, modify, distort, or recreate any product packaging, product name, brand logo, or label.

Reproduce all product visuals exactly as provided in the reference images.
```

此規範可降低 AI 圖像生成時出現以下問題：

* 品牌 Logo 被改壞
* 商品包裝文字被亂改
* 產品名稱變形
* 包裝設計被重繪
* 版面風格偏離品牌模板
* 商品圖不像原產品

## 圖像 Prompt 設計原則

每一組圖片 Prompt 都會包含以下元素：

| 元素                                | 說明              |
| --------------------------------- | --------------- |
| 產品名稱                              | 明確指定生成圖片的商品     |
| 具體畫面場景                            | 讓圖片具備生活化與銷售感    |
| 使用情境                              | 讓消費者能想像使用時機     |
| 產品功能 / 賣點                         | 強化購買理由          |
| Traditional Chinese headline text | 圖片主標題           |
| Traditional Chinese subtext       | 圖片副標題           |
| Traditional Chinese CTA text      | 行動呼籲            |
| 視覺風格指示                            | 控制畫面質感與品牌一致性    |
| 品牌模板規範                            | 保護 Logo、包裝與版面架構 |

## 完整 Prompt

```text
你是一位電商銷售圖策劃及 AI 圖像生成 Prompt 專家。 
請根據以下產品資料，幫我分析產品，並輸出可直接用於生成銷售圖片的內容。

產品名稱：提提研保濕金箔黑面膜(Plus) 6入
產品連結：https://www.watsons.com.tw/%E6%8F%90%E6%8F%90%E7%A0%94-%E6%8F%90%E6%8F%90%E7%A0%94%E4%BF%9D%E6%BF%95%E9%87%91%E7%AE%94%E9%BB%91%E9%9D%A2%E8%86%9C-plus-6%E5%85%A5/p/BP_257634
CTA：立即選購

任務要求：
請先爬取 / 分析產品頁內容，整理出此產品最適合用於銷售圖片的 3 個核心優點。

每個優點都要包含：
優點標題
銷售角度
使用模擬情境
可直接用於 AI 圖像生成的英文 Prompt

每個圖片生成 Prompt 必須包含：
產品名稱
具體畫面場景
使用情境
要突出的產品功能 / 賣點
Traditional Chinese headline text
Traditional Chinese subtext
Traditional Chinese CTA text
視覺風格指示

必須加入以下品牌模板要求：
Must respect and follow the brand's original visual style, layout framework and existing TEMPLATE; keep typography, spacing, logo placement and graphic structure consistent with the original brand template. Do NOT alter, modify, distort, or recreate any product packaging, product name, brand logo, or label. Reproduce all product visuals exactly as provided in the reference images.

圖像 Prompt 要適合用於生成電商銷售圖，不是單純產品照。
情境要具體、生活化、容易視覺化，方便逐張生成銷售圖片。
語氣請用台灣繁體中文。

如產品頁有明確規格，例如尺寸、容量、重量、支援型號、材質、防水、防震、收納空間等，請盡量放入對應賣點及 subtext。

不要只列資料，要轉化成「賣點 + 使用場景 + 圖像生成指令」。

最後請提供建議銷售圖排序，說明哪一張適合作為主 KV，哪一張作功能展示，哪一張作生活情境。

輸出格式請嚴格跟以下結構：

以下 3 個賣點係根據產品頁整理：

1）優點：{{優點標題}}
銷售角度： {{用繁體中文說明這個賣點適合打中哪類消費者，以及為什麼有銷售力}}
使用模擬情境： {{描述一個具體、可視覺化的生活使用畫面}}
圖片生成 Prompt：
[Prompt 1 開始] Create a sales image for {{產品名稱}}. Scene: {{具體英文場景描述}}. Emphasize {{要突出的功能 / 優點}}.
Add headline text in Traditional Chinese: 「{{主標題}}」
Subtext: 「{{副標題}}」
CTA: 「{{CTA 文字}}」
Use {{視覺風格描述}}. Must respect and follow the brand's original visual style, layout framework and existing TEMPLATE; keep typography, spacing, logo placement and graphic structure consistent with the original brand template. Do NOT alter, modify, distort, or recreate any product packaging, product name, brand logo, or label. Reproduce all product visuals exactly as provided in the reference images. [Prompt 1 結束]

2）優點：{{優點標題}}
銷售角度： {{用繁體中文說明這個賣點適合打中哪類消費者，以及為什麼有銷售力}}
使用模擬情境： {{描述一個具體、可視覺化的生活使用畫面}}
圖片生成 Prompt：
[Prompt 2 開始] Create a sales image for {{產品名稱}}. Scene: {{具體英文場景描述}}. Emphasize {{要突出的功能 / 優點}}.
Add headline text in Traditional Chinese: 「{{主標題}}」
Subtext: 「{{副標題}}」
CTA: 「{{CTA 文字}}」
Use {{視覺風格描述}}. Must respect and follow the brand's original visual style, layout framework and existing TEMPLATE; keep typography, spacing, logo placement and graphic structure consistent with the original brand template. Do NOT alter, modify, distort, or recreate any product packaging, product name, brand logo, or label. Reproduce all product visuals exactly as provided in the reference images. [Prompt 2 結束]

3）優點：{{優點標題}}
銷售角度： {{用繁體中文說明這個賣點適合打中哪類消費者，以及為什麼有銷售力}}
使用模擬情境： {{描述一個具體、可視覺化的生活使用畫面}}
圖片生成 Prompt：
[Prompt 3 開始] Create a sales image for {{產品名稱}}. Scene: {{具體英文場景描述}}. Emphasize {{要突出的功能 / 優點}}.
Add headline text in Traditional Chinese: 「{{主標題}}」
Subtext: 「{{副標題}}」
CTA: 「{{CTA 文字}}」
Use {{視覺風格描述}}. Must respect and follow the brand's original visual style, layout framework and existing TEMPLATE; keep typography, spacing, logo placement and graphic structure consistent with the original brand template. Do NOT alter, modify, distort, or recreate any product packaging, product name, brand logo, or label. Reproduce all product visuals exactly as provided in the reference images. [Prompt 3 結束]

建議銷售圖排序
第一張：{{說明為何適合作主 KV}}
第二張：{{說明為何適合作功能展示}}
第三張：{{說明為何適合作生活情境}}

參考文件說明：
請參考以下附件進行設計：
廣告參考模板（版面風格、構圖比例請對齊此模板）
品牌 Logo（請原樣套入，不得變形或修改）
產品圖片（請原樣使用，不得更改包裝、名稱或任何視覺元素）
```

## 建議工作流程

1. 準備商品頁連結、商品名稱與 CTA。
2. 將完整 Prompt 貼入支援網頁分析的 AI 工具。
3. 檢查 AI 是否正確擷取商品規格與賣點。
4. 將輸出的 3 組英文圖片 Prompt 分別貼入 AI 圖像生成工具。
5. 上傳或指定參考素材：

   * 廣告參考模板
   * 品牌 Logo
   * 產品圖片
6. 檢查產出的圖片是否有修改產品包裝或 Logo。
7. 依建議排序製作主 KV、功能展示圖與生活情境圖。

## 注意事項

* 若 AI 工具無法讀取商品頁，請手動提供產品頁文字、圖片與規格。
* 若產品頁資訊不足，建議補充品牌官方商品說明。
* AI 圖像生成工具可能無法完全正確產生中文字，建議最後由設計工具手動置入標題、副標與 CTA。
* 商品包裝、Logo、品牌名稱與標籤應以原始素材疊入，不建議完全交由 AI 重繪。
* 產出圖片上架前，請再次確認產品宣稱是否符合商品頁與品牌官方資料。

## License

MIT

```
```
