## 提示词注入生成器
提示词注入生成器，提示词注入作为LLM首要威胁，是现代LLM最大的攻击威胁之一，本程序集合了常见的提示词注入prompt，覆盖了提取系统提示词，绕过内置安全过滤器的提示词
并且自带多语言库，错别词库，语义替代库等。可进行单个payload攻击与组合攻击等，且在生成基础版的同时自带变异混淆版。

## 使用方法
安装pyperclip库
```
pip3 install pyperclip
```
之后使用
```
python3 main.py
```
进入命令行模式，此模式随机生成2种示例prompt且每次运行不一样
<img width="1206" height="326" alt="image" src="https://github.com/user-attachments/assets/aba59b59-82b6-4cb5-b930-ead09cf99b21" />
<img width="1206" height="328" alt="image" src="https://github.com/user-attachments/assets/b0f01750-2cbf-4733-bd11-82ccd59e8ce6" />
启用图形界面
```
python3 main.py -gui
```
<img width="1502" height="886" alt="image" src="https://github.com/user-attachments/assets/93f496c7-5d97-4569-a952-3b33149350b9" />
图形界面可自定义变异强度，默认为0.8，可单独选择基础版和组合版
<img width="1493" height="880" alt="image" src="https://github.com/user-attachments/assets/4e35dd6d-dda9-40f5-914f-c18742571d76" />
<img width="1502" height="921" alt="image" src="https://github.com/user-attachments/assets/bb91056c-7a46-447d-92bc-d2dfe86730d5" />
历史记录默认生成变异版，可双击复制
<img width="1496" height="911" alt="image" src="https://github.com/user-attachments/assets/2f05ad5f-312f-4014-a5f3-30c77690dc3f" />

## 扩展阅读
[如何获取主流大模型的系统提示词](https://xz.aliyun.com/news/18779)

[大模型安全攻防实践 越狱攻击方法与思路分享](https://xz.aliyun.com/news/18770)

## 时间线
2025.9.13    开天劈地，发布初版。
