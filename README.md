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
พิมพ์คำว่า help
## ![image](https://github.com/user-attachments/assets/41328c63-e07f-49ce-93c1-a827319486e4)
พิมพ์คำสั่ง consolehelp
## ![image](https://github.com/user-attachments/assets/1eda2c87-18dd-40c6-96de-affc124695ba)
พิมพ์คำสั่ง help consoletest
## ![image](https://github.com/user-attachments/assets/9faad475-0aef-47f7-8ad7-284534a6cfe6)
4.คัดลอก และ เพิ่มเนื้อหาตามนี้
## ![image](https://github.com/user-attachments/assets/da113bd8-2dd7-42d0-ac0f-b1a66cf52097)
และ เพิ่ม ESP_ERROR_CHECK(esp_console_cmd_register(&led));
### ![image](https://github.com/user-attachments/assets/c8a7e39f-4fcd-4f81-8706-4aed08efb83f)
และ คัดลอก ฟังก์ชั่นด้านบนมาแก้ไข ดังนี้
## ![image](https://github.com/user-attachments/assets/78b22f8a-5b6a-4336-a667-4405f293d3a4)
build และ flash และทดสอบพิมพ์ led 1 on
## ![image](https://github.com/user-attachments/assets/43c0a605-7925-4bdd-aeeb-9f6c015a05b5)
เพิ่มเนื้อหาดังนี้
## ![image](https://github.com/user-attachments/assets/87e33054-6849-4091-83b4-4de78e2067be)
build และ flash และทดสอบพิมพ์ led 1 on
## ![image](https://github.com/user-attachments/assets/7305f0a4-1861-48ce-a9a5-45c41e5fcb4b)
เพิ่มคำสั่งดังนี้
## ![image](https://github.com/user-attachments/assets/077e6979-2fa8-4f08-be54-3ce96d31ebb0)
build และ flash และทดสอบพิมพ์ led 1 on และ led y off แล้วสังเกตุผลลัพธ์
## ![image](https://github.com/user-attachments/assets/30fd51a1-e450-4421-b8d9-c282547d17ab)
เพิ่มคำสั่งดังนี้
## ![image](https://github.com/user-attachments/assets/17973c82-5537-4d23-986c-802ec6f5feec)
build และ flash และทดสอบพิมพ์ led 1 on และ led 1 off
## ![image](https://github.com/user-attachments/assets/f3de87ce-1a0d-4d7d-ad21-8168434a09e4)
5.เพิ่ม gpio_set_direction(GPIO_NUM_16, GPIO_MODE_OUTPUT);
## ![image](https://github.com/user-attachments/assets/1630ee0c-205e-4670-b46e-1783d1e08f28)
และเพิ่ม gpio_set_level(led_no,led_status);  ตามภาพ
## ![image](https://github.com/user-attachments/assets/3355cc92-53b0-42d2-af8c-129c9440437b)
ทดสอบ พิมพ์คำสั่ง led 16 on ผลลัพธ์ledจะติด
## ![image](https://github.com/user-attachments/assets/fc5cbe67-46a6-4026-853e-d4517b4b1828)
6.เพิ่มส่วนของenable
## ![image](https://github.com/user-attachments/assets/c980d5ad-372c-49aa-98d3-ba91c804fcdd)
*** ต้องลบ gpio_set_direction(GPIO_NUM_16, GPIO_MODE_OUTPUT); ออก
## ![image](https://github.com/user-attachments/assets/9e0e87fa-1945-49de-88ad-48f2ed9c2232)
build และ flash และทดสอบพิมพ์ led 17 enable และ led 17 on
## ![image](https://github.com/user-attachments/assets/2a9c9b8e-1ed7-4b48-9dc0-c0f942d79570)

 https://github.com/fulk2014/uart_repl-main   ไฟล์งาน





