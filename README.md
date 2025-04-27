{
  "name": "找书神器",
  "host": "https://mianfei22.com",
  "searchUrl": "https://mianfei22.com/search?keyword={{key}}",
  "bookSourceGroup": "自定义",
  "bookSourceType": 0,
  "bookSourceUrl": "https://mianfei22.com",
  "searchBook": {
    "rule": {
      "bookList": ".book-list li",
      "name": "a.title",
      "author": "p.author",
      "bookUrl": "a@href",
      "coverUrl": "img@src",
      "intro": "p.intro"
    }
  },
  "toc": {
    "rule": {
      "chapterList": ".chapter-list li",
      "chapterName": "a",
      "chapterUrl": "a@href"
    }
  },
  "content": {
    "rule": {
      "content": ".chapter-content"
    }
  }
}
