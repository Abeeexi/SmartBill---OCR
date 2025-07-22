# 🧾 SmartBill OCR

AI-powered OCR for retail invoices using Gemini Vision + LLM, OpenCV, and FastAPI.

## 🚀 Features
- OCR thông tin trên hóa đơn: Tên cửa hàng, ngày, sản phẩm, tổng tiền
- Sử dụng Gemini Vision+LLM với JSON prompt để trích xuất chính xác
- Tích hợp FastAPI để trả kết quả JSON cho CRM/ERP
- Post-processing logic: kiểm tra type, fuzzy matching, phân loại logo bằng CNN

## 🧠 Tech Stack
Python · OpenCV · Gemini SDK · FastAPI · MongoDB · MLflow · Docker · Kubernetes

## 🔧 How to Run
```bash
pip install -r requirements.txt
uvicorn src.api_fastapi:app --reload
