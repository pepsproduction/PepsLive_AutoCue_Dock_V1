# PepsLive AutoCue Dock V1

OBS Custom Browser Dock สำหรับควบคุม Source Timer และ Auto Scene Jump

## เปิดใช้งานบน GitHub Pages

ไฟล์หลักคือ:

```text
index.html
```

เมื่ออัพไฟล์ชุดนี้ขึ้น repo แล้ว ลิงก์หน้าโปรแกรมจะเป็น:

```text
https://pepsproduction.github.io/PepsLive_AutoCue_Dock_V1/
```

หรือเปิดตรงไฟล์สำรองได้ที่:

```text
https://pepsproduction.github.io/PepsLive_AutoCue_Dock_V1/PepsLive_AutoCue_Dock_V1.html
```

## ฟีเจอร์หลัก

- ตั้งเวลาเปิด Source แต่ละตัวแยกกันได้
- ตั้งเวลาปิด Source แต่ละตัวแยกกันได้
- กด `+ Add Source` เพิ่มแถว Source ได้เอง
- ย้ายออกจาก Target Scene แล้ว Source ในรายการปิดตัวเอง
- Auto Scene Jump: กดไป Scene ที่ตั้งไว้ แล้วกลับ Target Scene อัตโนมัติ
- Auto Scene Jump ทำงานซ้ำได้ตลอด จนกว่าจะเอาติ๊ก `เปิดใช้งาน` ออก
- ธีม Orange / Black ให้เข้ากับ PepsLive Dock V1

## วิธีเพิ่มเข้า OBS

ไปที่:

```text
Docks > Custom Browser Docks
```

ตั้งค่า:

```text
Dock Name:
PepsLive AutoCue Dock

URL:
https://pepsproduction.github.io/PepsLive_AutoCue_Dock_V1/
```

## ตั้งค่า OBS WebSocket

ใน OBS ไปที่:

```text
Tools > WebSocket Server Settings
```

แนะนำ:

```text
Enable WebSocket Server = ON
Server Port = 4455
Enable Authentication = OFF
```

ถ้าเปิด Authentication ไว้ ให้ใส่ Password ใน Popup Settings ของ Dock
