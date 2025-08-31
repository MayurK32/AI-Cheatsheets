# 🚀 AI Developer Cheatsheets

<div align="center">
  <img src="https://img.shields.io/badge/Learn-Build-Deploy-gradient?style=for-the-badge&color=667eea&labelColor=764ba2" alt="Learn Build Deploy">
  <img src="https://img.shields.io/badge/AI%20Powered-FastAPI-Groq-gradient?style=for-the-badge&color=10b981&labelColor=059669" alt="AI Stack">
  <img src="https://img.shields.io/badge/Beginner-Friendly-100%25-gradient?style=for-the-badge&color=f59e0b&labelColor=d97706" alt="Beginner Friendly">
</div>

<div align="center">
  <h2>🎯 From Zero to AI Hero - One Cheatsheet at a Time</h2>
  <p><b>Comprehensive, visual, and hands-on guides for developers learning AI integration</b></p>
  <p>Created by <a href="https://www.linkedin.com/in/mayur-kolekar-ai/">Mayur Kolekar</a> | Senior Developer - Applied AI</p>
</div>

---

## 🤔 Why This Repository?

### The Problem
Many developers want to integrate AI into their applications but face these challenges:
- **Information Overload**: Too many resources, not knowing where to start
- **Complex Documentation**: Official docs assume prior knowledge
- **Lack of Practical Examples**: Theory without hands-on practice
- **Fragmented Learning**: Pieces of knowledge scattered across different sources
- **Setup Frustration**: Environment issues before even writing code

### The Solution
This repository provides:
- **📚 Step-by-Step Learning Path**: Start from absolute basics, build up gradually
- **🎨 Visual Learning**: Color-coded sections, diagrams, and clear formatting
- **💻 Instant Practice**: Run code directly in Jupyter notebooks
- **🎯 Project-Based**: Build real, working applications
- **🔧 Troubleshooting Built-in**: Common errors and solutions included
- **✅ Success Checkpoints**: Know exactly when you've completed each step

---

## 🖥️ Complete Setup Guide for Beginners

### Step 1: Install Python

#### Windows
1. Visit https://www.python.org/downloads/
2. Download the latest Python (3.8 or higher)
3. Run the installer
4. **IMPORTANT**: Check "Add Python to PATH" during installation
5. Click "Install Now"
6. Verify installation:
   ```cmd
   python --version
   ```

#### macOS
1. Install using Homebrew (recommended):
   ```bash
   # Install Homebrew first if you don't have it
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   
   # Install Python
   brew install python3
   ```
2. Or download from https://www.python.org/downloads/
3. Verify installation:
   ```bash
   python3 --version
   ```

#### Linux (Ubuntu/Debian)
```bash
# Update package list
sudo apt update

# Install Python and pip
sudo apt install python3 python3-pip

# Verify installation
python3 --version
```

### Step 2: Understanding pip (Python Package Manager)

**What is pip?**
- pip is Python's package manager
- It installs libraries/packages that extend Python's capabilities
- Comes pre-installed with Python 3.4+

**Check if pip is installed:**
```bash
# Windows
pip --version

# macOS/Linux
pip3 --version
```

**If pip is not installed:**
```bash
# Windows
python -m ensurepip --upgrade

# macOS/Linux
python3 -m ensurepip --upgrade
```

**Basic pip commands:**
```bash
# Install a package
pip install package_name

# Upgrade a package
pip install --upgrade package_name

# List installed packages
pip list

# Uninstall a package
pip uninstall package_name
```

### Step 3: Install Jupyter Notebook

#### What is Jupyter Notebook?
- Interactive coding environment
- Combines code, text, and visualizations
- Perfect for learning and experimentation
- Runs in your web browser

#### Installation
```bash
# Windows
pip install notebook

# macOS/Linux
pip3 install notebook

# Or install JupyterLab (recommended - modern interface)
pip install jupyterlab
```

### Step 4: Create a Virtual Environment (Recommended)

**Why use virtual environments?**
- Isolates project dependencies
- Prevents package conflicts
- Makes projects reproducible

**Create and activate virtual environment:**

#### Windows
```cmd
# Create virtual environment
python -m venv myenv

# Activate it
myenv\Scripts\activate

# You'll see (myenv) in your terminal prompt
```

#### macOS/Linux
```bash
# Create virtual environment
python3 -m venv myenv

# Activate it
source myenv/bin/activate

# You'll see (myenv) in your terminal prompt
```

**Deactivate when done:**
```bash
deactivate
```

---

## 📓 How to Use Jupyter Notebooks

### Starting Jupyter

#### Method 1: Classic Notebook
```bash
# Navigate to your project folder
cd ai-developer-cheatsheets

# Start Jupyter
jupyter notebook

# Your browser will open automatically
# If not, copy the URL from terminal (usually http://localhost:8888)
```

#### Method 2: JupyterLab (Recommended)
```bash
# Navigate to your project folder
cd ai-developer-cheatsheets

# Start JupyterLab
jupyter lab

# Your browser will open with a modern interface
```

### Jupyter Interface Guide

#### Opening a Notebook
1. Click on the `.ipynb` file in the file browser
2. The notebook opens in a new tab

#### Understanding Cell Types
- **Code Cells**: Contains Python code (has `[ ]` on the left)
- **Markdown Cells**: Contains text, instructions, explanations

