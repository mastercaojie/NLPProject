# NLPProject
新闻文本分类、文本摘要、情感分析 Django web实现


自然语言处理语义系统
系统主要实现文本摘要、情感分析、文本分类三个功能，通过web界面展示。通过python编程实现，系统框架使用Django架构。
主要工作：
1、情感分析基于深度学习RNN实现，情感分析功能可以输入一句短评，输出情感倾向（消极或者积极）以及情感得分；
2、文本分类基于深度学习RNN实现，输入一段新闻，能正确分类出新闻的类别，可将新闻10个类别；
3、文本摘要基于TextRank算法实现，输入一段文本，抽取其中得分最高的前几个句子，重新排序作为摘要输出。

tensorflow
Django
CNN
TexRank
