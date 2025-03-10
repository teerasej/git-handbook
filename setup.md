
# การติดตั้ง Git client 

## 1. Download Installation files

- [ดาวน์โหลดไฟล์ติดตั้งที่เหมาะสมกับระบบปฏิบัติการของเรา จากที่นี่](https://git-scm.com/downloads)

เสร็จแล้วดำเนินการติดตั้งให้เรียบร้อย

## 2. ตั้งค่า Username และ Email 

1. เปิดโปรแกรม Command Line Interface
   - Windows สามารถใช้โปรแกรม Command Prompt หรือ Windows Terminal ก็ได้
   - MacOS สามารถใช้โปรแกรม Terminal (Bash หรือ Zshell ก็ได้)
  
2. รันคำสั่งด้านล่าง เพื่อกำหนด git user ของเรา ให้กับระบบ **โดยแทนที่คำว่า Your Name ด้วยชื่อภาษาอังกฤษของเรา**

```bash
git config user.name "Your Name"
```
```bash
# ตัวอย่าง
git config user.name "Teerasej Jiraphatchandej"
```

และกด enter ถ้าถูกต้อง จะเหมือนไม่มีตอบสนองคำสั่ง ให้ไปขั้นตอนต่อไปได้เลย

3. รันคำสั่งด้านล่าง เพื่อกำหนด git email ของเรา ให้กับระบบ **โดยแทนที่คำว่า your_email@example.com ด้วยชื่อภาษาอังกฤษของเรา**

```bash
git config user.email "your_email@example.com"
```
```bash
# ตัวอย่าง
git config user.email "training@nextflow.in.th"
```


และกด enter ถ้าถูกต้อง จะเหมือนไม่มีตอบสนองคำสั่ง แต่ถือว่าเป็นการ config เรียบร้อยแล้ว
