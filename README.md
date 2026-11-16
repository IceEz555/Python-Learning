# Python Learning

เอกสารประกอบการสอน Python พื้นฐาน และพื้นที่ส่งการบ้านผ่าน GitHub

## เนื้อหาในคอร์ส

| โฟลเดอร์ | หัวข้อ |
|---|---|
| `00 Course Overview` | Cheat sheet |
| `01 Python Basics` | Introduction, Jupyter Notebook |
| `02 Data Types and Variables` | ชนิดข้อมูลและตัวแปร |
| `03 Data Structures` | List, Tuple, Dictionary, Set |
| `04 Control Flow` | if-else, while, for |
| `05 Functions` | Functions |
| `06 Advanced Topics` | List comprehension, String, File I/O |
| `07 Data Science` | NumPy, SciPy, Pandas |
| `08 Git and GitHub` | สไลด์สอน Git/GitHub และการส่งงาน |

สไลด์ Git/GitHub: เปิด `08 Git and GitHub/Doc/Git_GitHub_Slides.html` ในเบราว์เซอร์ (กดลูกศรซ้าย/ขวาเพื่อเปลี่ยนหน้า)

## วิธีส่งการบ้าน (สรุป)

1. **Fork** repo นี้เป็นของตัวเอง (ทำครั้งเดียว)
2. **Clone** fork ของตัวเองลงเครื่อง
   ```bash
   git clone https://github.com/<ชื่อเรา>/Python-Learning.git
   ```
3. วางงานใน `submissions/<รหัส>-<ชื่อ>/` เช่น `submissions/6612345-somchai/hw01-hello.ipynb`
4. บันทึกและส่งขึ้น GitHub
   ```bash
   git add submissions/6612345-somchai/
   git commit -m "hw01: hello world"
   git push
   ```
5. เปิด **Pull Request** มาที่ repo นี้ ตั้งชื่อ `[hw01] 6612345 สมชาย`

รายละเอียดเพิ่มเติมดูที่ [`submissions/README.md`](submissions/README.md)

## ข้อตกลง

- แก้ไขไฟล์ได้เฉพาะในโฟลเดอร์ของตัวเองใน `submissions/` เท่านั้น
- รัน notebook ให้ครบทุก cell และ save ก่อน commit
- เปิด Pull Request ครั้งเดียว แล้ว push งานชิ้นต่อไปเพิ่มเข้าไปได้เลย
