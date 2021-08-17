# GensimWikiVector
## 將Wiki的文章，用Jieba斷字，如要繁體，用OpenCC轉成繁體後再訓練。

    使用Google Colab環境編輯，將檔案傳至雲端，若使用Jupyter Notebook環境根據檔案或是語法刪除或更改語句、語法

###### 使用步驟：
* 步驟1. 到(https://dumps.wikimedia.org/zhwiki/) 下載最新的(lastest)文章庫  
可以下載 zhwiki-latest-pages-articles.xml.bz2 or zhwiki-latest-pages-articles-multistream.xml.bz2

* 步驟2. **使用 WikiCorpus.ipynb** 根據檔案存放的位置，更改位置  

* 步驟3. **使用 ParsingWordAndOpenCC.ipynb** 需具備Jieba，若要繁體則需OpenCC，根據檔案存放的位置，更改位置  

* 步驟4. **使用 GensimModel.ipynb** 需具備Gensim(word2vec)，根據檔案存放的位置，更改位置，訓練玩模型後可以自行測試  

###### 參考文獻：
`1.https://clay-atlas.com/blog/2020/01/17/python-chinese-tutorial-gensim-word2vec/`
