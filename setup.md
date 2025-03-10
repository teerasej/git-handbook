
# การติดตั้ง Git client 

## 1. สมัครสร้าง Github Account (ถ้ายังไม่มี)

- ถ้ายังไม่มี github account [ให้สมัครสร้างบัญชีผู้ใช้ผ่าน link นี้](http://github.com/signup)

## 2. Download และติดตั้ง Visual Studio Code (ถ้ายังไม่มี)

1. [ดาวน์โหลดไฟล์ติดตั้งที่เหมาะสมกับระบบปฏิบัติการของเรา จากที่นี่](https://code.visualstudio.com/)
2. ดาวน์โหลดไฟล์เสร็จแล้ว ให้ดำเนินการติดตั้งให้เรียบร้อย

## 2. Download Git client setup file (ถ้ายังไม่มี)

1. [ดาวน์โหลดไฟล์ติดตั้งที่เหมาะสมกับระบบปฏิบัติการของเรา จากที่นี่](https://git-scm.com/downloads)
2. ดาวน์โหลดไฟล์เสร็จแล้ว ให้ดำเนินการติดตั้งให้เรียบร้อย

## 3. ตั้งค่า Username และ Email 

1. เปิดโปรแกรม Command Line Interface
   - Windows สามารถใช้โปรแกรม Command Prompt หรือ Windows Terminal ก็ได้
   - MacOS สามารถใช้ Terminal (Bash หรือ Zshell ก็ได้)
  
2. รันคำสั่งด้านล่าง เพื่อกำหนด git user ของเรา ให้กับระบบ **โดยแทนที่คำว่า Your Name ด้วยชื่อภาษาอังกฤษของเรา**

```bash
git config user.name "Your Name"
```

และกด enter ถ้าถูกต้อง จะเหมือนไม่มีตอบสนองคำสั่ง ให้ไปขั้นตอนต่อไปได้เลย

3. รันคำสั่งด้านล่าง เพื่อกำหนด git email ของเรา ให้กับระบบ **โดยแทนที่คำว่า your_email@example.com ด้วยชื่อภาษาอังกฤษของเรา**

```bash
git config user.email "your_email@example.com"
```

และกด enter ถ้าถูกต้อง จะเหมือนไม่มีตอบสนองคำสั่ง
