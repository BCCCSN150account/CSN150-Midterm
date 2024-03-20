# Cybersecurity 150 Lab

## Name of Project
ESP32 Amazing Cyber Program with Whatsapp

## Purpose
Create an ESP32 project using the ESP32CAM.

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Link to Documentation Followed
- [GitHub - martin-ger/esp32_nat_router](https://github.com/martin-ger/esp32_nat_router)

##### Youtube Video 1: 

##### Youtube Video 2: 

##### Other Links: 


## Steps I followed
1. I went to the Randomnerd tutorial website and selected the ESP32: Send Messages to WhatsApp guide.
2. Next I added +34 621 331 709 which is the callmebot api number to my Whatsapp
3. I installed the URLencode library on the Arduno application.
4. I used the code provided by randomnerdtutorial to process with sending the messages.
5. I placed the ssid and wi-fi password for my hotspot into the code.
6. Finally I placed the API code into my code and was able to receive the message.

## Problems
During step 2 I attempted to send the message while using the Bronx community college wifi and the message was not being sent. I fix this issue by using my cellphones wifi Hotspot and then I was able to recevie the message from the callmebot with the API that I would need later on and I was able to proceed with the folowing steps.

Example
1. Arduino code will not load on ESP32 Cam.
   Answer: Camera drivers were incorrect I needed to install the driver: [https://www.wch-ic.com/downloads/CH341SER_ZIP.html](https://github.com/martin-ger/esp32_nat_router).  I used file, "CH341SER.ZIP" and it worked.
