SOMESTRA HEALTHY COOKBOOK - FLIPBOOK WEBSITE
=============================================

ไฟล์ชุดนี้เป็นเว็บ E-Book แบบ Static ไม่มีลายน้ำของ FlipHTML5 / AnyFlip / Heyzine
และไม่ต้องใช้ฐานข้อมูลหรือระบบหลังบ้าน

ไฟล์หลัก
- index.html          หน้าเว็บ E-Book
- pages/              รูปภาพหน้า 1-31 ที่แปลงจาก PDF

วิธีเปิดทดสอบบนคอม
1) เปิดโฟลเดอร์นี้ด้วยเว็บเซิร์ฟเวอร์ (ไม่แนะนำดับเบิลคลิก index.html เพราะบางเบราว์เซอร์จำกัดฟังก์ชัน)
2) ถ้าใช้ VS Code ให้ใช้ Live Server ได้
3) หรือใช้คำสั่ง: python -m http.server 8000
   แล้วเปิด http://localhost:8000

วิธีขึ้นออนไลน์แบบฟรี (แนะนำ)
A) Cloudflare Pages
- สร้างโปรเจกต์ Pages แล้วอัปโหลดโฟลเดอร์นี้ทั้งโฟลเดอร์
- ระบบจะให้ URL ฟรี เช่น project.pages.dev
- หากมีโดเมน somestra.com สามารถผูก subdomain เช่น ebook.somestra.com ได้

B) GitHub Pages
- สร้าง repository ใหม่
- อัปโหลด index.html และโฟลเดอร์ pages
- Settings > Pages > Deploy from branch
- จะได้ URL ฟรีแบบ username.github.io/repository

หลังได้ URL ออนไลน์แล้ว สามารถนำ URL นั้นไปสร้าง QR Code ได้ทันที

ฟังก์ชันในตัว
- เปิดหน้าปกและอ่านแบบ 2 หน้าเมื่อใช้คอม
- มือถือแสดงทีละหน้า
- ปัดซ้าย/ขวาบนมือถือ
- ปุ่มก่อนหน้า/ถัดไป
- Thumbnail ทุกหน้า
- Zoom
- Fullscreen
- กรอกเลขหน้าเพื่อข้ามไปหน้าใดก็ได้
- Keyboard arrows / PageUp / PageDown

หมายเหตุ
- ชุดไฟล์นี้ไม่มีลายน้ำแพลตฟอร์ม
- ค่าโฮสติ้งสามารถเป็น 0 บาท หากใช้ Free plan ของผู้ให้บริการที่รองรับ Static Site
- ถ้าต้องการ URL เป็นโดเมนของ SOMESTRA จะมีเพียงค่าโดเมนตามผู้ให้บริการโดเมน (ถ้ามีโดเมนอยู่แล้วก็ใช้ subdomain ได้)
