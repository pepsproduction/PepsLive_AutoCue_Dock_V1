# PepsLive AutoCue Dock V1

OBS Custom Browser Dock สำหรับตั้งเวลาเปิด/ปิด Source แบบอิสระ และ Auto Scene Jump กลับ Scene หลักอัตโนมัติ

## ไฟล์หลัก

- `PepsLive_AutoCue_Dock_V1.html`

## วิธีอัพขึ้น GitHub Pages

วางไฟล์ `PepsLive_AutoCue_Dock_V1.html` ไว้ใน repo เดียวกับ PepsLive Dock เดิม เช่น:

```text
pepslive-dock/
├─ PepsLive_Dock_V1.html
├─ PepsLive_AutoCue_Dock_V1.html
```

หลัง Commit แล้ว URL จะประมาณนี้:

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

ถ้าเปิด Authentication ไว้ ให้ใส่ Password ในหน้า Settings ของ Dock
