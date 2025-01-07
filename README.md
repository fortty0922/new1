# new1

## 架構：爬蟲 -> 資料清理 -> AI 分析 -> 寫入 CSV -> 從 CSV寫入資料庫 -> Views展示階段

## fetch_news_從 Google News 抓取新聞資料的爬蟲功能
### varibale 
1. response:取得requests爬蟲url
2. soup:解析html文本
3. articles:查找所有文章
4. news_list:list
5. news_source:查找來源元素
6. source_name:
## parse_date_解析和標準化新聞的日期格式

## setup_chrome_driver_瀏覽器的無頭模式，讓 Chrome 在背景運行而不需要開啟實際的瀏覽器視窗

## extract_final_url_從 Google News 的 URL 中提取最終的 URL

## fetch_article_content_從新聞網站中擷取內容和摘要

## extract_image_url_從新聞網站中擷取圖片 URL

## load_and_summarize_csv_先將爬取到的資料存進csv檔

## chat_with_xai_V_X.AI 聊天功能

## is_disaster_news_使用 X.AI 判斷新聞是否主要報導自然災害事件

## main

