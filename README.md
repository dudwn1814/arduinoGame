# ๐ป ์ฅ์ ๋ฌผ ํผํ๊ธฐ ๊ฒ์ <img src="https://img.shields.io/badge/C++-yellow?style=flat-square&logo=C++&logoColor=white"/> <img src="https://img.shields.io/badge/Arduino-blue?style=flat-square&logo=Arduino&logoColor=white"/>


> ์๋์ด๋ธ๋ฅผ ์ด์ฉํด ๊ตฌํํ ์ฅ์ ๋ฌผ ํผํ๊ธฐ ๊ฒ์ (22.08.10 ~ 22.08.12)

![example_image](./image/example_image.png)          
<br/>

### ๐๏ธ <a href="https://player.vimeo.com/video/770017885?h=caac0de6f5&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479">์์ฐ์์</a>
<br/>

### ๐ ๏ธ ์ฌ์ฉ ํด / ์ธ์ด
    โฌ Arduino IDE
    โฌ C++
    โฌ Arduino (UNO Board, LCD 16x4, 8x8 Matrix, PS2 Joy Stick)
### ๐ ์ฌ์ฉ ๋ผ์ด๋ธ๋ฌ๋ฆฌ
    โฌ <MsTimer2.h>
    โฌ <LedControl.h>
    โฌ <Wire.h>
    โฌ <LiquidCrystal_I2C.h>
### ๐ ๊ธฐ๋ฅ ์ค๋ช
<details>
<summary style="Font-Weight:300">&nbsp;1. Set Up</summary>
<div markdown="1">
<pre>    โฌ Matrix ์ฐ๊ฒฐ ์ธํ<br/> 
    โฌ ์๋ฆฌ์ผ ํต์  ์ธํ<br/>
    โฌ Lc, Lcd ์ธํ ๋ฐ ์ด๊ธฐํ<br/>
    โฌ ์ด๊ธฐ ์์ ์์น๋ฅผ ์ค์ <br/>
    โฌ ํ๋ ์ด ์๊ฐ์ ๋ํ๋ผ ํ์ด๋จธ๋ฅผ ์ค์  ๋ฐ ์ด๊ธฐํ (๊ธฐ๋ณธ 1์ด ์ฃผ๊ธฐ)
</pre>
</div>
</details>

<details>
<summary style="Font-Weight:300">&nbsp;2. Start</summary>
<div markdown="1">
<pre>    โฌ ํ๋ ์ด ์๊ฐ ์ธก์  ๊ธฐ๋ฅ<br/>
    โฌ ์กฐ์ด์คํฑ์ 3์ด์ด์ ๋๋ฅด๋ฉด ๊ฒ์์ ์์ํ๋ ๊ธฐ๋ฅ
</pre>
</div>
</details>

<details>
<summary style="Font-Weight:300">&nbsp;3. Player Move</summary>
<div markdown="1">
<pre>    โฌ ํ์ด๋จธ๋ฅผ ํตํด 1์ด ์ฃผ๊ธฐ๋ก ์ฌ์ฉ์์ ์๋ ฅ์ ์ฝ์ด์ค๋ ๊ธฐ๋ฅ<br/>
    โฌ ์กฐ์ด์คํฑ์ ๋ฐฉํฅ์ ๋ฐ๋ผ ์ฌ์ฉ์์ ์์น๋ฅผ ์ด๋ํ๋ ๊ธฐ๋ฅ (+ ์์ชฝ ๋ชจ์๋ฆฌ์ ๊ฒฝ์ฐ ์์ง์ด์ง ์๋๋ก ์์ธ ์ฒ๋ฆฌ)<br/>
    โฌ ์กฐ์ด์คํฑ ๊ฐ๋์ ๋ฐ๋ผ ์ด๋ํ๋ ์ ๋๋ฅผ ์กฐ์ ํ๋ ๊ธฐ๋ฅ<br/>
    โฌ ์ฅ์ ๋ฌผ๊ณผ ๋ถ๋ชํ์ ๋ ์๋ช์ ํ๋ ์ฐจ๊ฐํ๋ ๊ธฐ๋ฅ
</pre>
</div>
</details>

<details>
<summary style="Font-Weight:300">&nbsp;4. Obstacle Move</summary>
<div markdown="1">
<pre>    โฌ ์ฅ์ ๋ฌผ ์์ ์์น๋ฅผ ๋๋ค์ผ๋ก ์ค์ ํ๋ ๊ธฐ๋ฅ<br/>
    โฌ ์ฅ์ ๋ฌผ์ด ๋ด๋ ค์ค๋ ์๊ฐ ์ค์  ๊ธฐ๋ฅ (๊ธฐ๋ณธ 1์ด ์ค์ )<br/>
    โฌ 2์นธ ํฌ๊ธฐ์ ์ฅ์ ๋ฌผ์ด ์ ํด์ง ์๊ฐ์ ์ฃผ๊ธฐ๋ก ํ ์ค์ฉ ๋ด๋ ค์ค๋ ๊ธฐ๋ฅ<br/>
    โฌ Player์ ๋ง์ฃผ์ณค์ ๊ฒฝ์ฐ ์ฅ์ ๋ฌผ์ ์์ ๋ ๊ธฐ๋ฅ<br/>
    โฌ Player์ ๋ง์ฃผ์น์ง ์๊ณ  ๋๊น์ง ๋ด๋ ค์์ ๊ฒฝ์ฐ ์ฅ์ ๋ฌผ์ ์์ ๋ ๊ธฐ๋ฅ
</pre>
</div>
</details>

<details>
<summary style="Font-Weight:300">&nbsp;5. End</summary>
<div markdown="1">
<pre>    โฌ ์๋ช์ด 0์ด ๋์์ ๊ฒฝ์ฐ ์ข๋ฃํ๋ ๊ธฐ๋ฅ<br/>
    โฌ ํ๋ ์ดํ ์๊ฐ์ Lcd์ ํ์ํ๋ ๊ธฐ๋ฅ<br/>
    โฌ ์ผ์  ์๊ฐ ๋๋ ์ด ํ, ๋ค์ ๊ฒ์ ์์ ํ๋ฉด์ ํ์ํ๋ ๊ธฐ๋ฅ (๊ธฐ๋ณธ ์ค์  ์๊ฐ 5์ด)      
</pre>
</div>
</details>      

### ๐ก ๋ฐ์  ๋ฐฉํฅ
    โฌ ์์ดํ์ด ๋ชจ๋์ ์ด์ฉํด ๊ฒ์ ์ ์๋ฅผ ์น์ ๋ฑ๋กํ๋ ๊ธฐ๋ฅ
    โฌ ๋์ด๋๋ฅผ ์ ํํ  ์ ์๋ ๊ธฐ๋ฅ (์๋, ์ฅ์ ๋ฌผ ๊ฐ์ ์กฐ์ )
    โฌ ์น๊ณผ DB๋ฅผ ์ฐ๋ํด ์ฌ์ฉ์์ ์์๋ฅผ ๋น๊ตํ๋ ๊ธฐ๋ฅ         

### ๐ฉ๐ปโ๐ซ ์ฐธ๊ณ  ์๋ฃ
    โฌ https://www.youtube.com/watch?v=nXdEqbL_6jg
    โฌ https://create.arduino.cc/projecthub/juanma-alvarez-plaza/arduino-catch-the-beat-8x8-led-matrix-f464b0?ref=search&ref_id=8x8&offset=17
### ๐ฉ๐ปโ๐ป ๊ฐ๋ฐ์
    โฌ ์์์ฃผ - https://github.com/dudwn1814
    โฌ ํฉ์์ - https://github.com/Seo0H        
  
