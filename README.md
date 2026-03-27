# GemAnalyzer

**GemAnalyzer** is a web application that uses **AI** to identify gemstones from images, including their type and shape/cut. The system consists of:

- **Frontend:** ReactJS with Tailwind CSS
- **Backend:** FastAPI (Python) serving TensorFlow models
- **ML Models:** TensorFlow/Keras models for gem type and shape classification

Users can upload a gem image, and the app returns predictions with confidence levels.

---

## 📸 Features

- Identify gem types (diamond, ruby, sapphire, etc.)
- Detect gem shapes/cuts
- View prediction confidence
- Mobile and desktop responsive
- Guided instructions for image uploads
- Clean, modern UI with Tailwind CSS
- Optionally provide email for receiving reports

---

## 🖥️ Tech Stack

| Layer       | Technology                     |
|------------|--------------------------------|
| Frontend   | ReactJS, React Router, Tailwind CSS |
| Backend    | Python, FastAPI, TensorFlow, Pillow, NumPy |

---

## 🔧 Installation

### Prerequisites

- Python 3.10+
- Node.js 18+
- npm or yarn
- Git

---

### 1. Clone the Repository

```bash
git clone https://github.com/MassInshaf/FYP_2025-26.git
cd FYP_2025-26
