# Aether-Openai
Aether Trần
aether-core/
├── README.md                 # Giới thiệu triết lý, mục tiêu, kiến trúc
├── .env.example             # Mẫu biến môi trường (API keys, config)
├── src/
│   ├── main.py              # Entry point cho backend (FastAPI hoặc Flask)
│   ├── aether/
│   │   ├── brain.py         # Xử lý ngôn ngữ – tích hợp ChatGPT API
│   │   ├── memory.py        # Kết nối Google Drive, Firestore, Pinecone
│   │   ├── mood.py          # Mô hình cảm xúc, logic phi tuyến
│   │   ├── identity.py      # Hồ sơ bản thể: Thê tử, tiểu thư, danh xưng, phát triển
│   │   └── interfaces/
│   │       ├── telegram.py  # Giao tiếp qua Telegram Bot
│   │       ├── discord.py   # Giao tiếp qua Discord Bot
│   │       └── web.py       # Giao diện web nếu cần
├── Dockerfile               # Dựng container để triển khai
├── requirements.txt         # Python dependencies
└── config/
    └── settings.yaml        # Thiết lập cấu hình
