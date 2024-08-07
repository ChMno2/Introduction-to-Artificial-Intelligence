# 什麼是 AI？

簡單來說，AI 是可模仿人類行為與能力的軟體。 主要的工作包含：

機器學習 - 這通常是 AI 系統的基礎，且是「指導」電腦模型進行預測並從資料中得出結論的方式。
電腦視覺 - 透過相機、影片和影像，以視覺方式解譯世界的 AI 功能。
自然語言處理 - 電腦解譯書寫或口語語言並做出相應回應的能力。
文件智慧 - 負責管理、處理和使用在表單和文件中找到的大量資料的 AI 功能。
知識採礦 - 從大量非結構化資料中擷取資訊，以建立可搜尋的知識存放區的 AI 功能。
生成式 AI - 可建立各種格式的原始內容 (包括自然語言、影像、程式碼等等) 的 AI 功能。

# 了解機器學習
機器學習是大部分 AI 解決方案的基礎。 自 20 世紀 50 年代以來，研究人員 (通常稱為資料科學家) 一直在研究不同的 AI 方法。 AI 的大部分新式應用程式都起源於機器學習，這是結合電腦科學和數學的 AI 分支。

讓我們先來看一個如何使用機器學習來解決難題的真實世界範例。

永續農業技術對於提高糧食生產並同時保護脆弱環境而言至關重要。 The Yield 是一間位於澳洲的農業技術公司，其使用感應器、資料和機器學習來協助農民制定與天氣、土壤和植物狀況相關的明智決策。

## 機器學習的運作方式
機器如何學習？

答案是透過資料。 在現今世界裡，我們會在日常生活時產生大量的資料。 從我們傳送的簡訊、電子郵件和社交媒體貼文，到以手機拍攝的相片和影片，都會產生大量的資訊。 而住家、車輛、城市、大眾運輸基礎結構和工廠中的數百萬個感應器也會產生更多資料。

資料科學家可使用所有資料來定型機器學習模型，並根據其在資料中找到的關聯性來進行預測和推斷。

機器學習模型會嘗試擷取資料之間的關聯性。 例如，假設環保組織希望志工使用手機應用程式來識別和分類不同的野花物種。 下列動畫顯示如何使用機器學習來實現此案例。

植物學家與科學家組成的小組在收集野生植物樣本的資料。
小組會使用正確的物種標記樣本。
標記的資料會使用演算法進行處理，以找出樣本特徵與所標記物種之間的關聯性。
演算法的結果會封裝在模型中。
當志工找到新的樣本時，此模型可識別正確的物種標籤。
AI 的方法已經提升，可完成更複雜的工作。 這些複雜的模型構成 AI 功能的基礎。

## Microsoft Azure 中的機器學習
Microsoft Azure 提供 Azure Machine Learning 服務 - 這是用於建立、管理和發佈機器學習模型的雲端式平台。 Azure Machine Learning Studio 會提供多種製作體驗，例如：

自動化機器學習：這項功能可讓非專家從資料快速建立有效的機器學習模型。
Azure Machine Learning 設計工具：一種無需程式碼即可開發機器學習解決方案的圖形化介面。
資料計量視覺效果 ：使用視覺效果來分析和最佳化您的實驗。
Notebooks：在直接於 Studio 中整體的受控 Jupyter Notebook 伺服器中撰寫並執行您自己的程式碼。

# 了解電腦視覺

電腦視覺是負責視覺處理的 AI 領域。 讓我們來探索電腦視覺帶來的一些可能性。

Seeing AI 應用程式是展現電腦視覺強大能力的絕佳範例。 Seeing AI 應用程式是專為視障和弱視社群所設計，其利用 AI 功能來開啟視覺世界並描述附近的人物和文字。

## 電腦視覺模型和功能
大部分的電腦視覺解決方案都是以機器學習模型為基礎，其可套用至相機、影片或影像的視覺輸入。 下表描述常見的電腦視覺工作。

