# 🇹🇭 Thailand Tourism Analysis 2025  
### 📊 Interactive Dashboard & Storytelling with DuckDB + Plotly

---

## 📌 Project Overview

โปรเจกต์นี้มีวัตถุประสงค์เพื่อวิเคราะห์ข้อมูล  
**นักท่องเที่ยวชาวต่างชาติที่เดินทางเข้าประเทศไทยในปี 2025**

โดยใช้เครื่องมือ:
- ⚡ **DuckDB** → สำหรับ query ข้อมูลขนาดใหญ่ได้รวดเร็ว  
- 📈 **Plotly Express & Graph Objects** → สำหรับสร้าง interactive visualization  
- 🐍 **Python (Pandas, NumPy)** → สำหรับ data cleaning และ transformation  

👉 เป้าหมายคือการแปลงข้อมูลเชิงตัวเลขให้กลายเป็น  
**Insight เชิงกลยุทธ์ที่สามารถนำไปใช้ได้จริง**

---

## 🎯 Key Questions

โปรเจกต์นี้ตอบ 3 คำถามหลัก:

1. **โครงสร้างตลาดนักท่องเที่ยวของไทยเป็นอย่างไร?**  
2. **นักท่องเที่ยวเดินทางมาไทยช่วงไหน และมี seasonality หรือไม่?**  
3. **ตลาดนักท่องเที่ยวกำลังเปลี่ยนไปในทิศทางใด?**  

---

## 🧠 Key Insights

### 1) Market Structure
- ตลาดมีลักษณะ **กระจุกตัวสูง**
- ประเทศหลัก: **Malaysia และ China**
- ไทยพึ่งพาตลาดเอเชียเป็นหลัก  

👉 *Regional-driven tourism economy*

---

### 2) Seasonality
- **Peak:** ต้นปี (Jan)  
- **Low:** กลางปี (Sep)  
- **Recovery:** ปลายปี  

- แต่ละประเทศมี pattern ต่างกัน  
👉 *Multi-seasonality structure*

---

### 3) Market Shift
- มี **Emerging markets** ที่เติบโตเร็ว  
- ตลาดใหญ่บางประเทศเริ่มชะลอ  
- **India** เริ่มเป็นตลาดเชิงกลยุทธ์  

👉 ตลาดกำลังเปลี่ยนสู่ **diversified portfolio**

---

## 📊 Dashboard Features

### 🎛️ One-Page Executive Dashboard
- Market Size (Top Countries)
- Growth (YoY %)
- Seasonality (Monthly Trend)
- Market Positioning (Bubble Chart)

👉 เหมาะสำหรับ **ผู้บริหาร / การพรีเซนต์**

---

### 🎬 Animated Monthly Leaderboard
- แสดง ranking แบบ dynamic รายเดือน
- เห็นการแข่งขันของตลาดแบบ real-time

👉 เปลี่ยน data เป็น **visual storytelling**

---

## ⚙️ Data Pipeline

### 🔗 Data Source
Dataset ถูก host บน GitHub และโหลดอัตโนมัติ:

```python
url = "https://raw.githubusercontent.com/Sujiwankit/DADS5001-HW1-Plotly-express-/main/International%20Tourist%20Arrivals%20to%20Thailand%20Jan%20-%20Dec%202025.csv"
