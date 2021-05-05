# Structural Patterns-1-1-Proxy

代理模式

### 適合應用場景:

- 訪問控制
- 資料緩存(大量重覆請求)
  - vuejs 響應資料的暫存(cache)就是利用代理機制實現...
- ...

## Javascript 中的代理

Proxy 創建一個代理對象，並且內建基本攔截數操作方法

學習資源:
- [代理模式](https://refactoringguru.cn/design-patterns/proxy)
- [mozilla Proxy](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Proxy)
- [js proxy 封裝案例](https://blog.fundebug.com/2019/06/14/how-to-use-javascript-proxy/)
- [使用 ES6 Proxy 監聽資料的變化](https://medium.com/%E6%89%8B%E5%AF%AB%E7%AD%86%E8%A8%98/using-proxy-to-monitor-object-e57af6326d73)
- [8、Proxy和Reflect](https://jelly.jd.com/article/604f04069c61f9014c21ad81) - 有提到 vue3 使用 proxy 的原因