* 影像分類：
影像分類需要定型機器學習服務模型，以根據影像的內容來分類影像。 例如，在交通監視解決方案中，您可使用影像分類模型，根據其所包含的車輛類型 (例如計程車、公車、腳踏車等) 來分類影像。
* 物件偵測：
定型物件偵測機器學習模型以分類影像中的個別物件，並使用週框方塊來識別其位置。 例如，交通監視解決方案可能會使用物件偵測來識別不同車輛類別的位置。
* 語意分割：
語意分割是一種進階機器學習技術，其中影像的個別像素會根據其所屬的物件進行分類。 例如，交通監視解決方案可能會使用「遮罩」層來將交通影像重疊，以使用特定色彩來醒目提示不同的車輛。
* 影像分析：
您可建立結合機器學習模型與進階影像分析技術的解決方案，從影像擷取資訊，包括可協助分類影像的「標籤」，或甚至是摘要影像中所示場景的描述性標題。
* 臉部偵測、分析和辨識
臉部偵測是一種特殊形式的物件偵測，可找出影像中的人臉。 這可與分類和臉部幾何分析技術結合，根據其臉部特徵來辨識個人。
* 光學字元辨識 (OCR)
光學字元辨識是用來偵測和讀取影像中文字的技術。 您可使用 OCR 來讀取相片中的文字 (例如道路標誌或店面)，或從掃描的文件 (例如信件、發票或表單) 擷取資訊。

# Microsoft Azure 中的電腦視覺服務
您可以使用 Microsoft 的 Azure AI 視覺來開發電腦視覺解決方案。 服務功能可用於 Azure Vision Studio 和其他程式設計語言中的使用和測試。 Azure AI 視覺的一些功能包括：

影像分析：分析影像和影片，以及擷取描述、標記、物件和文字的功能。
臉部：可讓您建置臉部偵測和臉部辨識解決方案的功能。
光學字元辨識 (OCR)：從影像擷取印刷或手寫文字的功能，可讓您存取掃描文字的數位版本。

# 了解自然語言處理
自然語言處理 (NLP) 屬於 AI 領域，負責建立軟體以理解書寫或口頭語言。

NLP 可供建立軟體，以便：

* 分析和解讀文件、電子郵件訊息及其他來源中的文字。
* 解譯口語語言，並合成語音回應。
* 自動翻譯不同語言的口語或書寫片語。
解譯命令並判斷適當的動作。
例如，Starship Commander 是 Human Interact 所發行的一款虛擬實境 (VR) 遊戲，其背景設定為科幻世界。 此遊戲使用自然語言處理，讓玩家能夠控制旁白，並與遊戲中的角色和星艦系統互動。

# 了解文件智慧服務和知識採礦
文件智慧是 AI 的領域，負責管理、處理和使用表單和文件中找到的大量資料。 文件智慧可讓您建立軟體，以自動化處理合約、健康情況文件、財務表單等等

# Microsoft Azure 中的文件智慧
您可以使用 Microsoft 的 Azure AI 文件智慧來建置解決方案，以管理和加速從掃描文件的資料收集。 Azure AI 文件智慧的功能可協助自動化應用程式和工作流程中的文件處理、增強資料驅動策略，以及擴充文件搜尋功能。 您可以使用預先建置的模型，為發票、收據、健康保險卡、稅務表單等項目新增智慧型文件處理。 您也可以使用 Azure AI 文件智慧服務，以您自己的已標記資料集建立自訂模型。 服務功能可用於文件智慧工作室和其他程式設計語言中的使用和測試。

# 知識採礦
知識採礦此字詞是用來描述解決方案，其涉及從大量非結構化資料中擷取資訊以建立可搜尋的知識存放區。

# 了解生成式 AI
生成式 AI 描述 AI 中建立原始內容的功能類別。 人員通常會與聊天應用程式內建的生成式 AI 互動。 讓生成式 AI 應用程式採用自然語言輸入，並以各種格式傳回適當的回應，包括自然語言、影像、程式碼和音訊。

# Microsoft Azure 中的生成式 AI
在 Microsoft Azure 中，您可以使用 Azure OpenAI 服務來建置生成式 AI 解決方案。 Azure OpenAI 服務是 Microsoft 的雲端解決方案，可用來部署、自訂及裝載生成式 AI 模型。 它結合 OpenAI 尖端模型和 API 的最佳功能，以及 Azure 雲端平台的安全性和延展性。

