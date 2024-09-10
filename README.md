# Heltec LoRa 32 V.3
 Ex for Heltec LoRa 32 V.3

ในไฟล์ heltec lora v3(ตัวไมโครคอนโทรลเลอร์ใน Code นี้จะรอรับข้อมูลตลอด) 
   วิธีเล่นคือ กดที่ปุ่ม PRG สำหรับการส่งข้อมูล(เมื่อส่งไปแล้วต้องรอ 5 วิเพื่อส่งข้อมูลใหม่)

ในไฟล์ heltec lora v3 Tx_Rx(จำลองการเป็น Node) และ heltec lora v3 Rx_Tx(จำลองการเป็น Gateway)
   State Send คือ การส่งข้อมูล
   State WAIT คือ รอรับข้อมูล
   heltec lora v3 Tx_Rx(จำลองการเป็น Node)
    -ส่งก่อนแล้วจึงเปลี่ยนมาเป็นรอรับข้อมูล
   heltec lora v3 Rx_Tx(จำลองการเป็น Gateway)
    -รอรับก่อนเมื่อได้รับข้อมูลแล้วจะส่งกลับไป
   
