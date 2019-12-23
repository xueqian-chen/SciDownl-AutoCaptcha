**[SciDownl](https://github.com/Tishacy/SciDownl)** is created by **[Tishacy](https://github.com/Tishacy)**. I modified it to make it identify the captcha automatically. Then, users can bulk download papers.



## Implement

The identification function is implemented by using a commercial system named *[chaojiying](https://www.chaojiying.com/price.html)*. The price is 0.02 RMB for each identification. No charge if the identification result is wrong.



## Install

Users should install some python packages through the following cmd command.

`pip install -r requirements.txt `


## Usage

1. See the attached video. Fill in the UserName, Password and AppID in lines ***205*** and ***209***, ***scihub.py***.
2. Modify the DOIs in ***run.bat***. To obtain a large number of DOIs, you can use Reference Management Software, such as EndNote.
3. Double click ***run.bat***. For each paper, the program will try 10 times at most to identify the captcha.
4. More detailed usages please see [SciDownl](https://github.com/Tishacy/SciDownl).

