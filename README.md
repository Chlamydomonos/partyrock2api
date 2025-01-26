![image](https://github.com/user-attachments/assets/718a4ca8-751d-4c93-a6ac-5af18561d875)# Partyrock2api


## 声明
- 仅用于学术研究和交流学习

## 支持模型
- claude-3-5-haiku
- claude-3-5-sonnet
- nova-lite-v1-0
- nova-pro-v1-0
- llama3-1-7b
- llama3-1-70b
- mistral-small
- mistral-large

## Docker部署
### 拉取
```bash
docker pull mtxyt/partyrock-api:1.1
```
### 运行
```bash
docker run -d -p 8803:8803 mtxyt/partyrock-api:1.1
```
请求key获取方式
### 准备步骤
点击Generate app按钮创建app
![image](https://github.com/user-attachments/assets/847748e6-896f-471d-8048-de3379cdbf70)
创建app后按f12打开开发者工具点击网络随便发起提问
### 1.在标头里拿到anti-csrftoken-a2z和cookie
找到对应请求
![屏幕截图 2025-01-26 204042](https://github.com/user-attachments/assets/e8c27ce9-0a0d-468c-89aa-8c61e64b990e)
### 1.在负载里拿到appid
![屏幕截图 2025-01-26 204209](https://github.com/user-attachments/assets/37c6707f-ad98-4cad-af35-b37d6c4d1ef7)

## 注
key的格式为appid|||anti-csrftoken-a2z|||cookie组合
如果你的appid=abab1,anti-csrftoken-a2z=132hdwqo,cookie=sdakvfjdijvdiv
那你的key就是abab1|||132hdwqo|||sdakvfjdijvdiv

## 声明
本项目仅供学术交流使用，请勿用于商业用途。
