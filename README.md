# 👋 Xin chào, tôi là Phạm Phúc Quang (Quang Phạm Phúc)

### 🚀 AI-Driven Software Engineer | Creative Technologist | Full-Stack Developer

- 🎯 **Triết lý phát triển:** Đi đầu trong phương pháp **AI-Driven Development (Vibe Coding)**, điều phối chuyên sâu các AI Agents & Copilots (**Antigravity, Cursor, Claude, ChatGPT**) giúp rút ngắn chu kỳ phát triển sản phẩm **gấp 5 lần** mà vẫn đảm bảo kiến trúc Full-Stack bền vững và đạt chuẩn bảo mật doanh nghiệp (**OWASP ASVS Level 2**).
- 🧠 **Chuyên môn cốt lõi:** Hệ thống AI tương tác thời gian thực (**RAG Chatbot, Digital Human, Face Swap, AI Voice/Music/Video Synthesis**), hệ thống **Multi-Screen WebSockets (<50ms)** cho sự kiện lớn, **Zalo Mini App**, và **Real-time Analytics Dashboard** chịu tải cao.
- 🎓 **Học vấn:** Kỹ sư Công nghệ Thông tin – **Đại học Thủy Lợi (2019 – 2026)** | Đồ án tốt nghiệp: *"Giải pháp ứng dụng Trí tuệ nhân tạo vào lĩnh vực y tế"*.
- 📫 **Liên hệ:** [quangsicmedia@gmail.com](mailto:quangsicmedia@gmail.com) | 📞 `0963 253 930` | 📍 Kim Liên, Đống Đa, Hà Nội

---

## 🛠️ Tech Stack & Công Nghệ Chủ Đạo

| Lĩnh vực | Công nghệ & Công cụ |
| :--- | :--- |
| **AI-Driven Engineering & Vibe Coding** | `Antigravity` • `Cursor` • `Claude` • `ChatGPT` • `System Prompt Engineering` • `Multi-Agent Workflow` |
| **AI / Machine Learning & Media Engine** | `OpenAI GPT-4` • `Google Gemini API` • `RAG Pipeline` • `ElevenLabs TTS (eleven_v3)` • `STT / Viseme Lip Sync` • `InsightFace` • `Stable Diffusion / ControlNet` • `OpenCV` • `MediaPipe` • `PyTorch` • `TensorFlow / Keras` • `FFmpeg Multi-threading` • `Model Quantization` |
| **Frontend & Interactive Web** | `React 18/19` • `Next.js` • `TypeScript` • `Vite` • `Tailwind CSS v4` • `GSAP` • `HTML5 Canvas` • `Zalo Mini App SDK` |
| **Backend, Realtime & Cloud Infra** | `Node.js` • `Express` • `Socket.io` • `WebSockets` • `Redis Task Queue` • `SQLite (29M+ rows)` • `Firebase (Hosting, Firestore, Realtime DB, Storage, Functions)` • `Docker` • `Google Cloud VM` • `Platform.sh` • `Traefik` |
| **Data Analytics, Security & Hardware** | `Custom Tracking SDK` • `Chart.js` • `Recharts` • `OWASP ASVS Level 2` • `HMAC-SHA256 / Argon2id / TOTP 2FA` • `NVIDIA Jetson Nano` • `Workstation GPU` |

---

## 🏆 Tổng Hợp Các Dự Án Thực Chiến Tiêu Biểu (CV & Local Projects)

### 🌟 I. Các Dự Án Trọng Điểm Trong CV (Enterprise & National Campaigns)

#### 1. 🌐 Hệ Thống Web Tương Tác Đa Màn Hình Thời Gian Thực — *Sự kiện Tập đoàn GE Vernova*
- **Bản chất dự án:** Giải pháp tương tác không gian tại sự kiện của tập đoàn đa quốc gia **GE Vernova**, kết nối thời gian thực giữa **Controller Web App** (trên Tablet/Mobile) và **Display Web App** (trên màn hình LED chính).
- **Giải pháp kỹ thuật:** Thiết kế giao thức truyền thông hai chiều bằng `Socket.io` và `WebSockets` qua máy chủ `Node.js` với **độ trễ đồng bộ dưới 50ms**. Kích hoạt hiệu ứng chuyển động mượt mà bằng `GSAP` và `HTML5 Canvas` tức thì trên màn hình LED.
- **Thành tựu:** Hoạt động liên tục 100% thời gian sự kiện không mất kết nối hay trễ nhịp khung hình, nâng tầm trải nghiệm khách mời cấp cao.
- **Repo / Mã nguồn:** `quangzz/ge-vernova-interactive-board` *(Private - Enterprise Client)*

