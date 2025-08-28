# Python Live Book

An interactive Python learning resource built with Quarto, WebAssembly, and Pyodide that enables code execution directly in the browser without requiring any local Python installation.

🌐 **Live Site:** [pybook.chaancegraves.com/latest](https://pybook.chaancegraves.com/latest)

📓 **Jupyter Notebook Version:** [Available here](#) <!-- Add your Jupyter notebook link -->

## 📚 Course Content

This interactive book covers essential Python programming concepts across 10 comprehensive modules:

1. **Introduction** - Getting started with Python basics
2. **Control Statements and Program Development** - Conditional logic and loops
3. **Functions** - Creating reusable code blocks
4. **Lists and Tuples** - Working with ordered collections
5. **Dictionaries and Sets** - Key-value pairs and unique collections
6. **Strings** - Text manipulation and processing
7. **NumPy Arrays** - Numerical computing fundamentals
8. **Files and Exceptions** - Data persistence and error handling
9. **Introduction to Object-Oriented Programming** - Classes and objects
10. **Special Topics**
    - Working with real-time data (APIs)
    - AI/ML overview
    - Gradio demo applications

## ✨ Features

- **Browser-based execution:** Run Python code directly in your web browser
- **Interactive learning:** Execute code examples and exercises without setup
- **Modern web technologies:** Built with Quarto, WebAssembly, and Pyodide
- **Pre-installed packages:** Includes pandas, matplotlib, and numpy
- **Responsive design:** Works on desktop and mobile devices
- **Dark/light themes:** Choose your preferred reading experience

## 🚀 Development Setup

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) (latest version)

### Installation Steps

1. **Install Quarto**
   ```bash
   # Visit https://quarto.org/docs/get-started/ for installation instructions
   # Or use your package manager, e.g.:
   # Linux/WSL: sudo apt-get install quarto
   # macOS: brew install quarto
   # Windows: Download from official site
   ```

2. **Clone and setup the project**
   ```bash
   git clone <your-repo-url>
   cd python-live-book
   ```

3. **Install the Quarto Live extension**
   ```bash
   quarto add r-wasm/quarto-live
   ```

4. **Preview the book locally**
   ```bash
   quarto preview
   ```
   The book will be available at `http://localhost:3456`

5. **Build for production**
   ```bash
   quarto render
   ```

## 📖 Usage

1. Navigate to the live site or run locally
2. Click through chapters in order or jump to specific topics
3. Execute code examples by clicking the "Run" button in code blocks
4. Experiment with the code by modifying examples
5. Complete exercises to reinforce learning

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.


---

*Happy coding! 🐍✨*
