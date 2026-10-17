# Otteri Drawing Tracker

ระบบติดตามเอกสารงานเขียนแบบ · Otteri

เว็บแอปแบบไฟล์เดียว (static HTML) เก็บข้อมูลไว้ในเบราว์เซอร์ (`localStorage`)
ของแต่ละเครื่อง — ไม่มีเซิร์ฟเวอร์ ไม่มีฐานข้อมูลส่วนกลาง

## Deploy

โฮสต์บน **GitHub Pages** — ไฟล์ที่เสิร์ฟคือ `index.html` ที่ root

## หมายเหตุ

- แก้ไขแอปที่ไฟล์ `index.html`
- ข้อมูลงาน (โฟลเดอร์เอกสารลูกค้า) และไฟล์ harness ของ AI ถูกกันออกจาก repo
  ด้วย `.gitignore` (whitelist เฉพาะไฟล์แอป)