#### 2. 📱 Hệ Thống Zalo Mini App Tạo Lời Chúc Cá Nhân Hóa & Dashboard Tracking — *Abbott Ensure Gold Vietnam*
- **Bản chất dự án:** Chiến dịch truyền thông diện rộng trên nền tảng Zalo cho phép người dùng tạo thiệp chúc mừng và kết xuất video cá nhân hóa tự động bằng AI, đi kèm hệ thống đo lường hiệu quả chiến dịch chi tiết.
- **Giải pháp kỹ thuật:** Tự phát triển thư viện **Tracking SDK** thu thập chi tiết hành vi người dùng (clicks, thời gian dừng, conversion funnel từng bước, tỷ lệ xem hết video) đẩy về API tối ưu hóa tải cao. Xây dựng **Real-time Dashboard** bằng `React` & `Chart.js` giám sát phễu chuyển đổi và hàng đợi render video (`Video Render Queue`).
- **Thành tựu:** Xử lý ổn định **hơn 50,000+ lượt tạo video AI cá nhân hóa**, lưu trữ chính xác 100% dữ liệu hành vi người dùng theo thời gian thực.
- **Repo / Mã nguồn:** `quangzz/ensure-gold-zalo-miniapp` *(Private - Enterprise Client)*

#### 3. 🎬 Web App Đổi Khuôn Mặt Sinh Video Truyền Thông — *Nutifood*
- **Bản chất dự án:** Ứng dụng web cho chiến dịch lan tỏa thương hiệu của Nutifood, nơi người dùng tải ảnh chân dung lên và hệ thống AI tự động ghép mặt vào các nhân vật trong video clip ngắn mẫu.
- **Giải pháp kỹ thuật:** Triển khai hàng đợi tác vụ (**Task Queue**) bằng `Redis` và `Node.js` phân phối tải hiệu quả đến cụm máy chủ xử lý **AI Face Swap**. Tối ưu hóa dung lượng video đầu ra kết hợp CDN và xây dựng Dashboard theo dõi hiệu năng GPU (`GPU utilization`, `queue processing time`) cùng nhân khẩu học người dùng.
- **Repo / Mã nguồn:** `quangzz/nutifood-ai-faceswap` *(Private - Enterprise Client)*

#### 4. 🤖 Hệ Thống Nhân Vật Ảo Tương Tác Trực Tiếp (Digital Human) — *Hội nghị Quốc tế 'AI for Good 2026'*
- **Bản chất dự án:** Giải pháp nhân vật số (**Digital Human**) đại diện cho công nghệ tương tác thế hệ mới kết hợp Photobooth AI tại hội nghị quốc tế *'AI for Good 2026'*.
- **Giải pháp kỹ thuật:** Đồng bộ hóa 3 cấu phần cốt lõi: Module nhận dạng giọng nói tự động (**Speech-to-Text**) lọc tiếng ồn sự kiện; Trí tuệ nhân tạo hội thoại (**LLM GPT-4 API**) xử lý ngữ cảnh sâu; và Module chuyển văn bản thành giọng nói (**Text-to-Speech**) đồng bộ hóa khẩu hình nhân vật ảo theo thời gian thực (**Viseme-based Lip Sync**).
- **Thành tựu:** Tạo ra trải nghiệm hội thoại tự nhiên như người thật với **độ trễ phản hồi tổng thể dưới 2 giây**.
- **Repo / Mã nguồn:** `quangzz/ai-for-good-digital-human` *(Private - Showcase)*

#### 5. 🏛️ Dự Án Đại Sứ Ảo AI Hỏi Đáp Lịch Sử (Hệ thống RAG) — *Triển lãm Quốc gia*
- **Bản chất dự án:** Triển khai AI Chatbot chuyên sâu phục vụ khách tham quan tìm hiểu kiến thức lịch sử tại Triển lãm *'80 năm Hành trình Độc lập - Tự do - Hạnh phúc'*.
- **Giải pháp kỹ thuật:** Xây dựng hệ thống cơ sở tri thức lịch sử chuẩn hóa qua phương pháp **RAG (Retrieval-Augmented Generation)**, kết hợp cơ chế kiểm soát nội dung (**Content Moderation**) đa tầng đảm bảo tính bảo mật và chính xác tuyệt đối 100% trước các chủ đề lịch sử nhạy cảm.
- **Repo / Mã nguồn:** `quangzz/historical-ai-rag-ambassador` *(Private)*

