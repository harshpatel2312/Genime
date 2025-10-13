# Genime

**Genime** is an AI-powered image generation platform built with a modular structure — separating the **[Genime-Frontend](https://github.com/harshpatel2312/Genime-Frontend)** (user interface) and **[Genime-Backend](https://github.com/harshpatel2312/Genime-Backend)** (model inference server).

This main repository links both components as Git submodules for simplified management and deployment.

---

## 🗂️ Repository Structure
```yaml
Genime/
├── Genime-Frontend/ 
├── Genime-Backend/
└── .gitmodules
```

---

## 🧩 Submodules Overview

| Component | Description |
|------------|--------------|
| **[Genime-Frontend](https://github.com/harshpatel2312/Genime-Frontend)** | Handles the user interface, prompt input, and image display. |  
| **[Genime-Backend](https://github.com/harshpatel2312/Genime-Backend)** | Manages image generation, AI model execution, and API endpoints. |  

> 🔍 *For detailed setup and configuration, please refer to each repo’s README.*

---

## ⚙️ Setup Instructions

### Clone with Submodules
To clone the entire project with both submodules:
```bash
git clone --recurse-submodules git@github.com:your-username/Genime.git
```
If you already cloned it:
```bash
git submodule update --init --recursive
```
To pull the latest changes from both submodules:
```bash
git submodule update --remote
```

---

## 🚀 Running the Project
Each submodule runs independently:
- **Backend**: → follow instructions in [Genime-Backend](https://github.com/harshpatel2312/Genime-Backend) README
- **Frontend**: → follow instructions in [Genime-Frontend](https://github.com/harshpatel2312/Genime-Frontend) README

---

## 📜 License

This project is licensed under the Apache 2.0 License.  
© 2025 Genime — AI Imagined Differently 🚀
