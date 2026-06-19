# Bài tập — Khóa hè Python & Machine Learning 2026

Repo **mẫu** để nộp bài tập của khóa học **Python & Machine Learning** — Machine Learning & IoT Lab, HCMUT.

> 📅 Khóa học: 20/6 – 30/8/2026 · 22 buổi · Thứ Bảy & Chủ Nhật

---

## 🚀 Cách sử dụng (dành cho học viên)

**Khuyến nghị:** repo này được đặt là *Template repository*. Hãy bấm nút **"Use this template" → "Create a new repository"** trên GitHub để tạo repo của riêng bạn.

Nếu làm thủ công bằng dòng lệnh:

```bash
# 1. Tải repo mẫu về
git clone https://github.com/mliotlab/Homework-summer-courses-2026.git
cd Homework-summer-courses-2026

# 2. Trỏ về repo CỦA BẠN (đã tạo trống trên GitHub)
git remote set-url origin https://github.com/<ten-cua-ban>/<repo-cua-ban>.git

# 3. Đẩy toàn bộ lên repo cá nhân
git push -u origin main
```

Sau đó, mỗi buổi:

```bash
# làm bài trong thư mục tuần tương ứng, ví dụ week01/
git add week01/
git commit -m "week01: hoan thanh bai tap buoi 1"
git push
```

**Nộp bài:** gửi **link repo cá nhân** của bạn theo hướng dẫn của mentor trên Discord.

---

## 📁 Cấu trúc thư mục

| Thư mục | Tuần | Nội dung |
|---|---|---|
| `week01` | Tuần 1 | Buổi 1 — Đại số tuyến tính · Buổi 2 — Xác suất thống kê |
| `week02` | Tuần 2 | Buổi 3 — Gradient Descent · Buổi 4 — NumPy & Pandas |
| `week03` | Tuần 3 | Buổi 5 — ML & Tiền xử lý · Buổi 6 — Hồi quy tuyến tính |
| `week04` | Tuần 4 | Buổi 7 — Logistic & KNN · Buổi 8 — Tree & Random Forest |
| `week05` | Tuần 5 | Buổi 9 — Clustering · Buổi 10 — Giảm chiều (SVD) |
| `week06` | Tuần 6 | Buổi 11 — SVM · Buổi 12 — Ensemble + **Kiểm tra giữa kỳ** |
| `week07` | Tuần 7 | Buổi 13 — Deep Learning & MLP · Buổi 14 — CNN |
| `week08` | Tuần 8 | Buổi 15 — Attention & Transformer · Buổi 16 — Object Detection |
| `week09` | Tuần 9 | Buổi 17 — LLM & Agent · Buổi 18 — Multimodal |
| `week10` | Tuần 10 | Buổi 19–20 — Final Project |
| `week11` | Tuần 11 | Buổi 21–22 — Final Project |

---

## 📝 Quy ước nộp bài

- Đặt bài làm vào **đúng thư mục tuần** (`weekXX/`).
- Định dạng: notebook `.ipynb` hoặc file `.py`; đặt tên rõ ràng, ví dụ `buoi01_nguyenvana.ipynb`.
- Commit message rõ ràng: `week01: hoan thanh bai tap buoi 1`.
- **Không commit** dữ liệu lớn / file nặng (đã cấu hình trong `.gitignore`).

## ⚙️ Cài đặt môi trường

```bash
pip install -r requirements.txt
```

---

*Machine Learning & IoT Lab — Khoa Điện–Điện tử, Đại học Bách Khoa TP.HCM*
