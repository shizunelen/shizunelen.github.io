# 你好，我是 XXX

我正在學習資料結構與演算法，未來希望成為軟體工程師。

---

## 關於我
- 正在學習：C++ / Python / 演算法
- 興趣：寫程式、學新技術
- 目標：進入科技公司當工程師

---

## 最新文章
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
