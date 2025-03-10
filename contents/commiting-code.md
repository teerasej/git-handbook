
# การ commit การเปลี่ยนแปลงของ code ด้วย Visual Studio Code

ใน Visual Studio Code จะมีส่วน Source Control ที่ช่วยจัดการโดยเฉพาะ

![2019-07-24_22-22-16](https://user-images.githubusercontent.com/85179/61806563-18589f80-ae62-11e9-8774-04d45162b742.png)

1. ส่วนจัดการ Source Control
2. ไฟล์ที่มีการเปลี่ยนแปลงจาก commit ล่าสุด จะมาแสดงใน รายการ **changed**
3. เราสามารถเลือกไฟล์ที่อยู่ในรายการ **changed** เข้าสู่รายการ **Staged changed** 
4. ถ้ามีไฟล์อยู่ในรายการ **Staged changed** ไฟล์ในรายการนี้เท่านั้น จะถูก commit 
5. เราสามารถกรอก ข้อความ note ไว้สำหรับการ commit แต่ละครั้งได
6. กดปุ่ม commit เพื่อยืนยัน ไฟล์และ note ที่กรอก (สามารถใช้ Ctrl + Enter แทนปุ่มลัดได้)

## Exercise 1: Create and commit file

1. สร้างไฟล์ใหม่ชื่อ `index.html` และใส่ข้อความดังนี้

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

2. บันทึกไฟล์
3. จะสังเกดเห็นว่าในขณะที่เราเปิดดู Explorer Activity จะมีไฟล์ `index.html` เป็นสีเขียว แสดงว่ามีการเปลี่ยนแปลงแบบเพิ่มไฟล์ 
   > ความสามารถนี้เป็นของ Visual Studio Code ซึ่งโปรแกรมอื่นๆ จะมีการแสดงผลต่างกันไป
4. สังเกตในส่วน Source Control Activity ทางด้านซ้ายมือ จะมีเลข 1 แสดงว่ามีไฟล์ที่เปลี่ยนแปลง 1 ไฟล์
5. กดเปิดดูในส่วน Source Control จะเห็นไฟล์ `index.html` อยู่ในรายการ **changed**
6. กดปุ่ม `+` ที่อยู่ข้างหน้าชื่อไฟล์ `index.html` จะเห็นว่าไฟล์ `index.html` จะเปลี่ยนจาก **changed** เป็น **Staged changed**
7. กรอกข้อความ note ในช่อง `Message (Ctrl+Enter to commit)` ว่า `Add home page` แล้วกดปุ่ม `commit` หรือใช้ Ctrl + Enter
8. จะเห็นว่าไฟล์ `index.html` จะหายไปจากรายการ **Staged changed** และเป็นไฟล์ที่ commit แล้ว

## Exercise 2: Modify and commit file

1. แก้ไขไฟล์ `index.html` ให้เป็นดังนี้

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>สวัสดี ชาวโลก</h1>
</body>
</html>
```

2. บันทึกไฟล์
3. สังเกตในส่วน Source Control Activity ทางด้านซ้ายมือ จะมีเลข 1 แสดงว่ามีไฟล์ที่เปลี่ยนแปลง 1 ไฟล์ (ใน Explorer activity จะเห็นไฟล์ `index.html` เป็นสีเหลือง)
4. กดเปิดดูในส่วน Source Control จะเห็นไฟล์ `index.html` อยู่ในรายการ **changed**
5. กดดูไฟล์ `index.html` จะเห็นการเปลี่ยนแปลงที่เกิดขึ้น แสดงขึ้นมาเทียบระหว่างไฟล์ที่ commit ไปล่าสุด และที่เปลี่ยนแปลงล่าสุด
6. กดปุ่ม `+` ที่อยู่ข้างหน้าชื่อไฟล์ `index.html` จะเห็นว่าไฟล์ `index.html` จะเปลี่ยนจาก **changed** เป็น **Staged changed**
7. กรอกข้อความ note ในช่อง `Message (Ctrl+Enter to commit)` ว่า `Change greeting message` แล้วกดปุ่ม `commit` หรือใช้ Ctrl + Enter
8. จะเห็นว่าไฟล์ `index.html` จะหายไปจากรายการ **Staged changed** และเป็นไฟล์ที่ commit แล้ว

## Tips: ย้อนดู Git history

- เราสามารถติดตั้ง extension ที่ชื่อ [`Git History`](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) จาก Visual Studio Code ได้ ซึ่งจะช่วยให้เราเห็นข้อมูลเพิ่มเติมของ commit ได้ง่ายขึ้น  