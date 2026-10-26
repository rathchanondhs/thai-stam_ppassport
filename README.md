# พาสปอร์ตเที่ยวไทย 77 จังหวัด

เช็กลิสต์เที่ยวไทยสไตล์พาสปอร์ตวินเทจ แต่ละคนสมัครบัญชีด้วยอีเมล แล้วเก็บเล่มของตัวเองบนคลาวด์

- `public/index.html` หน้าเว็บทั้งหมด
- `src/worker.js` ระบบสมาชิกและการบันทึกข้อมูล (Cloudflare Worker)
- `wrangler.jsonc` ตั้งค่า Cloudflare (ฐานข้อมูล D1 สร้างให้อัตโนมัติตอน deploy ครั้งแรก)

Deploy: เชื่อม repo นี้กับ Cloudflare Workers (Import a repository) ทุกครั้งที่อัปเดตไฟล์บน GitHub เว็บจะอัปเดตเอง
