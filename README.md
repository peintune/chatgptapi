# 说明
1 封装了chatgptapi

2 模型用的最新的 gpt-3.5-turbo。

3 免费接口2：

4 免费接口1：

5 合作接口：无限制

6 可以用在群机器人等场景中

# UI 使用地址：

https://chatai.taigoodai.com/

 <img src="https://user-images.githubusercontent.com/10082030/225298117-bb128bba-d3e8-41d1-b92e-693fb755cea7.png" width="700">


### 交流：
有合作和想法的伙伴可以加微信一起探讨

 <img src="https://user-images.githubusercontent.com/10082030/222692165-c91396fb-8062-473e-b083-c201fa19e9f1.png" width="150">


# 接口使用方法：
### 免费接口2：
> 此接口直接可调用
```
curl -X POST "http://chatgpt.taigoodai.com:9028/api/chatgpt/free/call/free2" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"chatgptRequest\": { \"messages\": [ { \"content\": \"你好\", \"role\": \"user\" } ], \"model\": \"gpt-3.5-turbo\" }}"


```

### 免费接口1：
> 注意，此接口要替换apiKey为你自己的Key

```
curl -X POST "http://chatgpt.taigoodai.com:9028/api/chatgpt/free/call/free1?apiKey=sk-4kxxxxxxx" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"chatgptRequest\": { \"messages\": [ { \"content\": \"帮我写首古诗\", \"role\": \"user\" } ], \"model\": \"gpt-3.5-turbo\" }}"
```



### 结果如下图：

 <img src="https://user-images.githubusercontent.com/10082030/222701499-b1b31636-26e9-4489-8a02-19ae1e9c8193.png" width="700">


 <img src="https://user-images.githubusercontent.com/10082030/222691557-e3f95750-9a96-4df6-b259-0c608f9d2dfd.png" width="700">


