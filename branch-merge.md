
# วิธีการรวม Branch (Merge Branch)

หลังจากการแก้ไขโค้ดใน Branch ที่สร้างขึ้นมาเสร็จสมบูรณ์ เราสามารถรวม changed ที่เกิดขึ้นใน Branch อื่นเข้ากับ Branch ที่ต้องการได้

1. จาก VSCode เลือกเปิด Branch ที่ต้องการเป็น**ตัวตั้ง** มาใช้งาน
2. เปิด **View > Command Pallete**
3. หา และเลือกคำสั่ง **Git: Merge Branch...**
4. เลือก Branch ที่ต้องการนำ changed มารวมกับ **Branch ตัวตั้ง**ที่เราเปิดใช้ปัจจุบัน
5. เช็คว่า code มี conflict ไหม ถ้ามีก็แก้ไขให้เรียบร้อย และ commit ตามปกติ