# เว็บไซต์เซอร์ไพรส์แฟน

## ฟีเจอร์
- หน้าแรกมีปุ่มอวยพรวันเกิด พร้อมเอฟเฟคหัวใจ
- มีปุ่ม "ไปหน้าถัดไป" กดแล้วจะไปยังหน้า `next.html`
- สามารถเพิ่มเนื้อหาในหน้าถัดไปได้ตามต้องการ

## วิธีใช้งาน
1. เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์
2. กดปุ่ม "ไปหน้าถัดไป" เพื่อไปยังหน้า `next.html`
3. หากต้องการแก้ไขข้อความหรือรูปภาพ สามารถแก้ไขในไฟล์แต่ละหน้าได้เลย

## การใช้งานบน Github Pages
- นำไฟล์ทั้งหมด (index.html, next.html, style.css, script.js) อัพโหลดขึ้น GitHub repository
- เปิดใช้งาน Github Pages ที่ Settings > Pages
- ใช้ลิงก์ที่ Github Pages สร้างขึ้นเพื่อแชร์ให้แฟนดูออนไลน์

## โค้ดตัวอย่างปุ่มลิงก์ไปหน้าถัดไป

```html
<button id="nextBtn">ไปหน้าถัดไป</button>
<script>
  document.getElementById('nextBtn').onclick = function() {
    window.location.href = 'next.html';
  }
</script>
```