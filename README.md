<div align="center">
  <h1>🤖 Agent Framework</h1>
  <p><b>Advanced, Modular & Framework-Agnostic AI System Prompts.</b></p>
  <p><i>Hệ thống Prompt chuyên gia, đa module dành cho các AI IDE.</i></p>
  
  ![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
  ![AI Agents](https://img.shields.io/badge/AI_Agents-FF6F00?style=for-the-badge&logo=openai&logoColor=white)
  ![Antigravity](https://img.shields.io/badge/Antigravity_2.0-8A2BE2?style=for-the-badge&logo=abstract&logoColor=white)

  [English](#english) • [Tiếng Việt](#tiếng-việt)
</div>

---

<h2 id="english">🇬🇧 English</h2>

A highly optimized, progressive-disclosure prompt architecture designed to turn generic AI coding assistants into a team of elite, specialized developers. By utilizing dynamic routing, it completely eliminates context rot and "AI-generated" code smells.

### 🧰 Agent Modules
| Specialist | Target Domain | Description |
| :--- | :--- | :--- |
| **Master Router** (`agents.md`) | System Core | Routes tasks, enforces the `[PLAN]` loop, and overrides output language to Vietnamese. |
| **Frontend Architect** | Web UI | Framework-agnostic (React, Vue, HTMX). Enforces hardware-accelerated animations and headless UI. |
| **UI/UX Director** | Design Systems | Synthesizes aesthetic archetypes (Apple, Stripe, Neo-Brutalism) and generates Design Tokens. |
| **Backend Engineer** | Server/API | Focuses on zero-trust security, strict API contracts, and database query optimization. |
| **Mobile Architect** | iOS/Android | Enforces 120fps performance, offline-first data sync (React Native, Flutter, Swift). |
| **DevOps & Infra** | CI/CD & Cloud | Handles Dockerization, GitHub Actions, and zero-downtime deployments. |
| **Script & Tooling** | Automation | Writes robust, idempotent, production-grade CLI tools (Python, Go, Bash). |

### ✨ Core Features
* **Progressive Disclosure:** Uses a root `agents.md` router to dynamically load only the necessary `.agents/*.md` specialist files, saving instruction budget and preventing AI confusion.
* **Framework-Agnostic:** Does not lock the AI into specific tech stacks. Agents dynamically adapt to React 19, Svelte 5, Go, or Rust based on user requests.
* **Anti-Robotic UI:** Enforces modern design principles (fluid typography, glassmorphism, compound components) to prevent generic, cheap-looking AI outputs.
* **The `[PLAN]` Loop:** Forces the AI to generate a concise execution plan and await human approval before writing a single line of code, mitigating hallucination risks.

### 🚀 Setup & Integration

#### 1. General AI IDEs (Cursor, Windsurf, Copilot)
1. Clone this repository.
2. Copy `agents.md` and the `.agents/` folder into the **root directory** of your target project.
3. Reload your IDE window to clear the AI's context cache.

#### 2. Antigravity IDE Integration
1. Place the files into your workspace root.
2. Ensure dotfiles are visible: Go to Antigravity Settings -> Search for `Exclude` -> Ensure `.agents` is **not** ignored by the file explorer or AI context indexer.
3. Open the Command Palette (`Ctrl/Cmd + Shift + P`), type **`Antigravity: Reload Window`** and execute.
4. Open a *new* AI Chat/Composer session. The Master Router is now active.

#### 3. Antigravity 2.0 (v2.4.3+) Advanced Setup
For Antigravity 2.0 running globally or as a local daemon, you can set this framework as your default system-wide persona:
1. Navigate to your global Antigravity config directory (usually `~/.antigravity/` or `%APPDATA%\antigravity\`).
2. Symlink or copy the `agents.md` and `.agents/` folder into this configuration directory.
3. If using the Antigravity CLI, initialize your project with: `antigravity init --apply-agents-path ~/.antigravity/agents.md`.
4. Restart the Antigravity background daemon to apply the new system prompt rules across all your workspaces.

---

<h2 id="tiếng-việt">🇻🇳 Tiếng Việt</h2>

Kiến trúc prompt phân tầng, tối ưu hóa cao được thiết kế để biến các trợ lý AI thông thường thành một đội ngũ lập trình viên tinh nhuệ. Thông qua cơ chế định tuyến động, hệ thống triệt tiêu hoàn toàn hiện tượng "ngộ độc context" và xóa bỏ "mùi AI" trong code.

### 🧰 Cấu Trúc Chuyên Gia
| Chuyên gia | Lĩnh vực | Ghi chú |
| :--- | :--- | :--- |
| **Master Router** (`agents.md`) | Lõi Hệ Thống | Điều phối luồng công việc, ép buộc vòng lặp `[KẾ HOẠCH]` và chuẩn hóa ngôn ngữ giao tiếp. |
| **Frontend Architect** | Web UI | Đa nền tảng (React, Vue, HTMX). Ép chuẩn animation tăng tốc phần cứng và kiến trúc Headless UI. |
| **UI/UX Director** | Design Systems | Định hình các gu thẩm mỹ (Apple, Stripe, Brutalism) và xuất hệ thống Design Tokens. |
| **Backend Engineer** | Server/API | Đặt bảo mật Zero-trust lên đầu, chuẩn hóa API contract và tối ưu truy vấn Database. |
| **Mobile Architect** | iOS/Android | Ép chuẩn hiệu năng 120fps, đồng bộ dữ liệu Offline-first (React Native, Flutter). |
| **DevOps & Infra** | CI/CD & Cloud | Đóng gói Docker, tự động hóa GitHub Actions và triển khai Zero-downtime. |
| **Script & Tooling** | Automation | Viết script tự động hóa chuẩn Production, xử lý lỗi mượt mà (Python, Go, Bash). |

### ✨ Tính Năng Nổi Bật
* **Khai mở dần dần (Progressive Disclosure):** Dùng `agents.md` ở root để điều hướng AI đọc đúng file chuyên môn trong thư mục `.agents/`, tiết kiệm tối đa Token và tránh làm AI bị "ngáo".
* **Không giới hạn Framework:** Không khóa chết AI vào một công nghệ. Hệ thống tự thích ứng linh hoạt với mọi stack từ React 19, Svelte 5 đến Go, Rust.
* **Chống Giao Diện Robot:** Ép AI áp dụng các tiêu chuẩn thiết kế hiện đại (typography linh hoạt, glassmorphism, compound components) để xóa bỏ các giao diện AI thô kệch, rẻ tiền.
* **Vòng lặp `[KẾ HOẠCH]`:** Bắt buộc AI phải trình bày kế hoạch ngắn gọn và chờ con người phê duyệt trước khi xuất code, triệt tiêu rủi ro code phá hỏng hệ thống.

### 🚀 Hướng Dẫn Cài Đặt & Tích Hợp

#### 1. Dành cho AI IDE phổ thông (Cursor, Windsurf)
1. Clone mã nguồn repository này về máy.
2. Copy file `agents.md` và thư mục `.agents/` thả vào **thư mục gốc (root)** của dự án.
3. Reload lại cửa sổ IDE để xóa bộ nhớ đệm (cache) của AI.

#### 2. Tích hợp riêng cho Antigravity IDE
1. Dán các file vào thư mục gốc của workspace.
2. Đảm bảo thư mục ẩn không bị chặn: Vào Settings của Antigravity -> Tìm `Exclude` -> Đảm bảo `.agents` **không** nằm trong danh sách bị bỏ qua (ignore) của File Explorer và AI Indexer.
3. Mở Command Palette (`Ctrl/Cmd + Shift + P`), gõ lệnh **`Antigravity: Reload Window`** và Enter.
4. Mở một phiên Chat/Composer *mới hoàn toàn*. Master Router lúc này đã nắm quyền điều khiển.

#### 3. Thiết lập nâng cao cho Antigravity 2.0 (v2.4.3+)
Nếu bạn dùng Antigravity 2.0 chạy ngầm hoặc qua CLI, bạn có thể thiết lập bộ framework này làm System Prompt mặc định cho mọi dự án:
1. Mở thư mục chứa file cấu hình global của Antigravity (thường là `~/.antigravity/` trên Linux/Mac hoặc `%APPDATA%\antigravity\` trên Windows).
2. Tạo Symlink (liên kết mềm) hoặc copy file `agents.md` cùng thư mục `.agents/` vào đây.
3. Nếu dùng CLI, chạy lệnh khởi tạo: `antigravity init --apply-agents-path ~/.antigravity/agents.md`.
4. Khởi động lại daemon/service của Antigravity để áp dụng bộ luật mới lên toàn bộ các workspace hiện có.
