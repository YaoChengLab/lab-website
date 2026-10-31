---
title: pxGPT（中文）
permalink: /resources/tools-data/pxgpt-tw/
---

# pxGPT 讓 AI 看植物照片，把外觀描述整理成表格

{% include figure.html image="images/projects/pxgpt-tw.jpg" %}

{% include button.html type="github" text="pxGPT on GitHub" link="YaoChengLab/pxgpt" %}
{% include button.html type="paper" text="Bioinformatics (2026)" link="https://doi.org/10.1093/bioinformatics/btag781" %}
{% include button.html type="link" text="English" link="resources/tools-data/pxGPT" %}

育種人員看一株植物，可能會寫下：「葉片圓圓的，有些皺，顏色鮮綠。」這些觀察很有用，但當植物數量增加，逐一看、逐一記錄就很花時間。每個人的用詞不同，也讓後續比較變得麻煩。

中央研究院農業生物科技研究中心林耀正團隊開發的開源軟體 pxGPT，就是為了協助整理這類紀錄。這項研究刊登於《Bioinformatics》。pxGPT 使用能同時讀懂圖片與文字的 AI，把不同角度的植物照片，轉成有固定欄位的外觀紀錄。

它的做法，可以想成「先寫作文，再出選擇題，最後填答案」。

1. **看照片，寫描述。** AI 一起查看同一份樣本的多個角度照片，用文字描述看得到的植物特徵。
2. **把描述整理成表單。** AI 從整批描述中提出要記錄的特徵和選項，再由研究人員檢查、修改。例如，要記錄哪些葉形？每個選項代表什麼？確認後，就固定使用這份表單。
3. **再看照片，依表填答。** AI 重新查看照片，按表單規則記錄每個特徵。原本一段段的文字，就變成方便比較和統計的表格。表單也區分「沒有這個構造」和「照片看不清楚，無法判斷」。

團隊以蕓薹屬植物的照片測試 pxGPT，這個屬包括白菜、甘藍和油菜。研究人員也請多位調查員獨立判讀，並比較 AI 與人的結果。測試顯示，pxGPT 能依照固定規則產生紀錄，但判讀仍會出錯，也還沒有達到人與人之間的一致程度。同一份表單能交給不同 AI 模型使用，結果仍會有差異。

pxGPT 提供了一種整理植物外觀資料的方法：讓 AI 協助看圖和填表，再由研究人員確認結果。用於其他作物或不同拍照條件時，也需要重新測試。

本篇論文由林耀正副研究員指導，第一作者為本院農生中心博士後研究學者鄭伯忻，林耀正實驗室歐正揚、徐德昌、吳亭利、王瑞萱、吳育伶共同參與。研究經費由本院永續農學計畫支持。

**論文：** Zheng et al. (2026). pxGPT: a schema-constrained multimodal large language model framework for plant phenotyping. *Bioinformatics*. DOI：[10.1093/bioinformatics/btag781](https://doi.org/10.1093/bioinformatics/btag781)  
**軟體：** [pxGPT](https://github.com/YaoChengLab/pxgpt)
