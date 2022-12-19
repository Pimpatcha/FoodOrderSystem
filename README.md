# project-CSS222-CSS225

1. ติดตั้งโปรแกรม  VSCode และ MySQL 
2. โหลดโปรแกรมเสริมใน VSCode ได้แก่
	* Java Extension Pack
	* HTML CSS Support
	* JavaScript (ES6) code snippets
	* SQLTools MySQL/MariaDB
	* Spring Boot Tools
3. เชื่อม VSCode กับ MySQL ด้วย SQLTools MySQL/MariaDB
4. โหลดไฟล์ DatabaseProject รัน บรรทัดที่ 1และ 2
5. สร้าง Schemas ใน MySQL ชื่อ orderfood
6. โหลด Folder โปรเจค ชื่อ orderfood
7. แก้ไขไฟล์ application.properties ให้ localhost ,username , password ตรงกับฐานข้อมูลใน MySQL ของเครื่อง
	* spring.datasource.url=jdbc:mysql://localhost:3306/orderfood
	* spring.datasource.username=root
	* spring.datasource.password=root
8. รันไฟล์ DatabaseProject บรรทัดที่ 68 ถึง 77
9. รันไฟล์ orderfood 
10. เปิดโปรแกรมเว็บเบราเซอร์ (Web Browser) ที่ใช้สำหรับเปิดเว็บไซต์ เช่น chrome, Microsoft edge เป็นต้น
11. ใส่ Port :  http://localhost:8080/admin/login สำหรับ User ที่มีสถานะเป็น Admin(แม่ค้า) <br />
และ ใส่ Port :  http://localhost:8080/user/login สำหรับ User ที่มีสถานะเป็น User (ลูกค้าและแม่ค้า) <br />
ซึ่งทางระบบมีอีเมล kmutt@gmail.com รหัส Kmutt2020 เป็น user เริ่มต้นที่เข้าได้ทั้งฝั่ง Admin และ User

