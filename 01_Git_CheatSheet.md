# Git Cheat Sheet - ResearchLab

---

# 1. Bắt đầu buổi làm việc

Luôn đồng bộ phiên bản mới nhất từ GitHub.

```bash
git pull
```

---

# 2. Kết thúc buổi làm việc

Sau khi hoàn thành công việc.

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

# 3. Kiểm tra trạng thái

```bash
git status
```

Hiển thị trạng thái hiện tại của Repository.

---

# 4. Kiểm tra kết nối GitHub

```bash
git remote -v
```

Hiển thị địa chỉ Repository.

---

# 5. Xem lịch sử Commit

```bash
git log --oneline
```

---

# 6. Kiểm tra thư mục hiện tại

```bash
pwd
```

---

# 7. Liệt kê file trong thư mục

```bash
ls
```

---

# 8. Quy trình làm việc chuẩn

## Trên PC

```text
git pull

↓

Làm việc

↓

git add .

↓

git commit -m "feat: ..."

↓

git push
```

## Chuyển sang Laptop

```text
git pull

↓

Làm việc

↓

git add .

↓

git commit -m "feat: ..."

↓

git push
```

## Quay lại PC

```text
git pull
```

---

# 9. Quy tắc

- Luôn bắt đầu bằng:

```bash
git pull
```

- Luôn kết thúc bằng:

```bash
git add .
git commit -m "feat: ..."
git push
```

- Không chỉnh sửa cùng một file trên PC và Laptop trước khi đồng bộ.

---

# 10. Quy ước Commit

| Prefix | Ý nghĩa |
|--------|---------|
| feat | Thêm tính năng |
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

# 11. Bốn lệnh sử dụng hằng ngày

```bash
git pull

git add .

git commit -m "feat: ..."

git push
```

---

# Ghi nhớ

Git chỉ là công cụ đồng bộ.

Mỗi ngày chỉ cần:

1. git pull
2. Làm việc
3. git add .
4. git commit
5. git push

---

ResearchLab v1.0