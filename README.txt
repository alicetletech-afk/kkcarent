KK Car Schedule — Final 2 Pages

ไฟล์ใน Google Apps Script:
- Code.gs
- Index.html
- Schedule.html

การทำงาน:
- หน้า /exec = เพิ่มสถานะรถ
- หน้า /exec?page=schedule = ตารางรถรายสัปดาห์
- ใช้เฉพาะชีต Cars และ Availability
- ไม่อ่าน ไม่แก้ และไม่เชื่อมชีต Booking

หัวตาราง Cars:
Car ID | Car Name | Year | Active

ระบบจะสร้าง Availability ให้อัตโนมัติหากยังไม่มี
ถ้ามี Availability แบบเก่า ระบบจะสำรองชีตก่อนแปลง
