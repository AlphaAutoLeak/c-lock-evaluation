---
![image](https://github.com/AlphaAutoLeak/c-lock-evaluation/blob/master/1.png)
---

## Introduction
- 评估结果仅供参考
- 数据均在同一时间运行进行统计
- 评估结果每台机器运行不同

---
## Statistics

| ollvm | string | bytecodeVerify |   file    | cost  |
| :---: | :----: | :------------: | :-------: | :---: |
|   √   |   √    |       √        |   ollvm   | 336ms |
|   ×   |   √    |       ×        | no-verify | 329ms |
|   ×   |   √    |       √        | no-ollvm  | 328ms |
|   ×   |   ×    |       ×        |  non-obf  | 473ms |

---
