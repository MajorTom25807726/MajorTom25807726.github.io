# MajorTom.github.io

# 波波的第一個網站ouob

<table>
    <tr>
        <td>大一</td>
    </tr>
    <tr>
        <td>大二</td>
    </tr>
</table>

波波的自介
=========
* 2018 學C做1A2B和OOXX
* 2019 學java沒做出東西
* 2020 學processing做出墜機模擬器
* 2021 學python立志做出Dcard自動回覆機器人

我喜歡的歌
=========
[波波喜歡的歌](https://www.youtube.com/watch?v=hPc7m1ffj3s)

波波的程式(python,需要執行請用Google Colab)
=========
```python
import random
max = 100
min = 0
number = random.randint(0, 100)
 
 
while 1:
    guess = int(input("請輸入數字:"))
    if guess > max:
        print("錯誤:輸入值超過最大值,請重新輸入!")
        guess = int(input("請輸入數字:"))
    else:
        if guess < number:
            min = guess
            print("範圍:",min,"到",max)
        elif guess > number:
            max = guess
            print("範圍:",min,"到",max)
        elif guess == number:
            break
print("正確數字為:",number)
```

# 波波喜歡的圖片
![瑞克警長](https://i.pinimg.com/originals/5a/bf/1d/5abf1d5725f05fdfa493d6afd2584343.jpg)
