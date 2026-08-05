# Git Cheat Sheet - ResearchLab

---

# 🚀 Bắt đầu buổi làm việc

```bash
git pull
```

Đồng bộ phiên bản mới nhất từ GitHub về máy đang làm việc.

---

# 💾 Kết thúc buổi làm việc

```bash
git add .
git commit -m "feat: mô tả thay đổi"
git push
```

Ví dụ:

```bash
git commit -m "feat: add NSGA-II"
```

```bash
git commit -m "fix: correct MOPSO velocity update"
```

```bash
git commit -m "docs: update README"
```

---

# 🔍 Kiểm tra trạng thái

```bash
git status
```

Xem các file đã thay đổi, đã theo dõi hay chưa.

---

# 🌐 Kiểm tra kết nối GitHub

```bash
git remote -v
```

Hiển thị địa chỉ Repository trên GitHub.

---

# 📜 Xem lịch sử Commit

```bash
git log --oneline
```

Hiển thị danh sách các commit gần nhất.

---

# 📂 Kiểm tra thư mục hiện tại

```bash
pwd
```

Hiển thị thư mục đang làm việc.

---

# 📁 Liệt kê file trong thư mục

```bash
ls
```

Hiển thị các file và thư mục hiện có.

---

# 📥 Lấy cập nhật từ GitHub

```bash
git pull
```

Luôn thực hiện trước khi bắt đầu làm việc trên máy khác.

---

# 📤 Đẩy thay đổi lên GitHub

```bash
git add .
git commit -m "feat: mô tả thay đổi"
git push
```

---

# 🔄 Quy trình làm việc chuẩn

## Làm trên PC

```text
git pull
      ↓
Viết code
      ↓
git add .
      ↓
git commit -m "feat: ..."
      ↓
git push
```

---

## Chuyển sang Laptop

```text
git pull
      ↓
Viết code
      ↓
git add .
      ↓
git commit -m "feat: ..."
      ↓
git push
```

---

## Quay lại PC

```text
git pull
```

---

# ⚠️ Quy tắc quan trọng

✅ Luôn bắt đầu bằng:

```bash
git pull
```

---

✅ Luôn kết thúc bằng:

```bash
git add .
git commit -m "feat: ..."
git push
```

---

❌ Không sửa cùng một file trên cả PC và Laptop trước khi đồng bộ.

---

# 📝 Quy ước Commit

| Tiền tố | Ý nghĩa |
|---------|----------|
| feat | Thêm tính năng mới |
| fix | Sửa lỗi |
| docs | Cập nhật tài liệu |
| refactor | Cải tiến mã nguồn |
| test | Kiểm thử |

Ví dụ:

```bash
git commit -m "feat: add NSGA-II"
```

```bash
git commit -m "fix: correct MOPSO"
```

```bash
git commit -m "docs: update README"
```

---

# 🎯 95% thời gian chỉ dùng 4 lệnh

```bash
git pull

git add .

git commit -m "feat: ..."

git push
```

---

**ResearchLab v1.0**