
# วิธีการสร้าง Branch 

Branch เหมือนเป็นการทำสำเนาโปรเจคออกมาเป็นอีก copy หนึง มักใช้ตอนที่เราจะเริ่มเปลี่ยนแปลงโค้ดในโปรเจค เช่น

1. เพิ่ม features
2. แก้ bug

## 1. การสร้าง Branch ในโปรเจค ด้วย VSCode

1. จาก Visual Studio Code ให้เปิดโฟลเดอร์โปรเจคที่เราต้องการสร้าง Branch
2. เปิดเมนู **View > Command Paletted** (Ctrl + Shift + P)
3. เลือกคำสั่ง **Git: Create Branch...**
4. ตั้งชื่อ Branch ว่า 
   ```
   add link
   ``` 
5. กด Enter

    จะสังเกตง่ายที่สุดที่มุมล่างขวา ชื่อ Branch จะแสดงขึ้นมา

    ![2019-07-24_23-34-36](https://user-images.githubusercontent.com/85179/61812485-ca499900-ae6d-11e9-9732-98b9baf20319.png)

6. ตรงจุดนี้ Branch ที่เราสร้างขึ้นมาจะมีอยู่แค่ในเครื่องเราเท่านั้น และยังไม่มีการเชื่อมต่อกับ remote repository ที่เราสร้างไว้
7. กดปุ่ม publish branch เพื่อสร้าง branch ชื่อเดียวกันขึ้นมาใน remote repository ที่เราสร้างไว้

## 2. การใช้งาน Branch ในการ track การเปลี่ยนแปลง

1. เปิดไฟล์ `README.md` แล้วเพิ่มข้อความด้านล่างนี้
    ```markdown
    # My Website 

    สวัสดีครับ ผมชื่อพล นักพัฒนาเว็บไซต์ และออกแบบเว็บไซต์ สนใจติดต่อได้ที่ [เว็บไซต์](https://www.nextflow.in.th)

    ## ช่องทางติดต่อ
    - Youtube
    - Facebook 
    - Email: training@nextflow.in.th
    ```

2.  แก้ไขข้อความในไฟล์ `README.md` โดยการเพิ่ม Link  เข้าไป และบันทึกไฟล์
    
    ```markdown
    # My Website 

    สวัสดีครับ ผมชื่อพล นักพัฒนาเว็บไซต์ และออกแบบเว็บไซต์ สนใจติดต่อได้ที่ [เว็บไซต์](https://www.nextflow.in.th)

    ## ช่องทางติดต่อ
    - [Youtube](https://www.youtube.com/teerasej)
    - [Facebook](https://www.facebook.com/teerasej) 
    - Email: [training@nextflow.in.th](mailto:training@nextflow.in.th)
    ```

3. ทำการใช้ Source control activity ในการดู change และทำการ commit ด้วย ข้อความ
    ```
    Add link to README.md
    ```
