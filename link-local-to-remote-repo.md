
# กำหนด remote git url ให้กับ local git repository

หลังจากสร้าง Remote Repository บน Github แล้ว เราจะสามารถใช้คำสั่งในส่วนนี้ได้

![2019-07-24_23-17-18](https://user-images.githubusercontent.com/85179/61810951-a173d480-ae6a-11e9-952a-965378e7898a.png)

1. copy คำสั่งที่ 1 มารันใน Terminal ของโปรเจค ([ต้องมีการรันคำสั่ง git init เสร็จแล้ว](/create-local-git-repo.md))
2. สั่ง commit changed ทั้งหมด เพื่อให้สามารถ push code ได้
3. ใช้คำสั่งที่ 2 รันใน Terminal 

หรือถ้าใช้ Visual Studio Code จะสามารถคลิกปุ่มด้านซ้ายล่าง

![2019-07-24_23-34-36](https://user-images.githubusercontent.com/85179/61811477-bc931400-ae6b-11e9-92b9-40413ff6d383.png)

หรือไปที่ Source Control 

    1. ต้องไม่มี file **changes** เหลืออยู่ในรายการ ถึงจะสามารถ pull หรือ push โค้ดจาก remote repository ได้
    2. กดเปิด **option**
    3. เลือกคำสั่ง **push** 

![2019-07-24_23-33-15](https://user-images.githubusercontent.com/85179/61811473-bac95080-ae6b-11e9-92a7-453102857056.png)
