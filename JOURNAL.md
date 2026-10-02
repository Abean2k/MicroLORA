---
title: "Micro LORA Tag"
github: "https://github.com/Abean2k/MicroLORA"
description: "A small 20-gram lora tag, with a receiver as well. Making this for my model rockets, because they keep drifting off like 1km and then I lose my rockets :( "
created_at: "2026-09-30"
total_time: "1h 30m"
---

# October 1, 2026: Planning (MCU and LORA Module Selection)
<!-- fabricate:entry 64 -->

Today I just quickly planned out what I wanted this project to be, what LORA module would work, and which MCU would be easy to work with. 


## Chosen LORA Module: E22-900M22S

While looking for the LORA module, I had a few requirements. First, it had to have at least 5km of range (verified), needed to be small-ish, had to be under 10 dollars each, be 900-915hz, and it had to have decent documentation. The company that I ended up selecting was E-Byte, as they make a lot of modules, especially in that 900-915 hz range. After a bit of reading the website and seeing which modules were readily available, I need up choosing the E22-900M22S. It had a 7km nominal range, it's available on Aliexpress for about $5 per module, and it is pretty easy to use. 

### Picture of the Lora Module:
![](https://fabricate.hackclub-assets.com/17564238fe92caf464ea16d22b5170dab267c0dc1303099686d64f36d395c16b/image.png)


## Chosen MCU: ESP32-C3 Module 
While this might change later, I choose the esp32-c3 because I have worked with esp32 moudles before and I can use the Wi-Fi for the receiver interface and as a close in system on the transmitter. 

### Notes:
I currently just plan on using the same Esp32-c3 on both the small transmitter and the receiver, however I am thinking of changing the MCU on the transmitter as the c3 might be to big for the 30x30 mm size goal. The LORA modules will 100% be the same between both the transmit and receiver though.

**Total time spent: 1h 30m**
