# The-Last-repo-read-eval-print-loop-REPL
## ขั้นตอนการทดลอง
1.กด show example หา uart_repl สร้างโปรเจคใหม่






## Reference
### ตำแหน่งขาของ ESP32

![image](https://github.com/user-attachments/assets/7c29cbd2-c7ec-4a8d-9129-355cf9fa44bc)

### การเชื่อมต่อ ESP32 กับ USB

![image](https://github.com/user-attachments/assets/7f11041f-d8dc-493f-b609-fb6c0fa71b7a)



2.เปลี่ยนขา 
## ![image](https://github.com/user-attachments/assets/f693048a-39d2-41e3-a4de-59392f29ebcb)

3.ทำการbuildแล้วก็flashลงบอร์ด
## ![image](https://github.com/user-attachments/assets/8a679d30-29cf-46bb-bebb-e1f3d0a950f9)
พิมค์คำว่า help
## ![image](https://github.com/user-attachments/assets/41328c63-e07f-49ce-93c1-a827319486e4)
พิมค์คำสั่ง consolehelp
## ![image](https://github.com/user-attachments/assets/1eda2c87-18dd-40c6-96de-affc124695ba)
พิมค์คำสั่ง help consoletest
## ![image](https://github.com/user-attachments/assets/9faad475-0aef-47f7-8ad7-284534a6cfe6)
4.คัดลอก และ เพิ่มเนื้อหาตามนี้
## ![image](https://github.com/user-attachments/assets/da113bd8-2dd7-42d0-ac0f-b1a66cf52097)
และ เพิ่ม ESP_ERROR_CHECK(esp_console_cmd_register(&led));
### ![image](https://github.com/user-attachments/assets/c8a7e39f-4fcd-4f81-8706-4aed08efb83f)
และ คัดลอก ฟังก์ชั่นด้านบนมาแก้ไข ดังนี้
## ![image](https://github.com/user-attachments/assets/78b22f8a-5b6a-4336-a667-4405f293d3a4)
build และ flash





