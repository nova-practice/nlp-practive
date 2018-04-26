# nlp-practive
nlp练习


### 百度自然语言处理API

[API文档](http://ai.baidu.com/docs#/NLP-Java-SDK/top)

使用 baidu sdk，NLP Java SDK目录结构如下：

```
com.baidu.aip
       ├── auth                                //签名相关类
       ├── http                                //Http通信相关类
       ├── client                              //公用类
       ├── exception                           //exception类
       ├── nlp
       │       └── AipNlp           //AipNlp类
       └── util                                //工具类
```

SDK源码地址: [https://github.com/Baidu-AIP/java-sdk](https://github.com/Baidu-AIP/java-sdk)


#### 1. 词法分析
词法分析接口向用户提供分词、词性标注、专名识别三大功能；能够识别出文本串中的基本词汇（分词），对这些词汇进行重组、标注组合后词汇的词性，并进一步识别出命名实体。

#### 2. 词法分析（定制版）
定制版接口的使用教程请看链接：http://ai.baidu.com/forum/topic/show/496975

#### 3. 依存句法分析
依存句法分析接口可自动分析文本中的依存句法结构信息，利用句子中词与词之间的依存关系来表示词语的句法结构信息（如“主谓”、“动宾”、“定中”等结构关系），并用树状结构来表示整句的结构（如“主谓宾”、“定状补”等）。

#### 4. 词向量表示
词向量表示接口提供中文词向量的查询功能。

#### 5. DNN语言模型
中文DNN语言模型接口用于输出切词结果并给出每个词在句子中的概率值,判断一句话是否符合语言表达习惯。

#### 6. 词义相似度
输入两个词，得到两个词的相似度结果。

#### 7. 短文本相似度
短文本相似度接口用来判断两个文本的相似度得分。

#### 8. 评论观点抽取
评论观点抽取接口用来提取一条评论句子的关注点和评论观点，并输出评论观点标签及评论观点极性。

#### 9. 情感倾向分析
对包含主观观点信息的文本进行情感极性类别（积极、消极、中性）的判断，并给出相应的置信度。

#### 10. 文章标签
文章标签服务能够针对网络各类媒体文章进行快速的内容理解，根据输入含有标题的文章，输出多个内容标签以及对应的置信度，用于个性化推荐、相似文章聚合、文本内容分析等场景。

#### 11. 文章分类
对文章按照内容类型进行自动分类，首批支持娱乐、体育、科技等26个主流内容类型，为文章聚类、文本内容分析等应用提供基础技术支持

#### 12. 


### hanlp练习