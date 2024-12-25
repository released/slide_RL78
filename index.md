
[return to index](https://released.github.io/)

<a id="article_top"></a>

# Agenda

* IDE 開發工具的安裝&介紹
  * CS+ , e² studio , CCRH , CCRL , Smart Configurator , Renesas Flash programmer
* Smart Configurator
  * [Clock tree , Pin configuration , Peripheral configuration](#article_clock)
  * [Timer](#article_timer)
  * [GPIO](#article_gpio)
  * [external pin interrupt](#article_ext)
  * [I2C](#article_i2c)
  * [SPI](#article_spi)
  * [UART](#article_uart)
  * [PWM](#article_pwm)
  * [ADC](#article_adc)
* CS+
  * Code Compiler & programming flow ( from C code to IC ).
* Tips

---

# IDE & Debug tool

[Debug & programmer - E2 emulator](https://www.renesas.com/us/en/software-tool/e2-emulator-rte0t00020kce00000r)


[Debug & programmer - E2 emulator lite for RL78](https://www.renesas.com/us/en/software-tool/e2-emulator-lite-rte0t0002lkce00000r)


[IDE – CS+ , suggest for automotive product](https://www.renesas.com/en/software-tool/cs)


[IDE – e² studio](https://www.renesas.com/en/software-tool/e-studio)

![](img/slide_extend_RL780.png)

![](img/slide_extend_RL781.png)

---

# User manual : CS+


[CS+ User’s Manual](https://www.renesas.com/en/software-tool/cs)

![](img/slide_extend_RL782.png)

![](img/slide_extend_RL783.png)

<u>Integrated Development Environment User's Manual: RL78 Debug Tool</u>
[back to top](#article_top)

---

# User manual : e² studio


[e² studio User’s Manual](https://www.renesas.com/en/software-tool/e-studio)

![](img/slide_extend_RL784.png)

![](img/slide_extend_RL785.png)

---

# Compiler : CC-RL for RL78
 

[Compiler – C Compiler Package for RL78 Family [CC-RL] ](https://www.renesas.com/en/software-tool/c-compiler-package-rl78-family)

***Base on selected IDE , install the related compiler ( RL78 Compiler CC-RL for CS+ or for e² studio)**


[Compiler Licenses](https://www.renesas.com/en/software-tool/compiler-licenses)

![](img/slide_extend_RL787.png)

![](img/slide_extend_RL786.png)

![](img/slide_extend_RL788.png)

![](img/slide_extend_RL789.png)

---

# User manual : CC-RL for RL78


[Compiler CC-RL User’s Manual](https://www.renesas.com/en/software-tool/c-compiler-package-rl78-family)

![](img/slide_extend_RL7810.png)

![](img/slide_extend_RL7811.png)

---

# Smart Configurator main window

[IDE plug in  – Smart Configurator](https://www.renesas.com/en/software-tool/smart-configurator)

***Base on selected IDE , install the related Smart Configurator**

![](img/slide_extend_RL7812.png)

---

# Renesas Flash Programmer


[Renesas Flash Programmer (Programming GUI)](https://www.renesas.com/en/software-tool/renesas-flash-programmer-programming-gui)

![](img/slide_extend_RL7813.png)

![](img/slide_extend_RL7814.png)

---

# Create project by CS+ (RL78)

![](img/slide_extend_RL7816.png)

![](img/slide_extend_RL7815.png)


<u>Integrated Development Environment User's Manual: Project Operation</u>
[back to top](#article_top)

---

# CS+ (RL78) : main window

![](img/slide_extend_RL7817.png)

---

# CS+ (RL78) : open smart configurator

![](img/slide_extend_RL7818.png)

<span style="color:#FF0000">
Open smart configurator from IDE (CS+)<br><br> 
</span>
    
![](img/slide_extend_RL7819.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
<u>Smart Configurator User's Manual: RL78 API Reference</u>
[back to top](#article_top)

---

# CS+ (RL78) : CC-RL options

![](img/slide_extend_RL7820.png)

![](img/slide_extend_RL7821.png)

<u>Integrated Development Environment User's Manual: RL78 Debug Tool</u>
[back to top](#article_top)

---

# CS+ (RL78) : Debug Tool options

<span style="color:#FF0000">
Select Debug Tool<br><br>
</span>

![](img/slide_extend_RL7822.png)


![](img/slide_extend_RL7823.png)

<u>Integrated Development Environment User's Manual: RL78 Debug Tool</u>
[back to top](#article_top)

---

# Smart Config. : main window (RL78)

![](img/slide_extend_RL7824.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top) 

---

<a id="article_clock"></a>

# Smart Config. : Clock

![](img/slide_extend_RL7825.png)


<span style="color:#FF0000">
Select high speed on chip osc:40MHz<br><br> 
</span>  

<span style="color:#FF0000">
If want to enable PLL , select on chip osc: 20MHz<br><br>
</span>  

![](img/slide_extend_RL7826.png)

![](img/slide_extend_RL7827.png)

![](img/slide_extend_RL7828.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7829.png)

![](img/slide_extend_RL7830.png)

<span style="color:#FF0000">
Enable X1 osc , will use X1 , X2 pin<br><br>
</span>  

![](img/slide_extend_RL7831.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : add component

![](img/slide_extend_RL7832.png)

![](img/slide_extend_RL7833.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_timer"></a>

# Smart Config. : Interval Timer

![](img/slide_extend_RL7835.png)

![](img/slide_extend_RL7834.png)

![](img/slide_extend_RL7836.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
TAUxx timer difference<br><br>
</span>  

![](img/slide_extend_RL7837.png)


<span style="color:#FF0000">
TAUxx timer clock source<br><br>
</span>

![](img/slide_extend_RL7838.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7839.png)

![](img/slide_extend_RL7840.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Press <b>[Generate Code]</b> in Smart config. will automatically generate driver source code under CS+ project<br><br>
</span> 

![](img/slide_extend_RL7841.png)

![](img/slide_extend_RL7842.png)

![](img/slide_extend_RL7843.png)

 

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Re-build project , will see the build result is complete without error<br><br>
</span>

![](img/slide_extend_RL7845.png)

![](img/slide_extend_RL7844.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7846.png)

![](img/slide_extend_RL7847.png)

![](img/slide_extend_RL7848.png)

![](img/slide_extend_RL7849.png)

![](img/slide_extend_RL7850.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Need to manual add interrupt enable and while(1)<br><br>
</span>

```
BSP_EI();

while(1)
{
}

```

<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_TAU0_0_Start(); 
```

![](img/slide_extend_RL7851.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---


<span style="color:#FF0000">
Need to manual add include file , to fix warning<br><br>
</span>

```
#include "r_smc_entry.h"
#include "platform.h"
```

![](img/slide_extend_RL7852.png)

![](img/slide_extend_RL7853.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7856.png)

![](img/slide_extend_RL7854.png)

![](img/slide_extend_RL7855.png)


<span style="color:#FF0000">
Add TIMER interrupt function under <br><br>
</span>  

```
r_Config_TAU0_0_interrupt()
```

![](img/slide_extend_RL7857.png)

![](img/slide_extend_RL7858.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : Timer delay

![](img/slide_extend_RL7860.png)

![](img/slide_extend_RL7859.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : Generate code

<span style="color:#FF0000">
[Generate Code] in Smart configurator , will re-generate driver code <b><u>every time</b></u><br><br>
</span> 

![](img/slide_extend_RL7861.png)

![](img/slide_extend_RL7862.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# CS+ : driver code

<span style="color:#FF0000">
Put custom application code , variable , declaration , between these 2 comment , will merge into driver code when execute [Generate Code] in Smart config<br><br>
</span>  

![](img/slide_extend_RL7863.png)

![](img/slide_extend_RL7864.png)

![](img/slide_extend_RL7865.png)




<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_gpio"></a>

# Smart Config. : GPIO


![](img/slide_extend_RL7866.png)

![](img/slide_extend_RL7867.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Select target GPIO port , to set GPIO input , output<br><br>
</span>

![](img/slide_extend_RL7868.png)

![](img/slide_extend_RL7869.png)

![](img/slide_extend_RL7870.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7871.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : GPIO control example

![](img/slide_extend_RL7873.png)

![](img/slide_extend_RL7874.png)

![](img/slide_extend_RL7872.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# RL78 F24 example code

[https://www\.renesas\.com/en/products/microcontrollers\-microprocessors/rl78\-low\-power\-8\-16\-bit\-mcus/rl78f24\-next\-generation\-actuator\-and\-sensor\-microcontroller](https://www.renesas.com/en/products/microcontrollers-microprocessors/rl78-low-power-8-16-bit-mcus/rl78f24-next-generation-actuator-and-sensor-microcontroller)

![](img/slide_extend_RL7876.png)

![](img/slide_extend_RL7875.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_ext"></a>

# Smart Config. : external int.


![](img/slide_extend_RL7877.png)

![](img/slide_extend_RL7878.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7879.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7880.png)

![](img/slide_extend_RL7881.png)

<span style="color:#FF0000">
Add code when trigger external interrupt INTP2<br><br>
</span>

![](img/slide_extend_RL7882.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_INTC_INTP2_Start();
```

![](img/slide_extend_RL7883.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_i2c"></a>

# Smart Config. : I2C


![](img/slide_extend_RL7884.png)

![](img/slide_extend_RL7886.png)

![](img/slide_extend_RL7885.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7887.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7888.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7889.png)

![](img/slide_extend_RL7890.png)

![](img/slide_extend_RL7891.png)

<span style="color:#FF0000">
Read function example :<br><br>
</span>

```
R_Config_IIC00_Master_Send(…,reg,...)
R_Config_IIC00_Master_Receive(…,data,...)
```

<span style="color:#FF0000">
Write function example :<br><br>
</span>


```
R_Config_IIC00_Master_Send(…,data,...)
```


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : I2C(IICA0)

![](img/slide_extend_RL7893.png)

![](img/slide_extend_RL7892.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7894.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL7895.png)

![](img/slide_extend_RL7896.png)

![](img/slide_extend_RL7897.png)

<span style="color:#FF0000">
Read function example :<br><br>
</span>

```
R_Config_IICA0_Master_Send(…,reg,...)
R_Config_IICA0_Master_Receive(…,data,...)
```
<span style="color:#FF0000">
Write function example :<br><br>
</span>

```
R_Config_IICA0_Master_Send(…,data,...)
```

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_spi"></a>

# Smart Config. : SPI (CSI)

![](img/slide_extend_RL7899.png)

![](img/slide_extend_RL7898.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
To fix conflict , select other SAU port , each SAU channel only support one function at the same time<br><br>
</span>

![](img/slide_extend_RL78100.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : CSI table for SPI/UART/I2C

![](img/slide_extend_RL78101.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78102.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : CPOL/CPHA

* CPOL :
  * 0 : clock idle at LOW
  * 1 : clock idle at HIGH
* CPHA :
  * 0 : 1^st^ EDGE
  * 1 : 2^ND^ EDGE


![](img/slide_extend_RL78103.png)

![](img/slide_extend_RL78104.png)


| CPOL | CPHA | mode | Type |
|:--:|:--:|:--:|:--:|
| 1  | 1 | 3 | 1 |
| 0  | 1 | 1 | 2 |
| 1  | 0 | 2 | 3 |
| 0  | 0 | 0 | 4 |


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : SPI (CSI)

![](img/slide_extend_RL78105.png)

![](img/slide_extend_RL78106.png)

![](img/slide_extend_RL78107.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_CSI01_Start();
```

![](img/slide_extend_RL78108.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_uart"></a>

# Smart Config. : UART

![](img/slide_extend_RL78109.png)

![](img/slide_extend_RL78110.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78111.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78112.png)

![](img/slide_extend_RL78113.png)

![](img/slide_extend_RL78114.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_UART1_Start();
```

![](img/slide_extend_RL78115.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : UART , printf redirect

<span style="color:#FF0000">
Add printf function

1. Add include <stdio.h>
2. Enable library config : C90/C99
3. redirect putchar function
</span> 

![](img/slide_extend_RL78116.png)


<span style="color:#000000">
Ex : redirect putchar in UART<span style="color:#FF0000"><b>0</b></span> 

STMK<span style="color:#FF0000"><b>0</b></span> = 1U;  \/\* disable INTST0 interrupt \*\/
SDR<span style="color:#FF0000"><b>00L</b></span> = (unsigned char)c;
while(STIF<span style="color:#FF0000"><b>0</b></span>  == 0)
{
}
STIF<span style="color:#FF0000"><b>0</b></span>  = 0U\;  \/\* clear INTST0 interrupt flag \*\/
</span>


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_pwm"></a>

# Smart Config. : PWM

<span style="color:#FF0000">
The PWM (pulse width modulation) output function is timer that generate multiple PWM outputs by using <u>a master and multiple slave channels.</u><br>
The pulse cycle <u>(frequency)</u> is set in the master channel.<br>
The pulse width <u>(duration)</u> is set in the slave channel.<br><br>
</span>

![](img/slide_extend_RL78118.png)

![](img/slide_extend_RL78117.png)


<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78119.png)

![](img/slide_extend_RL78120.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78121.png)

![](img/slide_extend_RL78122.png)

![](img/slide_extend_RL78123.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : PWM formula

![](img/slide_extend_RL78124.png)

![](img/slide_extend_RL78125.png)

MCU clock src : 40M , 
clock div : 40M / 2^6 = 625K Hz , 
target freq : 100Hz = 10000 us

![](img/slide_extend_RL78126.png)

![](img/slide_extend_RL78127.png)

period : 1/100 (which is 10000us) = (val_m + 1 ) * (1/ 625K)

=> val_m : 625K/100 – 1 = 6250 – 1 = 6249 (<span style="color:#FF0000"><b>0x1869</b></span>)

duty(%) = val_s / (val_m + 1) *100 , 50/100 = val_s/(val_m + 1)
=> val_s = (1/2)*6250 = 3125 (<span style="color:#FF0000"><b>0xC35</b></span>)

duty(%) = val_s / (val_m + 1) *100 , 75/100 = val_s/(val_m + 1)
=> val_s = (3/4)*6250 = 4687.5 (<span style="color:#FF0000"><b>0x1250</b></span>)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78128.png)

![](img/slide_extend_RL78129.png)

<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_TAU0_2_Start();
```

![](img/slide_extend_RL78130.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_adc"></a>

# Smart Config. : ADC

![](img/slide_extend_RL78132.png)

![](img/slide_extend_RL78131.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RL78133.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : ADC sampling

![](img/slide_extend_RL78134.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : ADC driver

![](img/slide_extend_RL78137.png)

![](img/slide_extend_RL78135.png)

![](img/slide_extend_RL78136.png)

![](img/slide_extend_RL78138.png)

example : 

```
static void __near r_Config_S12AD0_interrupt(void)
{
/* Start user code for r_Config_S12AD0_interrupt. Do not edit comment generated here */
    ADC_Process_in_IRQ();
/* End user code. Do not edit comment generated here */
}

void ADC_Process_in_IRQ(void)
{
    FLAG_PROJ_TRIG_ADC_CH = 1;
}

void GetADC(unsigned char ch)
{
    unsigned short tmp_buffer = 0;

    FLAG_PROJ_TRIG_ADC_CH = 0;
    R_Config_S12AD0_Start();
    while(!FLAG_PROJ_TRIG_ADC_CH);
    R_Config_S12AD0_Get_ValueResult((e_ad_channel_t) ch,&tmp_buffer);
    R_Config_S12AD0_Stop();
    FLAG_PROJ_TRIG_ADC_CH = 0;

    adc_buffer[ch] = tmp_buffer;    
}

```

![](img/slide_extend_RL78139.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# CS+ : Add root path in Path Edit

![](img/slide_extend_RL78140.png)


<span style="color:#FF0000">
add root path under project to fix compile error issue<br><br>
</span>

```
.\
.
```

![](img/slide_extend_RL78141.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# CS+ : Add main loop

<span style="color:#FF0000">
Need to manual add enable interrupt <br><br>
</span>

```
BSP_EI();
```

<span style="color:#FF0000">
Need to manual add main loop , ex : <br><br>
</span>

```
while(1)
{
}
```

![](img/slide_extend_RL78142.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
If not add while loop under main code , program will <b>stop</b> at exit in csstart.asm<br><br>
</span> 

![](img/slide_extend_RL78143.png)

<u>RL78 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# CS+ : entry debug mode

<span style="color:#FF0000">
Make sure <u><b>[DISCONNECT]</b></u> CS+ project before REMOVE DEBUGGER tool <br><br>
</span>  

![](img/slide_extend_RL78144.png)

download program after rebuild
![](img/slide_extend_RL78147.png)

debug function
![](img/slide_extend_RL78145.png)
![](img/slide_extend_RL78146.png)
![](img/slide_extend_RL78149.png)
![](img/slide_extend_RL78150.png)

![](img/slide_extend_RL78148.png)


<u>Integrated Development Environment User's Manual: RL78 Debug Tool</u>
[back to top](#article_top)    

---

# Renesas Flash Programmer

![](img/slide_extend_RL78151.png)

![](img/slide_extend_RL78153.png)

![](img/slide_extend_RL78152.png)

![](img/slide_extend_RL78154.png)

<u>Renesas Flash Programmer V*.** Flash memory programming softwareUser's Manual </u>
[back to top](#article_top)    

---

<a id="article_tips"></a>

# Tips : Convert to Hex


![](img/slide_extend_RL78155.png)

![](img/slide_extend_RL78156.png)
   

---

# Tips : Emulator power on MCU

![](img/slide_extend_RL78157.png)

![](img/slide_extend_RL78158.png)
   

---

# Tips : map file display

![](img/slide_extend_RL78159.png)

<span style="color:#FF0000">
Function address<br>
size display<br>
location assignment<br>
Code size <br>
RAM size display<br><br>
</span>

variable place address (SRAM)
![](img/slide_extend_RL78160.png)

function place address (FLASH)
![](img/slide_extend_RL78161.png)

section size display in map file
![](img/slide_extend_RL78162.png)
   

---

# Tips : section message display

![](img/slide_extend_RL78163.png)


Display section message
![](img/slide_extend_RL78164.png)
   

---

# Tips : section size display in output window

![](img/slide_extend_RL78165.png)

![](img/slide_extend_RL78166.png)
   

---

# Tips : Backup times (generate code)

![](img/slide_extend_RL78167.png)
   

---

# Tips : section define modify

![](img/slide_extend_RL78168_1.png)
   

---

# Tips : section define (const)

<span style="color:#FF0000">
ADD [<b>privateData.const</b>] in Section Settings<br>
1. Select on [.data] in Section<br>
2. Select [Add]<br>
3. Key in [<b>privateData.const</b>] <br><br>
</span>  

![](img/slide_extend_RL78168.png)

| item | note |
|:--:|:--:|
| data  | variables with initial value  |
| bss  | variables with no initial value  |
| text  | program code  |
|<span style="color:#FF0000"><b>const</b></span>   | <span style="color:#FF0000"><b>constant data</b></span>  |

![](img/slide_extend_RL78169.png)

Code assignment example
![](img/slide_extend_RL78170.png)

<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)
   
---

# Tips : section define (data)

<span style="color:#FF0000">
ADD [<b>privateData.data</b>] in Section Settings<br>
1. Select on [.data] in Section<br>
2. Select [Add]<br>
3. Key in [<b>privateData.data</b>] <br><br>
</span>

![](img/slide_extend_RL78171.png)

| item | note |
|:--:|:--:|
| <span style="color:#FF0000"><b>data</b></span>  | <span style="color:#FF0000"><b>variables with initial value</b></span>  |
| bss  | variables with no initial value  |
| text  | program code  |
|const   | constant data  |

![](img/slide_extend_RL78173.png)

Code assignment example
![](img/slide_extend_RL78172.png)

<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)

---

# Tips : section define (bss)

<span style="color:#FF0000">
ADD [<b>privateData.bss</b>] in Section Settings<br>
1. Select on [.bss] in Section<br>
2. Select [Add]<br>
3. Key in [<b>privateData.bss</b>] <br><br>
</span>


![](img/slide_extend_RL78174.png)


| item | note |
|:--:|:--:|
| data  | variables with initial value  |
| <span style="color:#FF0000"><b>bss</b></span>  | <span style="color:#FF0000"><b>variables with no initial value</b></span>  |
| text  | program code  |
|const   | constant data  |

![](img/slide_extend_RL78176.png)

Code assignment example
![](img/slide_extend_RL78175.png)

<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)   

---

# Tips : section define (not assigned address)

<span style="color:#FF0000">
New add custom define section as below <br>
Also able to define the address base on application<br><br>
</span>

![](img/slide_extend_RL78177.png)

Code assignment example
![](img/slide_extend_RL78178.png)

check the address in map file
![](img/slide_extend_RL78179.png)


<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)


---

# Tips : section define (assigned address)

<span style="color:#FF0000">
New add custom define section as the capture<br>
Also able to define the address base on application<br><br>
</span>

![](img/slide_extend_RL78180.png)

Code assignment example
![](img/slide_extend_RL78181.png)

check the address in map file
![](img/slide_extend_RL78182.png)


<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)

---

# Tips : section allocation , size

![](img/slide_extend_RL78183.png)

<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)

---

# Tips : project split


<span style="color:#FF0000">
Use [<b> Build Mode Setting </b>] , to split different macro in different project setting if necessary<br><br>
</span>

![](img/slide_extend_RL78184.png)

Project split example , modify the projec name
![](img/slide_extend_RL78185.png)

![](img/slide_extend_RL78186.png)

![](img/slide_extend_RL78187.png)

Add the macro define for extra project 
![](img/slide_extend_RL78188.png)

<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)

---

# Tips : E1203124

<span style="color:#FF0000">
[Direct Error Cause]
Writing to the on-chip debug reserved area is prohibited.(address: 0x00000002)(E1203124)<br><br>
</span>

![](img/slide_extend_RL78189.png)

how to fix
![](img/slide_extend_RL78190.png)

![](img/slide_extend_RL78191.png)

<u>CC-RL Compiler User's Manual</u>
[back to top](#article_top)

---

