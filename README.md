# 青马班课时记录（Gitee Pages）

学生访问：https://oblivion_1_0.gitee.io/qingma-jilu

## 日常更新（约 1 分钟）

1. 腾讯文档打开课时表 → **文件 → 导出为 → Excel(.xlsx)**
2. 把文件重命名为 `qingma.xlsx`，放到本目录（覆盖旧文件）
3. 双击 **`一键同步.bat`**，等窗口跑完
4. 学生刷新网页即可

## 首次额外步骤

1. 双击同步成功后，打开仓库：https://gitee.com/oblivion_1_0/qingma-jilu
2. 顶部 **服务 → Gitee Pages**
3. 部署分支选 `master`，目录填 `/`，开启
4. 等待部署完成后用微信打开上面的学生地址

## 推送登录说明

首次 `git push` 可能弹出登录框：

- 用户名：`oblivion_1_0`
- 密码：填 **私人令牌**（不是 Gitee 登录密码）

## 文件说明

| 文件 | 作用 |
|---|---|
| `qingma.xlsx` | 你导出的课时表（本地用，不会推到公开站） |
| `一键同步.bat` | 一键转换并推送 |
| `sync.py` | 转换/推送逻辑 |
| `index.html` | 学生查询页 |
| `data.json` | 网页读取的数据 |

仓库：https://gitee.com/oblivion_1_0/qingma-jilu.git
