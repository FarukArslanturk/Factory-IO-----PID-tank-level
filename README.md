# Factory-IO-----PID-tank-level
Factory IO -- PID tank level solution.

TIA PORTAL and Twincat 3 solution is attached. C# WinForm solution also added lately, but in another repository. You can find it in my main home directory.

Here below youtube link attached using twincat 3. I didn't record a video for TIA PORTAL.

https://www.youtube.com/watch?v=hXsjRrmK38g

TIA PORTAL:

I didn't think SCL language is required for this project so the program is written in LAD language.

![PID Values](https://user-images.githubusercontent.com/70879506/109421193-61ca8280-79e7-11eb-980a-4ae3fecdd0dc.PNG)

This PID values can be used if you want to have no overshoot and steady-state error. 

Twincat 3 : 

Program is written in ST language. Modbus Tcp is set for communication between twincat 3 and Factory IO. 

![image](https://user-images.githubusercontent.com/70879506/110313931-36afe680-8018-11eb-8f40-2cc73972a2d2.png)

This PID values can be used. No overshoot. No steady-state error, but slow reaction time. 

