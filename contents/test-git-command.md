
# ทดสอบใช้งาน Git command

## 1. Git version

- สามารถทดสอบคำสั่ง git command ด้านล่างได้ ผ่านโปรแกรม
  - Visual Studio Code > New Terminal 
  - MacOS: เปิด Terminal
  - Windows: เปิด Command prompt 

แล้วพิมพ์คำสั่งด้านล่าง

```bash
git --version
```
เราควรเห็นข้อความประมาณด้านล่าง 

```bash
git version 2.39.5
```

## 2. ทดสอบแสดงการตั้งค่า username และ email ของ git บนเครื่อง

รันคำสั่งด้านล่าง 

```bash
git config --list
```

เราควรเห็นข้อความประมาณด้านล่าง จะแตกต่างไปตามระบบ แต่ให้สังเกต username และ email ว่ามีหรือไม่

```bash
credential.helper=osxkeychain
init.defaultbranch=main
user.name=Teerasej
user.email=training@nextflow.in.th
pull.rebase=false
core.repositoryformatversion=0
```

ถ้าไม่มี ให้ใส่ค่า username และ email ด้วยคำสั่งด้านล่าง โดยแทนที่ **"Your Name"** และ **"username@example.com"** ด้วยข้อมูลของเรา

```bash
git config --global user.name "Your Name"
```

```bash
git config --global user.email "username@example.com"
```

## 3. Setup Git repository บนเครื่อง

1. ถ้าใช้ Visual Studio Code ให้สร้าง folder ใหม่ 
2. เปิดโฟลเดอร์นั้นใน Visual Studio Code 
3. เปิดเมนู Terminal > New Terminal 
4. รันคำสั่งด้านล่าง

```bash
git init -b main
```

เราจะเห็นคำสั่งประมาณด้านล่าง 

```bash
Initialized empty Git repository in /home/teerasej/xxx/.git/

Switched to a new branch 'main'
```

## 4. เช็คสถานะของ Git Repository 

รันคำสั่งด้านล่าง

```bash
git status
```

เราควรเห็นข้อความประมาณด้านล่าง 

```bash
On branch main

 No commits yet

 nothing to commit (create/copy files and use "git add" to track)
```
