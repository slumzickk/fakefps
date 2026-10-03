# SLUMZICK FAKEFPS

**โปรแกรมจำลองการแสดงผลค่า FPS สำหรับ Windows**

---

## ภาพรวมโปรเจกต์

**SLUMZICK FAKEFPS** เป็นซอฟต์แวร์ที่พัฒนาขึ้นสำหรับจำลองการแสดงผลค่าอัตราเฟรม (FPS) บนหน้าจอ โดยผู้ใช้งานสามารถกำหนดช่วงค่าต่ำสุด–สูงสุดได้ด้วยตนเอง รองรับค่าการแสดงผลสูงสุดถึง **5,000 FPS**

โปรแกรมนี้ถูกออกแบบมาเพื่อวัตถุประสงค์ด้าน **การสาธิต การบันทึกวิดีโอ การแชร์หน้าจอ และการสร้างคอนเทนต์** ที่ต้องการควบคุมค่าตัวเลข FPS ที่ปรากฏบนหน้าจอ

> **หมายเหตุ:** ค่าที่แสดงโดยโปรแกรมเป็น **ค่าจำลอง** ไม่ใช่ค่า FPS จริงที่เกมหรือแอปพลิเคชันกำลังเรนเดอร์

---

## คุณสมบัติหลัก (Features)

- รองรับการกำหนดค่า **Min FPS** และ **Max FPS** ตามต้องการ
- รองรับค่าการแสดงผลสูงสุดถึง **5,000 FPS**
- ระบบ **Auto Re-apply** สำหรับนำค่าที่กำหนดกลับมาใช้โดยอัตโนมัติ
- ระบบควบคุมครบวงจร: **Connect / Apply / Stop / Disconnect**
- ระบบตรวจสอบสิทธิ์ด้วย **License Key**
- อินเทอร์เฟซสไตล์ **Dark / Purple**
- รองรับการใช้งานร่วมกับ **การแชร์หน้าจอและการบันทึกวิดีโอ**
- พัฒนาและออกแบบสำหรับระบบปฏิบัติการ **Windows**

---

## ค่า FPS สูงสุดที่รองรับ

| รายการ | ค่า |
|---|---|
| ค่าสูงสุดที่กำหนดได้ | **5,000 FPS** |

**ตัวอย่างการตั้งค่า:**

```text
Min FPS : 240
Max FPS : 5000
```

---

## License Key

สำหรับเวอร์ชันปัจจุบัน:

```text
Key: slumzick
```

ขั้นตอน: กรอก License Key ในหน้า **Login** แล้วเลือก **Continue**

---

## คู่มือการใช้งาน (Usage)

### 1. เปิดโปรแกรม (Launch)
เปิดโปรแกรม **SLUMZICK FAKEFPS** ขึ้นมา

### 2. ตรวจสอบสิทธิ์ (Authentication)
กรอก License Key:

```text
slumzick
```

จากนั้นเลือก **Continue**

### 3. กำหนดค่า FPS (Configure FPS)
ตั้งค่าตัวแปร:
- **Min FPS** — ค่า FPS ต่ำสุด
- **Max FPS** — ค่า FPS สูงสุด (ไม่เกิน 5,000)

### 4. เปิดใช้งาน Auto Re-apply
เปิดฟังก์ชัน **Auto Re-apply** หากต้องการให้โปรแกรมนำค่าที่กำหนดกลับมาใช้อัตโนมัติ

### 5. เริ่มใช้งาน (Apply)
เลือก **Connect** จากนั้นกด **Apply** เพื่อเริ่มใช้ค่าที่กำหนด

### 6. หยุดการทำงาน (Stop)
เลือก **Stop** เมื่อต้องการหยุดการทำงานของโปรแกรม

---

## ส่วนติดต่อผู้ใช้งาน (Interface)

### หน้า Login
ระบบตรวจสอบ License Key ก่อนเข้าใช้งานโปรแกรม

### หน้าหลัก (Main Interface)

| Control | Description |
|---|---|
| **Min FPS** | กำหนดค่า FPS ต่ำสุด |
| **Max FPS** | กำหนดค่า FPS สูงสุด |
| **Auto Re-apply** | ใช้ค่าที่กำหนดซ้ำโดยอัตโนมัติ |
| **Connect** | เริ่มการเชื่อมต่อ |
| **Apply** | ใช้ค่าที่กำหนด |
| **Stop** | หยุดการทำงาน |
| **Disconnect** | ยกเลิกการเชื่อมต่อ |

---

## ตัวอย่างหน้าจอโปรแกรม (Preview)

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1550781099938938912/1553404054355443712/image.png?ex=6ac1b183&is=6ac06003&hm=a8586ef40115cdc7671844d1bea5f821ff82b280a3d737efd509ac1a79de53d1" width="800">
</p>
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1550781099938938912/1553404054862827632/image.png?ex=6ac1b183&is=6ac06003&hm=316be4b2385a0788b58eda8274fa722b24ccd808ff703fc76f097f355c666407" width="800">
</p>

---

## วิดีโอสาธิต (Demo)

ไฟล์วิดีโอสาธิตอยู่ภายใน Repository:

```text
assets/slumzick.mp4
```

สามารถเปิดดูได้จากโฟลเดอร์ `assets`

---

## โครงสร้างโปรเจกต์ (Project Structure)

```text
SLUMZICK-FAKEFPS/
│
├── README.md
│
└── assets/
    └── slumzick.mp4
```

---

## ความต้องการของระบบ (System Requirements)

| Requirement | Specification |
|---|---|
| ระบบปฏิบัติการ | Windows |
| สถาปัตยกรรม | x64 |
| ค่าการแสดงผลสูงสุด | 5,000 FPS |
| License | จำเป็นต้องมี |

---

## ข้อจำกัดความรับผิดชอบ (Disclaimer)

**SLUMZICK FAKEFPS** เป็นเครื่องมือสำหรับ **จำลอง** ค่าการแสดงผล FPS เท่านั้น

- โปรแกรมนี้ **ไม่ได้** เพิ่มประสิทธิภาพการประมวลผลของ CPU หรือ GPU
- **ไม่ได้** เพิ่มค่า FPS จริงของเกม
- **ไม่ได้** เปลี่ยนแปลงค่า Refresh Rate ของจอภาพ

ค่าที่แสดงผลโดยโปรแกรมเป็น **ค่าจำลอง** และไม่ควรนำไปใช้อ้างอิงเป็นผลการทดสอบประสิทธิภาพหรือ Benchmark ในเชิงจริง

ผู้พัฒนา **ขอสงวนสิทธิ์ไม่รับผิดชอบ** ต่อการนำซอฟต์แวร์ไปใช้งานนอกเหนือจากวัตถุประสงค์ที่ระบุไว้ข้างต้น

---

## ช่องทางการติดต่อ (Community)

| แพลตฟอร์ม | ลิงก์ |
|---|---|
| **Discord** | https://discord.gg/sfN7NZHEud |
| **YouTube** | SLUMZICK |
| **Facebook** | https://www.facebook.com/share/1bcFUyWGz6/?mibextid=wwXIfr |

---

## ข้อมูลโปรเจกต์ (Project Information)

| รายการ | รายละเอียด |
|---|---|
| **Project** | SLUMZICK FAKEFPS |
| **Developer** | SLUMZICK |
| **Platform** | Windows |
| **Maximum Display Value** | 5,000 FPS |
| **License Key** | `slumzick` |

---

<p align="center">
  <strong>SLUMZICK FAKEFPS</strong><br>
  FPS Display Simulation Tool for Windows
</p>
