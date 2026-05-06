# Hello SKKU App 🎓

A simple web app built with Streamlit.

## Overview

This project is a beginner-friendly web application that displays a welcome message using [Streamlit](https://streamlit.io), a Python framework for building interactive web apps with minimal code.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required dependencies:
   ```bash
   pip install streamlit
   ```

### Running the App

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

## Project Structure

```
your-repo-name/
└── app.py        # Main application file
```

## Code Overview

```python
import streamlit as st
st.title("Hello, SKKU! 🎓")
st.write("My first web app")
```

| Line | Description |
|------|-------------|
| `import streamlit as st` | Imports the Streamlit library and aliases it as `st` |
| `st.title(...)` | Renders a large heading at the top of the page |
| `st.write(...)` | Displays a text message below the title |

## Built With

- [Streamlit](https://streamlit.io) — Python library for building web apps

## License

This project is open source and available under the [MIT License](LICENSE).
