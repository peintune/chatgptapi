# 说明
1 封装了chatgptapi

2 模型用的最新的 gpt-3.5-turbo。

3 此项目只做学习使用，不能有太大的流量调用，目前服务器配置较低，请不要一直刷

4 我加了ip限流，1个ip 1分钟 5次。

### 交流：
有合作和想法的伙伴可以加微信一起探讨

 <img src="https://user-images.githubusercontent.com/10082030/222692165-c91396fb-8062-473e-b083-c201fa19e9f1.png" width="150">


# 使用方法：
> 注意，要替换apiKey为你自己的Key
### 使用方式1：curl
```
curl -X POST "http://chatgpt.taigoodai.com:9028/api/chatgpt/call/common?apiKey=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" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"chatgptRequest\": { \"messages\": [ { \"content\": \"帮我写首古诗\", \"role\": \"user\" } ], \"model\": \"gpt-3.5-turbo\" }}"

```

结果如下图：

 <img src="https://user-images.githubusercontent.com/10082030/222691984-ef67b3bb-b31f-406d-a94b-7401513669fc.png" width="700">



### 使用方式2：- postman：
 <img src="https://user-images.githubusercontent.com/10082030/222691557-e3f95750-9a96-4df6-b259-0c608f9d2dfd.png" width="700">


### 使用方式3：在你的程序调用
