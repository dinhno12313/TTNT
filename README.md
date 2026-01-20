# TTNT — DeepSpell (Keras)

Một bản triển khai/thử nghiệm **DeepSpell** (sửa lỗi chính tả bằng Deep Learning) phục vụ mục đích học tập/môn **TTNT (Trí tuệ nhân tạo)**.

> Dự án này **dựa trên mã nguồn của MajorTal/DeepSpell**.  [oai_citation:1‡GitHub](https://github.com/dinhno12313/TTNT)

---

## Giới thiệu nhanh

**DeepSpell** là một hướng tiếp cận dùng mô hình deep learning để:
- học cách “sửa” chuỗi ký tự bị sai (misspelling/typo)
- sinh ra chuỗi ký tự đúng hơn theo ngữ cảnh dữ liệu huấn luyện

Repo gốc: **MajorTal/DeepSpell** (kèm bài viết giới thiệu).  [oai_citation:2‡GitHub](https://github.com/MajorTal/DeepSpell)

---

## Nội dung trong repo

- `keras_spell.py`: script chính (Keras/TensorFlow) để huấn luyện/chạy thử mô hình.
- `README.md`: tài liệu dự án.

(Repo hiện khá tối giản, đúng mục tiêu “study/experiment”.)  [oai_citation:3‡GitHub](https://github.com/dinhno12313/TTNT)

---

## Cài đặt

### Yêu cầu
- Python 3.x
- pip / virtualenv (khuyến nghị)

### Tạo môi trường & cài dependencies (gợi ý)
```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
pip install --upgrade pip

# Gợi ý các thư viện thường dùng cho script Keras
pip install tensorflow numpy

# DeepSpell

See (https://github.com/MajorTal/DeepSpell)


Additional details:

The project is based on source code from developer MajorTal
