# RemoteControl 
---  

## Guide Content  

1. [Introduction](#Introduction)  
2. [Hardware Overview](#Hardware Overview)  
3. [Usage](#Usage)  
4. [Reference](#Reference)  

<a name="Introduction"></a>
## 1. Introduction  

Sivann的RemoteControl模組上面有5個按鍵，供電後按鍵一般狀態為高電位，當按下按鍵後為低電位。  
#### Sivann模組疊合  
Sivann 有感測模組外、無線模組以及電源模組，使用者可以將模組疊合使用，相關介紹在 sivann 模組疊合介紹。  
#### Features  
 * 5個按鍵給使用者設計。  

<a name="Hardware Overview"></a>
## 2. Hardware Overview  

![RemoteControl](http://i.imgur.com/vEMSWk2m.png "RemoteControl")

### Pinouts  
* Power Pins:  
  * Vcc(3.3V) – 3.3V 的電源腳位。  
  * GND – Vcc的地。  
* Button – (點擊按鍵前/後的電壓 Vcc/0V)  
  * Right – 右按鍵。  
  * Left – 左按鍵。  
  * Up – 上按鍵。  
  * Down – 下按鍵。  
  * OK – 中心按鍵。  

<a name="Usage"></a>
## 3. Usage  
1.	連接Vcc (3.3V) 至電源供應。
2.	連接 GND 至電源供應的地。
3.	連接 Button (RT, LT, UP, DN, OK) 至微控制器的輸入腳位。


<a name="Reference"></a>
## 4. Reference   

Schematic  