#### Running Cells
1. Click on a cell to select it
2. Press `Shift + Enter` to run and move to next cell
3. Or press `Ctrl + Enter` to run and stay in same cell
4. Or click the "Run" button in toolbar

#### Essential Keyboard Shortcuts
- `Shift + Enter`: Run cell, move to next
- `Ctrl + Enter`: Run cell, stay in place
- `Alt + Enter`: Run cell, insert new cell below
- `Esc`: Command mode (blue border)
- `Enter`: Edit mode (green border)
- `A`: Insert cell above (in command mode)
- `B`: Insert cell below (in command mode)
- `DD`: Delete cell (in command mode)
- `M`: Convert to Markdown (in command mode)
- `Y`: Convert to Code (in command mode)
- `Z`: Undo
- `Shift + Z`: Redo

#### Saving Your Work
- Auto-saves every 120 seconds
- Manual save: `Ctrl + S` (Windows/Linux) or `Cmd + S` (Mac)
- Create checkpoint: File → Save and Checkpoint

#### Restarting the Kernel
If something goes wrong:
1. Kernel → Restart
2. Run all cells again from the beginning

---

## 📘 Cheatsheet 1.0: FastAPI + Groq AI

### Overview
**Build Your First AI-Powered API in 30 Minutes!**

This beginner-friendly notebook teaches you how to create a fully functional REST API that uses artificial intelligence.

### What You'll Build
- 💬 Chat endpoint that talks intelligently with users
- 🌍 Translation service for any language
- 🎨 Creative content generator (stories, poems)
- 📊 Automatic API documentation

### Prerequisites
- Python 3.8+ installed (follow guide above)
- Internet connection
- Free Groq account (instructions in notebook)

### Learning Path

#### Step 1: Environment Setup (5 min)
- System check
- Package installation
- Verification

#### Step 2: Get AI API Key (5 min)
- Create Groq account
- Get free API key
- Configure authentication

#### Step 3: Build Basic API (5 min)
- Create FastAPI app
- Add endpoints
- Test locally

#### Step 4: Add AI Power (10 min)
- Integrate Groq AI
- Create chat function
- Add translation
- Build content generator

#### Step 5: Test Everything (5 min)
- Test each endpoint
- Debug issues
- Verify responses

#### Step 6: Launch Server (5 min)
- Run API server
- Access documentation
- Make API calls

---

## 🚀 Quick Start Guide

### 1. Clone or Download Repository
```bash
# Clone with git
git clone https://github.com/yourusername/ai-developer-cheatsheets.git

# Or download ZIP from GitHub and extract
```

### 2. Navigate to Repository
```bash
cd ai-developer-cheatsheets
```

### 3. Install Jupyter
```bash
# Windows
pip install jupyterlab

# macOS/Linux
pip3 install jupyterlab
```

### 4. Launch Jupyter
```bash
jupyter lab
```

### 5. Open the Notebook
- Click on `1_0_FastAPI_And_Types_Of_Prompt.ipynb`
- Start with the first cell
- Follow instructions step by step

---

## 🗂️ Repository Structure

```
ai-developer-cheatsheets/
│
├── 📓 1_0_FastAPI_And_Types_Of_Prompt.ipynb  # Main tutorial notebook
├── 📄 README.md                              # This file
└── 📄 requirements.txt                       # Dependencies (auto-generated)
```

---

## 🔧 Troubleshooting

### Common Issues and Solutions

#### Python not found
- **Windows**: Reinstall Python and check "Add to PATH"
- **Mac/Linux**: Use `python3` instead of `python`

#### pip not found
```bash
# Windows
python -m pip install --upgrade pip

# Mac/Linux
python3 -m pip install --upgrade pip
```

#### Jupyter won't start
```bash
# Reinstall Jupyter
pip uninstall jupyter notebook jupyterlab
pip install jupyterlab
```

#### Port already in use
```bash
# Use different port
jupyter lab --port=8889
```

#### Kernel died error
- Restart kernel: Kernel → Restart
- Clear outputs: Edit → Clear All Outputs
- Restart Jupyter

#### Package import errors
```bash
# Install missing package
pip install package_name
```

---

## 💡 Tips for Success

### For Complete Beginners
1. **Take it slow**: No rush, learning takes time
2. **Run every cell**: See what each piece does
3. **Read errors carefully**: They tell you what's wrong
4. **Google is your friend**: Search error messages
5. **Celebrate progress**: Every working cell is a win!

### Best Practices
1. **Always use virtual environments** for projects
2. **Save your work frequently** (Ctrl+S)
3. **Read markdown cells** - they explain the code
4. **Experiment with code** - change values and see what happens
5. **Keep notes** - add your own markdown cells

---

## 📞 Support

- **Creator**: [Mayur Kolekar on LinkedIn](https://www.linkedin.com/in/mayur-kolekar-ai/)
- **Issues**: Check troubleshooting section in notebook
- **Learning**: Each notebook has built-in help sections

---

## 📜 License

MIT License - Free to use for educational purposes. This is a read-only repository.

---

<div align="center">
  <h3>🎯 Ready to Start Your AI Journey?</h3>
  <p><b>Open the notebook and build your first AI API in 30 minutes!</b></p>
  <br>
  <p>Made with ❤️ for the developer community</p>
</div>
