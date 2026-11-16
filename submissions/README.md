# ส่งการบ้านที่นี่

## ตั้งชื่อโฟลเดอร์และไฟล์

```
submissions/
└── <รหัสนักเรียน>-<ชื่อภาษาอังกฤษตัวเล็ก>/
    ├── hw00-hello.ipynb
    ├── hw01-variables.ipynb
    └── ...
```

- ชื่อโฟลเดอร์: `6612345-somchai` (ไม่มีเว้นวรรค ไม่ใช้ภาษาไทย)
- ชื่อไฟล์: `hwXX-หัวข้อ.ipynb` เช่น `hw03-list.ipynb`

## ขั้นตอน

```bash
# ก่อนเริ่มทำงานทุกครั้ง: ดึงของใหม่
git pull

# หลังทำงานและ save แล้ว
git status
git add submissions/6612345-somchai/
git commit -m "hw03: ทำข้อ 1-5"
git push
```

จากนั้นเข้า fork ของตัวเองบน GitHub แล้วเปิด Pull Request (ถ้ายังไม่เคยเปิด)

## ดึงบทเรียนใหม่จากครู

กด **Sync fork → Update branch** ในหน้า fork บน GitHub แล้วรัน `git pull` ในเครื่อง

หรือใช้ Terminal:

```bash
git remote add upstream https://github.com/<ชื่อครู>/Python-Learning.git   # ครั้งแรกครั้งเดียว
git pull upstream main
git push
```

## ปัญหาที่พบบ่อย

| อาการ | วิธีแก้ |
|---|---|
| `nothing to commit` | ยังไม่ได้ save notebook หรือไฟล์อยู่นอกโฟลเดอร์ repo |
| `Please tell me who you are` | `git config --global user.name "..."` และ `git config --global user.email "..."` |
| `403` / `Permission denied` | clone repo ของครูมาแทน fork ให้ clone fork ของตัวเอง |
| `rejected (fetch first)` | `git pull` ก่อน แล้วค่อย `git push` |
| `CONFLICT` | เปิดไฟล์ที่ชน เลือกเวอร์ชันที่ถูก แล้ว `git add` + `git commit` |
