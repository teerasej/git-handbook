
# วิธีการรวม Branch (Merge Branch)



หลังจากการแก้ไขโค้ดใน Branch ที่สร้างขึ้นมาเสร็จสมบูรณ์ เราสามารถรวม changed ที่เกิดขึ้นใน Branch อื่นเข้ากับ Branch ที่ต้องการได้

## 1. การรวม Branch ที่สร้างขึ้นมากับ Branch ตัวหลัก

1. จาก VSCode เลือกเปิด Branch ที่ต้องการเป็น**ตัวหลัก** มาใช้งาน
2. เปิด **View > Command Pallete**
3. หา และเลือกคำสั่ง **Git: Merge Branch...**
4. เลือก Branch ที่ต้องการนำ changed มารวมกับ **Branch ตัวตั้ง**ที่เราเปิดใช้ปัจจุบัน
5. เช็คว่า code มี conflict ไหม ถ้ามีก็แก้ไขให้เรียบร้อย และ commit ตามปกติ
6. หลังจากนั้น กดปุ่ม **Push** หรือ **Sync** เพื่อส่ง changed ไปยัง remote repository ของเรา
7. หลังจากนั้นลองขึ้นไปดูใน remote repository ว่า changed ที่เรา commit ไปมีอยู่ใน remote repository หรือไม่

## 2. การลบ Branch ที่ไม่ใช้แล้วทิ้ง

1. สังเกตว่าการ merge จะทำให้ Branch ที่เรา merge มากับ Branch ตัวหลัก จะมี changed ทั้งหมดของ Branch ที่ merge มาด้วย
2.  Branch ที่ merge มาจะยังคงอยู่ และสามารถใช้งานต่อได้
3. แต่ถ้าเราต้องการลบ Branch ที่ merge มา เราสามารถลบได้โดยการเปิด **View > Command Pallete** แล้วเลือกคำสั่ง **Git: Delete Branch...** แล้วเลือก Branch ที่ต้องการลบ