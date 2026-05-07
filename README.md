# PepsLive AutoCue Dock V1

OBS Custom Browser Dock สำหรับควบคุม Source Timer และ Auto Scene Jump

## ฟีเจอร์หลัก

- ตั้งเวลาเปิด Source แต่ละตัวแยกกันได้
- ตั้งเวลาปิด Source แต่ละตัวแยกกันได้
- กด `+ Add Source` เพิ่มแถว Source ได้เอง
- ย้ายออกจาก Target Scene แล้ว Source ในรายการปิดตัวเอง
- Auto Scene Jump: กดไป Scene ที่ตั้งไว้ แล้วกลับ Target Scene อัตโนมัติ
- Auto Scene Jump ทำงานซ้ำได้ตลอด จนกว่าจะเอาติ๊ก `เปิดใช้งาน` ออก
- ธีม Orange / Black ให้เข้ากับ PepsLive Dock V1

## ไฟล์หลัก

```text
PepsLive_AutoCue_Dock_V1.html
```

## URL หลังอัพขึ้น GitHub Pages

ถ้า repo คือ:

```text
https://github.com/pepsproduction/pepslive-dock
```

URL จะเป็น:

```text
https://pepsproduction.github.io/pepslive-dock/PepsLive_AutoCue_Dock_V1.html
```

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
https://pepsproduction.github.io/pepslive-dock/PepsLive_AutoCue_Dock_V1.html
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

## วิธีใช้แบบเร็ว

1. เปิด Dock ใน OBS
2. กดรูปเฟือง
3. กด Connect
4. เลือก Target Scene
5. กด Reload
6. กด + Add Source
7. เลือก Source
8. ตั้งเวลาเปิดและเวลาปิด
9. ถ้าใช้ Auto Scene Jump ให้ติ๊ก `เปิดใช้งาน`
10. เลือก Scene Jump และเวลาที่จะให้กลับ Target Scene
