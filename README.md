# Basic Geo-Spatial Analysis

โปรเจกต์นี้เป็นตัวอย่างการวิเคราะห์ข้อมูลเชิงพื้นที่ด้วย **GeoPandas** และเครื่องมือที่เกี่ยวข้อง พร้อมโน้ตบุ๊กสำหรับการเรียนรู้ทีละบท

## โครงสร้างโปรเจกต์
- [main.py](main.py) — สคริปต์หลัก (หากมีการใช้งาน)
- [pyproject.toml](pyproject.toml) — รายการ dependencies และการตั้งค่าโปรเจกต์
- [notebooks/](notebooks/) — โน้ตบุ๊กบทเรียน
- [data/](data/) — ข้อมูลดิบ/ประมวลผล/ชั่วคราว

## การติดตั้ง
> ต้องใช้ Python >= 3.11

### สร้าง virtual env
```bash 
uv venv --python 3.11

```

### การเปิดใช้งาน Virtual Environment

**บน macOS/Linux:**
```bash
source .venv/bin/activate
```

**บน Windows (Command Prompt):**
```cmd
.venv\Scripts\activate.bat
```

**บน Windows (PowerShell):**
```powershell
.venv\Scripts\Activate.ps1
```

> **หมายเหตุ:** หากใช้ PowerShell อาจต้องเปลี่ยน execution policy ก่อน:
> ```powershell
> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
> ```

### ทำการ ติดตั้ง package หรือ library ที่ใช้
```bash
uv sync