#### 6. 🎵 Hệ Sinh Thái Chiến Dịch AI "Vươn Tầm Từ Di Sản" – Tạp Chí Di Sản & AI Music Game — *Ngân hàng MSB*
- **Bản chất dự án:** Phát triển hệ thống Web tương tác cho chuỗi 2 chiến dịch AI trọng điểm của ngân hàng MSB: *"Lên Bìa Tạp Chí Di Sản Tương Lai"* (tạo ảnh bìa tạp chí cá nhân hóa bằng AI) và *"MSB AI Music Game – Cùng Quang Hùng MasterD Viết Tiếp Di Sản"* (sáng tác lời ca khúc, tổng hợp giọng hát AI và kết xuất MV âm nhạc).
- **Giải pháp kỹ thuật:** Kiến trúc **Multi-SPA** bằng `React`, `TypeScript`, `Vite`, `Tailwind CSS v4` trên `Firebase Hosting` & Global CDN. Pipeline Backend tích hợp LLM sinh lời nhạc, AI Voice/Music synthesis ghép nối giai điệu gốc, bộ lọc kiểm duyệt **Brand Safety** đa tầng và hệ thống tự động kết xuất video lyric, bình chọn (Voting) kèm thu thập dữ liệu tương tác TikTok.
- **Thành tựu:** Phục vụ hơn **10,500+ lượt truy cập**, khởi tạo thành công **2,729 bìa tạp chí AI** và **4,068 bài nhạc/video AI**; thu hút **257 video dự thi trên TikTok** đạt tổng cộng **hơn 3,59 triệu lượt tương tác**.
- **Repo / Mã nguồn:** `quangzz/msb-heritage-magazine` & `quangzz/msb-ai-music-game` *(Private - Enterprise Client)*

#### 7. 🥤 Hệ Thống Tạo Video & Giọng Nói AI Cá Nhân Hóa – "Cùng MILO Cổ Vũ Tới Cùng" — *Nestlé MILO*
- **Bản chất dự án:** Nền tảng Web App tương tác cho chiến dịch của Nestlé Việt Nam, cho phép người dùng tải ảnh chân dung và chọn chủ đề để AI tự động sinh giọng đọc cổ vũ cá nhân hóa, đồng thời ghép mặt chuyển động vào video/karaoke Full HD.
- **Giải pháp kỹ thuật:** Frontend (`React 19`, `TypeScript`) và **Backend Media Engine** (`Node.js Express` tích hợp `Python OpenCV`, `MediaPipe`, `PyTorch`, `FFmpeg` 4 luồng) trên Google Cloud VM & Platform.sh. Tích hợp `ElevenLabs TTS (eleven_v3)`, cổng xác thực OTP Zalo ZNS/Voice Call ký mã `HMAC-SHA256` chống bot bào mòn ngân sách API, cùng bộ lọc Brand Safety kiểm duyệt khuôn mặt và từ ngữ.
- **Thành tựu:** Đạt **100% tiêu chuẩn kiểm định bảo mật doanh nghiệp của Nestlé (OWASP ASVS v4.0.3 Level 2 & OWASP API Security Top 10)**.
- **Repo / Mã nguồn:** `quangzz/nestle-milo-ai-cheer` *(Private - Enterprise Client)*

#### 8. 🌉 Nền Tảng Tương Tác QR Code "Cầu Đi Bộ Nutifood" – Bản Đồ Tọa Độ & Ảnh/Video AI — *Nutifood 2026*
- **Bản chất dự án:** Nền tảng Web tương tác quy mô lớn cho dự án Cầu Đi Bộ của Nutifood, nơi người dùng quét mã QR định danh, xác thực OTP để nhận tọa độ vị trí riêng trên bản đồ mặt cầu, đồng thời tạo ảnh thẻ có tọa độ và video AI cá nhân hóa (*"Sổ Cổ Đông"*).
- **Giải pháp kỹ thuật:** Kiến trúc Backend (`Express`, `TypeScript`, `Docker` trên GCP VM) tối ưu hóa truy vấn cơ sở dữ liệu `SQLite` quy mô **29 triệu bản ghi mã QR (3GB)** với độ trễ **< 200ms**. Xây dựng cơ chế khôi phục hành trình thông minh (**QR Resume Flow**), kiểm duyệt hình ảnh/tên tự động bằng `Gemini AI`, thuật toán ghim tọa độ trực quan trên bản đồ mặt cầu và hệ thống Admin Dashboard bảo mật 2 lớp (`Argon2id` + `TOTP 2FA`).
- **Repo / Mã nguồn:** `quangzz/nutifood-bridge-2026` *(Private - Enterprise Client)*

