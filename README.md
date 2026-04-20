# 📄 README — Video Transcription with Whisper (GPU Supported)

## 📌 Overview
Notebook này sử dụng **OpenAI Whisper** để:
- Trích xuất audio từ video
- Chuyển giọng nói → văn bản (speech-to-text)
- Trả về:
  - Text theo từng câu
  - Timestamp (start–end)
  - Confidence (độ tin cậy ước lượng)

Hỗ trợ:
- ✅ GPU (CUDA) → chạy nhanh hơn
- ✅ CPU fallback nếu không có GPU

---

## ⚙️ Requirements (Cài đặt trước khi chạy)

### 1. Python
- Python **3.8 – 3.11** (khuyến nghị)

---

### 2. Cài thư viện

```bash
pip install openai-whisper moviepy torch
