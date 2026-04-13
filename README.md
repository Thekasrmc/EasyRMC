# EASYRMC
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Discord](https://img.shields.io/badge/discord-bot-7289DA)
![Utility](https://img.shields.io/badge/Utility-Moderation-red)
<img align="right" src="/assets/EASYRMC.png" width=200 alt="Easyrmc logo">

> [!NOTE]
> บอท Discord สำหรับจัดการเซิร์ฟเวอร์แบบง่ายๆ แต่ครบเครื่อง  
> ใช้งานได้ทันที ไม่ต้องตั้งค่าซับซ้อน
> 
> **แนะนำ‼️** [VEXRMC Bot Security Bot สำหรับ Discord ป้องกัน Raid / Nuke / Spam / Abuse หากต้องการกดที่นี่เลย !!!](https://github.com/Thekasrmc/VEXRMC)


## ⚡ เริ่มต้นใช้งาน (สำคัญ)

1. เชิญบอทเข้าเซิร์ฟเวอร์

https://discord.com/oauth2/authorize?client_id=1488039685468065833&permissions=5633351516519639&integration_type=0&scope=bot+applications.commands

2. เปิดใช้งาน Slash Commands (Quick)
3. ตั้งค่า role แอดมินด้วยคำสั่ง:
```
/config setmodrole role:<ยศ>
```

✅ หลังจากนี้คุณจะสามารถใช้คำสั่งทั้งหมดได้
> < หากหลังจากตั้งค่าเเล้ว ผู้อื่นที่ไม่ได้อยู่ใน role ที่ตั้งค่าจะไม่สามารถใช้ได้ !!
---

## 📌 วิธีใช้งาน

พิมพ์ `/` ใน Discord แล้วเลือกคำสั่งของ EasyRMC


## 🧹 คำสั่งจัดการแชท

- `/clear count:<จำนวน> channel:<ห้อง>`  
ลบข้อความในแชท (รองรับข้อความเก่า)

- `/lock`  
ปิดห้องไม่ให้พิมพ์

- `/unlock`  
เปิดห้องให้พิมพ์ได้

- `/slowmode seconds:<วินาที>`  
ตั้งเวลาหน่วงการพิมพ์
> หากต้องการปิด slowmode ให้ตั้งเวลา เป็น 0 วินาที!!
---

## 👤 คำสั่งข้อมูล

- `/userinfo user:<ผู้ใช้>`  
ดูข้อมูลผู้ใช้

- `/serverinfo`  
ดูข้อมูลเซิร์ฟเวอร์

---

## ⚙️ ตั้งค่าบอท

- `/config view`  
ดูค่าตั้งค่าปัจจุบัน

- `/config setlog channel:<ห้อง>`  
ตั้งห้อง log

- `/config setmodrole role:<ยศ>`  
ตั้ง role แอดมิน

- `/config setslowmode seconds:<วินาที>`  
ตั้งค่า slowmode เริ่มต้น

- `/config reset`  
รีเซ็ตค่าทั้งหมด

---

## 🏷️ จัดการ Role

- `/role add user:<ผู้ใช้> role:<ยศ>`  
เพิ่ม role

- `/role remove user:<ผู้ใช้> role:<ยศ>`  
ลบ role

---

## 💬 คำสั่งทั่วไป

- `/say message:<ข้อความ>`  
ให้บอทพูดแทน

- `/embed title:<หัวข้อ> description:<รายละเอียด> color:<สี>`  
ส่ง Embed

---

## 🔧 อื่นๆ

- `/help`  
ดูคำสั่งทั้งหมด

- `/ping`  
เช็คความเร็วบอท

- `/panel`  
เปิดแผงควบคุม

- `/backup`  
สำรองข้อมูลเซิร์ฟเวอร์

---

## 💡 หมายเหตุ

- ต้องตั้งค่า `/config setmodrole` ก่อนใช้งานคำสั่งหลัก
- ผู้ใช้ต้องมี role ที่กำหนดถึงจะใช้คำสั่งได้

---

## ✨ About

EasyRMC — บอทที่เน้น "ความง่าย" แต่ครบทุกฟีเจอร์ที่จำเป็น
