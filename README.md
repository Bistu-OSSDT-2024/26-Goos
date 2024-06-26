# 大学生的AI自动回复工具

<p align="left">
    <a href="./LICENSE"><img src="https://img.shields.io/badge/license-GNU-dfd.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/series-AI_Operating-yellow.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/python-3.9+-aff.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/os-windows-pink.svg"></a>
</p>

🌟 专为忙碌的大学生打造
你是不是常常因为忙于上课、考试、做实验，而错过了微信上的重要信息或朋友们的问候？不用担心，这款工具能够帮你自动回复微信消息，让你在学习与社交之间游刃有余。
💡 功能特点
智能回复：基于开源大模型技术，智能理解消息内容，自动给出合适的回复，让你的聊天更加自然流畅。
隐私保护：我们承诺严格保护用户隐私，所有聊天记录仅在本地存储，不会泄露给任何第三方。
🎉 为什么选择我们？
专注学习：不再为频繁的消息打扰而分心，专注于你的学习任务。
维护人际关系：确保你能够及时回应朋友们的问候，维护良好的人际关系。
节省时间：无需频繁切换应用，一键设置，让聊天变得更加轻松高效。

## 👀 效果演示  

https://github.com/Bistu-OSSDT-2024/26-Goos/blob/%E6%95%88%E6%9E%9C%E6%BC%94%E7%A4%BA/%E6%95%88%E6%9E%9C%E6%BC%94%E7%A4%BA.mp4


支持单一聊天和群聊，设置了消息免打扰的会自动略过。目前只支持中文客户端。
## ⚡ 快速开始
1. 克隆 repo 到你的电脑上:
```
git clone https://github.com/ethanhwang1024/AI-Operating-Wechat.git
```
2. 进入目录:
```
cd AI-Operating-Wechat
```
3. 安装依赖：
```
pip install -r requirements.txt
```
4. 在config.py中输入阿里通义千问的apikey，可以去[dashscope](https://dashscope.aliyun.com/)获取
```
qwen_apikey = ""
```
5. 打开电脑微信窗口，确保整个窗口可见，并将文件传输助手右键置顶  
   <img width="336" alt="1703510831355" src="https://github.com/ethanhwang1024/AI-Operating-Wechat/assets/89822193/40a3335e-4578-4ea5-a14e-45b7aed38d34">
  
6. 运行   
```
python main.py
```
7. prompt可以在chat文件夹下的prompt.py文件里自己做一些定制


## 📣 致谢

修改自AI-Operating-Wechat，感谢原作者ethanhwang1024。
