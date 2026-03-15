# Random Name Generator

โปรแกรม JavaScript ขนาดเล็ก สำหรับสุ่มชื่อจาก Array

## สิ่งที่ได้เรียนรู้

* การใช้งาน **Array** ใน JavaScript
* การใช้ **Math.random()** เพื่อสุ่มตัวเลข
* การดึงข้อมูลจาก Array แบบสุ่ม

## ตัวอย่างโค้ด

```javascript
const names = ["John","Mike","Anna"];

const random =
names[Math.floor(Math.random()*names.length)];

console.log("Random Name:", random);
```

## ผลลัพธ์ตัวอย่าง

Random Name: Mike

## จุดประสงค์ของโปรเจกต์

โปรเจกต์นี้ทำขึ้นเพื่อฝึกพื้นฐาน JavaScript เช่น Array และการสุ่มค่า
