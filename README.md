# youtube-transcript-rag
YouTube Transcript Extractor &amp; RAG Q&amp;A System

# 🎬 YouTube Transcript RAG System

Sistem Expert System berbasis RAG (Retrieval-Augmented Generation) 
untuk mengekstrak transcript YouTube dan melakukan tanya jawab cerdas.

## Fitur Utama
- 📥 **Fitur 1**: Ambil transcript YouTube → Generate PDF terverifikasi dengan secret key
- 🔐 **Fitur 2**: Upload PDF → Verifikasi otomatis → Tanya jawab berbasis RAG

## Teknologi yang Digunakan
- Google Gemini 2.5 Flash (LLM)
- FAISS (Vector Database)
- Sentence Transformers - all-MiniLM-L6-v2 (Embedding Model)
- Gradio (User Interface)
- LangChain (Text Splitting)
- ReportLab (PDF Generation)

## Cara Menjalankan
1. Buka notebook di Kaggle
2. Tambahkan `GOOGLE_API_KEY` di Kaggle Secrets
3. Run semua cell secara berurutan
4. Akses aplikasi melalui link Gradio yang muncul
