# chatgptapi
封装了chatgptapi,模型用的最新的 gpt-3.5-turbo。
此项目只做学习使用，不能有太大的流量调用，目前服务器配置较低，请不要一直刷，我加了ip限流，1个ip 1分钟 5次。


# 使用方法：
> 注意，要替换apiKey为你自己的Key
### 使用方式1：curl
```
curl -X POST "http://chatgpt.taigoodai.com:9028/api/chatgpt/call/common?apiKey=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" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"chatgptRequest\": { \"messages\": [ { \"content\": \"帮我写首古诗\", \"role\": \"user\" } ], \"model\": \"gpt-3.5-turbo\" }}"

```

### 使用方式2：- postman：

![image](https://user-images.githubusercontent.com/10082030/222690497-830bd5ee-3cf4-471b-9651-f3ea96929dba.png)


### 使用方式3：在你的程序调用
