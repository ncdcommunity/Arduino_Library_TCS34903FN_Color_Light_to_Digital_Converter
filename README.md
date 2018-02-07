[![TCS34903FN](TCS34903FN_I2C.png)](https://store.ncd.io/product/tcs34903fn-color-light-to-digital-converter-i2c-mini-module/)

# TCS34903FN

The TCS3490 provides color and IR (red, green, blue, clear and IR) light sensing using I2C communications. The color sensing provides for improved accuracy lux and color temperature measurements typically used to adjust the backlight intensity and correct the display color gamut. Additionally it can be used for light source type detection as it reports the IR content of the light.
This Device is available from www.ncd.io 

[SKU: TCS34903FN_I2CS]

(https://store.ncd.io/product/tcs34903fn-color-light-to-digital-converter-i2c-mini-module/)
This Sample code can be used with Arduino.

Hardware needed to interface TCS34903FN sensor with Arduino

1. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-nano/">Arduino Nano</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-micro-with-i2c-expansion-port/">Arduino Micro</a>

3. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-uno/">Arduino uno</a>

4. <a href="https://store.ncd.io/product/dual-i2c-shield-for-arduino-due-with-modular-communications-interface/">Arduino Due</a>

5. <a href="https://store.ncd.io/product/tcs34903fn-color-light-to-digital-converter-i2c-mini-module/">TCS34903FN Color Light To Digital Converter</a>

6. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

TCS34903FN:

The TCS3490 provides color and IR (red, green, blue, clear and IR) light sensing using I2C communications. The color sensing provides for improved accuracy lux and color temperature measurements typically used to adjust the backlight intensity and correct the display color gamut. Additionally it can be used for light source type detection as it reports the IR content of the light.

Applications:

• Ambient light sensing

• Color temperature sensing

• Industrial process control

• Medical diagnostics.

How to Use the TCS34903FN Arduino Library

The TCS34903FN has a number of settings, which can be configured based on user requirements.
          
1.Accessing timer:The following command is used to set the accessing time of sensor.

          tcs.setATime(ATIME_712MS);               // Cycles: 256, Time: 712 ms Max Count: 65535
            
 2.Waiting time:The following command is used to set the waiting time of sensor.
 
          tcs.setWTime(WTIME_1);                      // Wait Time: 1, Time (WLONG = 0): 2.78 ms Time (WLONG = 1):  0.03 sec
            
3.Gain setup:The following command is used to set the gain for color.

          tcs.setColorGain(AGAIN_1X);                 // Color Gain: 1X
