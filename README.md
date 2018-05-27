# How-to-use-Github

## Git
- ### Git initialize
> #### 1.mkdir recipe_hello: 建立資料夾給該個repository
> #### 2.git clone 加上複製repository網址: clone github上面檔案到本機
> #### 3.輸入帳密:
>> ##### git config --global user.email "you@example.com"
>> ##### git config --global user.name "Your Name"

- ### git系列功能: 丟到暫存區，所以如果把檔案丟到資料夾並不會直接跑上去github
> #### 1.git status: 可以看該資料夾裡面多增加了什麼
> #### 2.git add .: 把整個資料夾更新全部放至暫存區
> #### 3.git commit -m "add foodsoup.py": 把檔案丟至暫存區，""裡面放本次更動敘述
> #### 4.git push: 上傳至github
> #### 5.git pull: 如有同一人共同編輯同一個repository，push的時候就會出現rejected，此時就會需要用pull指令把github上面有變動的部分pull下來，才有辦法push新的東西上去

## Markdown
- ### CheatSheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

