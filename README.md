# Heltec LoRa 32 V.3
"***ต่อเสาสัญญาณก่อนใช้งานทุกครั้ง!!!***"<br>
 Ex for Heltec LoRa 32 V.3<br>
 
ในไฟล์ heltec lora v3(ตัวไมโครคอนโทรลเลอร์ใน Code นี้จะรอรับข้อมูลตลอด)<br>
   -วิธีเล่นคือ กดที่ปุ่ม PRG สำหรับการส่งข้อมูล(เมื่อส่งไปแล้วต้องรอ 5 วิเพื่อส่งข้อมูลใหม่)<br> 
   
ในไฟล์ heltec lora v3 Tx_Rx(จำลองการเป็น Node) และ heltec lora v3 Rx_Tx(จำลองการเป็น Gateway)<br>

   State Send คือ การส่งข้อมูล<br> 
   State WAIT คือ รอรับข้อมูล<br> 
   
   heltec lora v3 Tx_Rx(จำลองการเป็น Node)<br> 
    -ส่งก่อนแล้วจึงเปลี่ยนมาเป็นรอรับข้อมูล(delay 5 วิ)<br> 
   heltec lora v3 Rx_Tx(จำลองการเป็น Gateway)<br> 
    -รอรับก่อนเมื่อได้รับข้อมูลแล้วจะส่งกลับไป(delay 5 วิ)<br> 
   
 แหล่งอ้างอิง<br>
 Code ตัวอย่าง : https://github.com/ropg/heltec_esp32_lora_v3/tree/main<br>
 Code ทดสอบ : https://khunsomsak.medium.com/heltec-wifi-lora-32-v3-c7319bfc560<br>
 ข้อมูลของ Heltec LoRa 32 V3 : https://heltec.org/project/wifi-lora-32-v3/<br>
