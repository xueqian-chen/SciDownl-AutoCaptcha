## 简介

本项目是在 **[Tishacy](https://github.com/Tishacy)** 创作的 **[SciDownl](https://github.com/Tishacy/SciDownl)** 基础上做的微小修改，实现了自动识别验证码，从而批量下载文献的功能。



## 实现方法

验证码识别使用的商用验证码识别平台[超级鹰](https://www.chaojiying.com/price.html)。费用约0.02元每次，识别错误不收费。我没有尝试别的验证码识别平台，如有更好的平台，欢迎大家推荐。



## 安装

首先要安装一些第三方库，在 cmd 中执行以下命令。注意cmd的路径要改为 requirements.txt 所在的文件夹。

`pip install -r requirements.txt `



## 使用方法

1. 首先根据附件`tutorial.md`，注册超级鹰帐号并充值（或者根据超级鹰的官网提示获取试用额度），修改 **scihub.py** 中的第 205 行，输入超级鹰帐号密码。在 **scihub.py**文件末尾添加要下载文件的DOI，然后运行 **scihub.py**即可。
2. 更详细的使用方法，如更新 SciHub 的可用地址，请看 [SciDownl](https://github.com/Tishacy/SciDownl).

