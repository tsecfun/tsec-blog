---
title: ChatGPT如何为安全工作助力
date: 2023-02-17
author: tsec
desc: ChatGPT目前是全行业的热词，各行各业都在寻找ChatGPT能够提供的机会，在安全运营方面有哪些工作能够通过使用chatGPT更高效的完成？
img: http://pic.hackmyhome.top/i/202302171412349.jpg
imgWidth: 800
imgHeight: 500
---



## 简介

ChatGPT（全名：Chat Generative Pre-trained Transformer）是由OpenAI开发的一个人工智能聊天机器人程序，于2022年11月推出。该程序使用基于GPT-3.5架构的大型语言模型并通过强化学习进行训练。ChatGPT目前仍以文字方式互动，而除了可以透过人类自然对话方式进行交互，还可以用于相对复杂的语言工作，包括自动文本生成、自动问答、自动摘要等在内的多种任务。如：在自动文本生成方面，ChatGPT可以根据输入的文本自动生成类似的文本（剧本、歌曲、企划等），在自动问答方面，ChatGPT可以根据输入的问题自动生成答案。还具有编写和调试计算机程序的能力。在推广期间，所有人可以免费注册，并在登入后免费使用ChatGPT实现与AI机器人对话。

## ChatGPT能在哪些方面发力？

### 安全运营工作

日常安全运营工作主要是对告警进行分析、处置、输出归档报告，chatgpt在这方面可以帮助安全人员快速的对告警信息进行判断。

**> 事件日志分析：请根据给定日志，请帮我分析一下是否是攻击行为。**

<img src="http://pic.hackmyhome.top/i/202302171422055.png" alt="image-20230217142239088"  />

**> 协助事件处置：请针对上述的事件针对性的输出处置建议。**

![image-20230217142332991](http://pic.hackmyhome.top/i/202302171423551.png)

**>编写规则：请根据给定攻击方法，请帮我编写一条suricata/yara检测规则。**

![image-20230217142437780](http://pic.hackmyhome.top/i/202302171424439.png)

**>规则优化：请对给定规则进行优化，要求能够对XXXX进行检测。**

> 

![image-20230217142717973](http://pic.hackmyhome.top/i/202302171427722.png)

**>编写报告：请根据给定数据格式，编写网络安全事件处置报告单。**

![image-20230217143349236](http://pic.hackmyhome.top/i/202302171433203.png)



**>编写安全工具：请帮我编写一个python程序，实现对内网多台linux服务器的/tmp目录进行扫描，查找123.txt文件是否存在，如果存在则删除此文件。**

![image-20230217143443866](http://pic.hackmyhome.top/i/202302171434404.png)

## 常用的几种提问方式

用好chatgpt的基础是要有提问的技巧，目前已有一些现成的提问工具，比如：

[awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts)

以下是我常用的提问方式：

- 写代码：生成一段XXX代码，实现XXXXX
- 检查代码：请根据给定代码，帮我检查一下是否有错误
- 处理数据：根据给定数据，帮我对数据进行XXX处理
- 总结文章：请帮我总结http://xxx.xxx.xxx的文章主旨
- 写材料：根据给定内容，请帮我写一段5分钟的演讲材料
- 解释：你能解释一下XXX么？
- 继续

## 小结

- 简单，简短，避免长句。
- 目标明确，指定步骤。
- 对指定材料命名或者代指清晰。
- 对实用性任务，给出限定性、客观性提示。
- 对创造性任务，给出开放性、探索性提示。



**ChatGPT是一面镜子，它的回应是你的影子**

---

### 2月18日晚8点直播聊聊网络安全方面有哪些使用技巧。

链接：https://t.me/secnote?livestream=c845f4f46707dd1cde