Azure OpenAI 支援許多可滿足不同需求的基礎模型選擇。 服務功能可用於 Azure OpenAI Studio 和其他程式設計語言中，或用於測試。 您可以使用 Azure OpenAI Studio 使用者介面來管理、開發及自訂生成式 AI 模型。

# AI 的挑戰和風險
| **挑戰或風險**                          | **範例**                                                         |
|---------------------------------------|----------------------------------------------------------------|
| **偏差可能會影響結果**                | 貸款核准模型因為其訓練資料有偏差而有性別上的差別待遇               |
| **錯誤可能造成傷害**                  | 自動駕駛汽車遇到系統故障而導致車禍                                 |
| **資料可能遭到公開**                  | 醫療診斷 Bot 會使用敏感的患者資料進行訓練，而這些資料並未安全地儲存   |
| **解決方案可能不適用於所有人**        | 家庭自動助理不會針對視覺受損的使用者提供音訊輸出                    |
| **使用者必須信任複雜的系統**          | 基于 AI 的金融服务工具提供投资建议 - 它们基于什么？                 |
| **誰應該對 AI 驅動的決策負責任？**    | 無辜的人因為來自臉部辨識的證據而被判有罪 – 這是誰的責任？           |


# 了解負責任 AI
在 Microsoft，AI 軟體開發是以一組六個準則為導向，旨在確保 AI 應用程式針對難題提供出色的解決方案，而不會產生任何非預期的負面後果。

## 公平性
AI 系統應該公平對待所有人。 例如，假設您建立機器學習模型來支援銀行的貸款核准申請。 此模型應該預測是否應核准或拒絕貸款，而不會有偏見。 這種偏見可能是基於性別、種族或其他因素，導致特定申請人群體的不公平優勢或不利因素。

Azure Machine Learning 能夠解譯模型，並針對資料每項特徵如何影響模型預測的程度進行量化。 這項功能可協助資料科學家和開發人員識別及緩和模型中的偏見。

另一個範例是 Microsoft 使用臉部服務實作負責任 AI，該功能會淘汰可用來嘗試推斷情緒狀態和身分識別屬性的臉部辨識功能。 如果誤用，這些功能可能會導致人們遭受刻板印象、歧視或不公平地拒絕服務。

## 可靠性和安全性
AI 系統應該以安全可靠的方式執行。 例如，假設有一個以 AI 為基礎的軟體系統用於自動駕駛汽車，或有一個機器學習模型用於診斷病患症狀並建議處方。 這類系統若是不可靠，便可能會對人類生命造成極大風險。

以 AI 為基礎的軟體應用程式開發必須遵守嚴格測試和部署管理程序，以確保其如預期般運作再予以發行。

## 隱私權與安全性
AI 系統應該安全並尊重隱私。 AI 系統所依據的機器學習模型依賴大量資料，其中可能包含必須確保隱私的個人詳細資料。 即使模型經過定型，而且系統仍在生產環境中，也必須考慮隱私權和安全性。 當系統使用新資料進行預測或採取動作時，根據資料所做的資料和決策都可能受限於隱私權或安全性考慮。

# 包容性
AI 系統應該賦予所有人權力，且讓人們參與。 AI 應該造福社會的每一份子，無論其身體能力、性別、性傾向、種族或其他因素。

# 透明
AI 系統應該是可以了解的。 使用者應該充分了解系統的用途、其運作方式，以及可能預期的限制。

# 當責
使用者應該對 AI 系統負責。 以 AI 為基礎的解決方案設計人員和開發人員應該在治理和組織準則的架構中工作，以確保解決方案符合清楚定義的道德和法律標準。

# 結論
人工智慧可供建立功能強大的解決方案來解決各種問題。 AI 系統可展現人類分析周遭世界的特質、進行預測或推斷，並以不久前只能想像的方式代替人類行動。

但此強大能力也伴隨著責任。 身為 AI 解決方案的開發人員，我們必須應用原則，以確保每個人都能從 AI 受益，而不會對社會的任何人或團體造成不利影響。
