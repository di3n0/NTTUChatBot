# NTTUChatBot
https://ai-sdk-starter-groq-five-tau.vercel.app/

I have built a retrieval-augmented generation (RAG) system powered by Groq for high-speed inference and information retrieval.</br>
This system generates responses using AI models and external knowledge sources to assist users efficiently.</br>
However, all generated content is for informational purposes only and should not be considered professional, legal, medical, or financial advice.</br>
I do not assume any responsibility for decisions or actions taken based on the system’s outputs.</br>

![image](https://github.com/di3n0/NTTUChatBot/blob/main/0.png)
</br></br></br>
## 廣度優先搜尋 (BFS) 演算法：</br>
1. 起始頁面 (根節點)： 只抓取頁尾 (Footer) 的聯絡資訊並儲存。</br>
2. 索引頁面 (連結 > 50個)： 判斷為「導覽頁」，不儲存內容，但會從中找出新連結繼續探索。</br>
3. 內容頁面 (連結 ≤ 50個)： 判斷為「文章頁」，會清理掉選單、廣告等雜訊，儲存主要內文。</br>
