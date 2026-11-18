# McEnergy × SONY — FCU / AHU Cleaning Report

| ไฟล์ | ใช้ทำอะไร |
|---|---|
| `index.html` | ฟอร์มรายงานล้างเครื่อง 6 หน้า (ช่างสแกน QR แล้วเปิดหน้านี้) |
| `qr.html` | สร้าง/พิมพ์สติกเกอร์ QR ของแต่ละเครื่อง |

## ขึ้น GitHub + Vercel
1. สร้าง repository ใหม่บน GitHub เช่น `mcenergy-sony-fcu-report` (Public หรือ Private ก็ได้)
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (Add file → Upload files → Commit)
3. เข้า vercel.com → Add New → Project → Import repository นี้
   - Framework Preset: **Other** · Build Command: เว้นว่าง · Output Directory: เว้นว่าง → Deploy
4. ได้ลิงก์ เช่น `https://mcenergy-sony-fcu-report.vercel.app`

## ลิงก์ที่ใช้
- ฟอร์มรายงาน: `https://<โปรเจกต์>.vercel.app/?unit=FCU-101&type=FCU&loc=Building%201`
- ทำสติกเกอร์ QR: `https://<โปรเจกต์>.vercel.app/qr.html` (URL ใส่ให้อัตโนมัติ วางรายการจาก Excel แล้วกดพิมพ์)

แก้ไฟล์แล้วอัปโหลดทับบน GitHub → Vercel จะอัปเดตเว็บเองภายในไม่กี่วินาที ลิงก์เดิม QR เดิมใช้ต่อได้
