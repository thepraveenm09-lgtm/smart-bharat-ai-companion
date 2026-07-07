# Smart Bharat – AI-Powered Civic Companion

Smart Bharat is a state-of-the-art civic portal designed for Indian citizens to access government services, report public utilities issues, check welfare scheme eligibilities, and interact with an AI-driven chat companion.

This application is built with a decoupled architecture containing a fast React frontend and a Python Flask backend.

---

## Repository Structure

```text
smart-bharat-ai-companion/
├── frontend/             # React + TypeScript + Vite UI
└── backend/              # Python Flask backend & Gemini integrations
```

---

## Getting Started

### 1. Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install the Node packages:
   ```bash
   npm install
   ```
3. Run the Vite development server:
   ```bash
   npm run dev
   ```
4. Access the web app at `http://localhost:5173`.

### 2. Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Create and activate a Python virtual environment:
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Copy the `.env.example` file to `.env` and fill in your Google Gemini API Key:
   ```bash
   cp .env.example .env
   ```
5. Start the Flask application:
   ```bash
   python app.py
   ```
6. The backend runs on `http://127.0.0.1:5000`.

---

## Features Implemented (Phase 1)
- **Modern Responsive Landing Page**: Dynamic theme accents reflecting the Indian flag with glassmorphic designs.
- **Top Navbar**: Includes branding, quick language selector, and citizen profile dashboard links.
- **Hero Banner**: Empowering headings, animated analytics counters, and central search box.
- **Interactive Feature Cards**:
  - **AI Assistant**: A civic helper widget.
  - **Government Services**: Quick links for standard public services.
  - **Report Public Issue**: Citizens can file mock complaints.
  - **My Complaints**: Track resolved and pending issues.
  - **Scheme Recommender**: Search centrally and state-level welfare programs.
- **Footer**: Citizen portal helpline details and prototype disclaimer notes.
