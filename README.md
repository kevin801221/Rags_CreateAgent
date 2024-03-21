### 1.記得pip install poetry 建立開發環境必需python的庫
### 2.clone整個github repo
### 3.poetry install --with dev 建立開發環境
### 4.在".streamlit/secrets.toml" 底下放進你自己的openai api key. 切記千萬不可外流
### 5.用streamlit run的方式展開接口檔案 1_home.py => streamlit run 1_home.py

#### 首頁可跟AI進行對話, AI可以透過自然語言幫我們建立不同領域的Agent代理人:
![image](https://github.com/kevin801221/Rags_CreateAgent/assets/55553401/f5291967-ced4-4c63-a2c7-13d36a27d797)
#### 左邊的一排看似亂碼的東西, 是每一次建立Agent時候產生的Agent 緩存id
#### 左上排除了home之外還有Genearated RAG Agent可以選, 在跟home確定好config設置之後就可以確定。
#### 初始狀態是 "Agent not created. Please create an agent in the above section.
![image](https://github.com/kevin801221/Rags_CreateAgent/assets/55553401/93993f36-7c49-4385-8d2f-4722a36773c4)

#### 再來可以設定RAG的參數。
topK, chunk size of documents, LLM是哪一種等... (看似可以設定, 但其實UI介面的設定一刷就重置了。)
![image](https://github.com/kevin801221/Rags_CreateAgent/assets/55553401/375f09c4-8e07-4a17-8c54-209fb1b2fd59)

用自然語言跟AI直接對話建立物理Agent:
![image](https://github.com/kevin801221/Rags_CreateAgent/assets/55553401/4dc1b061-7871-4dec-ba5e-086e5d019d7b)

接下來旁邊的緩存就會產生Agent給我們選擇:
![image](https://github.com/kevin801221/Rags_CreateAgent/assets/55553401/0d1b0985-afcd-43bf-9330-d1740d7f03bb)