---

### 💻 II. Các Dự Án Sản Phẩm, SaaS & Nền Tảng Công Nghệ Khác Trên Máy

| STT | Tên Dự Án | Công Nghệ Chính | Mô Tả Chi Tiết | Trạng Thái Repo |
| :-: | :--- | :--- | :--- | :---: |
| **9** | **Personal Interactive Portfolio (`cv_quang`)** | `React 19`, `TypeScript`, `Tailwind v4`, `Firebase` | Trang Web Portfolio cá nhân tương tác dạng Bento Grid, hỗ trợ lọc hồ sơ theo vai trò (AI Engineer / IT System), sơ đồ kiến trúc trực quan và chế độ in PDF tự động. | **Public** (`quangzz/cv-quang-portfolio`) |
| **10** | **AI Đọc Nhanh (`docnhanh`)** | `React`, `TypeScript`, `Node.js`, `Docker`, `Traefik` | Nền tảng ứng dụng AI hỗ trợ đọc nhanh, tóm tắt và phân tích tài liệu thông minh với kiến trúc Reverse Proxy bảo mật qua Traefik. | **Private** (`quangzz/ai-doc-nhanh`) |
| **11** | **Techcombank / TCLIFE AI Photobooth & Dashboard** | `React`, `PHP`, `AI Image Pipeline`, `Analytics` | Hệ thống ứng dụng tương tác tạo ảnh AI theo mẫu trang phục thương hiệu và trang quản trị thống kê số liệu thời gian thực cho chiến dịch Techcombank / TC Life 2026. | **Private** (`quangzz/tclife-techcombank-campaign`) |
| **12** | **Cùng AI – AI Mindset & AI SME Workshop (`cungai`)** | `React`, `TypeScript`, `Tailwind CSS`, `Vite` | Hệ sinh thái các trang Landing Page truyền thông và đăng ký khóa học/workshop chuyển đổi AI cho doanh nghiệp SME (*AI Mindset*, *AI SME*, *Workshop LDP*). | **Public** (`quangzz/cung-ai-workshops`) |
| **13** | **Hệ Thống Tương Tác & Brand Safety BTMH (`btmh`)** | `React`, `Firebase Functions`, `Node.js`, `AI Safety` | Nền tảng tương tác tích hợp hệ thống kiểm duyệt an toàn thương hiệu (Brand Safety) tự động và quản lý phiên xử lý AI theo thời gian thực. | **Private** (`quangzz/btmh-interactive-platform`) |
| **14** | **Nền Tảng AIxB 2026 (`aixb`)** | `Next.js`, `TypeScript`, `Firebase`, `AI Studio` | Ứng dụng web đa ngôn ngữ kết hợp AI Studio phục vụ sự kiện và kết nối cộng đồng công nghệ AIxB 2026. | **Private** (`quangzz/aixb-2026-platform`) |
| **15** | **URAH SME SaaS Platform (`urah-saas`)** | `React`, `TypeScript`, `Firebase Admin SDK` | Hệ thống phần mềm quản trị và tự động hóa quy trình bằng AI dành cho doanh nghiệp vừa và nhỏ (SME). | **Private** (`quangzz/urah-sme-saas`) |
| **16** | **IFAGENT & Proto 21 Event Idea Tool** | `React`, `Firebase Functions`, `LLM Agents` | Bộ công cụ AI Agent tự động sáng tạo ý tưởng sự kiện (Event Idea Book), xây dựng kịch bản tương tác và quản lý vận hành agency. | **Private** (`quangzz/ifagent-event-idea-tool`) |
| **17** | **TriAn Senior Healthcare AI & Edge Quantization** | `Small Language Models`, `Model Quantization`, `Jetson Nano`, `GTX 1050Ti` | Phát triển API hiệu năng cao kết nối mô hình ngôn ngữ nhỏ với hệ thống CRM hỗ trợ người cao tuổi; lượng tử hóa trọng số để chạy mượt trên phần cứng nhúng giới hạn hiệu năng. | **Case Study** |

---

## 📫 Kết Nối Với Tôi

- 📧 **Email:** [quangsicmedia@gmail.com](mailto:quangsicmedia@gmail.com)
- 📱 **Điện thoại / Zalo:** `0963 253 930`
- 💼 **GitHub:** [https://github.com/quangzz](https://github.com/quangzz)
