# IOTA_price_ticker_TTGO-TS_1.8-TFT
Simple IOTA price ticker by using TTGO-TS_1.8 TFT and CoinMarketcap API for Arduino IDE
<br>

<p><img src="https://oxinon.com/wp-content/uploads/2019/03/IOTA-ticker.png" alt="Cover" width="100"></p>
IOTA ticker on Youtube: https://www.youtube.com/watch?v=napduhMtkBk&t=94s
<br>
<br>
<p><img src="https://oxinon.com/wp-content/uploads/2019/03/BTC-ticker.png" alt="Cover" width="100"></p>
BTC ticker on Youtube: https://www.youtube.com/watch?v=0brdvBQd6Ao&t=9s
<br>
<br>

* * *

+ [Add ESP32 Arduino IDE](#ESP32)
+ [Libraries for Arduino IDE](#libraries)
+ [The function](#function)
+ [Screen shifting Issue](#issue)

* * *

<a name="ESP32"></a><h2>Add ESP32 in Arduino IDE</h2>
Before we can start compiling, the Arduino must have the TTGO-TS board, based on an ESP32 in the board selection available.
The instruction on https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
In board selector you can select "ESP32 Dev Module" for TTGO-TS.
<br>
<br>

<a name="libraries"></a><h2>Libraries for Arduino IDE</h2>
Now we add libraries for Arduino IDE:

Adafruit_GFX.h <p>
Adafruit_ST7735.h (see "Screen shifting Issue" Adafruit_ST7735_and_ST7789_Library-TS18 if you have Screen shifting)<p>
ArduinoJson.h <p>
CoinMarketCapApi.h <p>
<br>
<br>

<a name="function"></a><h2>The Function</h2>
<p><img src="https://oxinon.com/wp-content/uploads/2019/03/BTC-ticker.png" alt="Cover" width="100"></p>
<p><img src="https://oxinon.com/wp-content/uploads/2019/03/BTC-change-ticker.png" alt="Cover" width="100"></p>
<p><img src="https://oxinon.com/wp-content/uploads/2019/03/BTC-error-ticker.png" alt="Cover" width="100"></p>

<br>
<br>

<a name="issue"></a><h2>Screen shifting Issue</h2>


<p><img src="https://oxinon.com/wp-content/uploads/2019/03/Display-Mapping.png" alt="Cover" width="100"></p>
<br>
<p><img src="https://oxinon.com/wp-content/uploads/2019/03/field-test.png" alt="Cover" width="100"></p>
<br>

