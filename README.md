# Guardrail_Demo_DSD

This repository demonstrates the integration of [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) with a basic Python application. It showcases how to implement conversational AI guardrails to ensure safe and controlled interactions.

## 🧰 Project Structure


- **`guardrail_config/`**: Contains configuration files for NeMo Guardrails.
  - **`config.yml`**: Defines the guardrail settings.
  - **`main.colang`**: Specifies conversational flows and constraints using Colang.
- **`main.py`**: The main Python script to run the application.
- **`requirements.txt`**: Lists the Python dependencies.
- **`test_queries.txt`**: Contains sample queries to test the guardrails.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- An OpenAI API key

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/IqraSiddiqui/Guardrail_Demo_DSD.git
   cd Guardrail_Demo_DSD
2. **Create a virtual environment (optional but recommended):**
  ```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
  ```
3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set your OpenAI API key:**
  ```bash
export OPENAI_API_KEY='your-api-key-here'  # On Windows: set OPENAI_API_KEY=your-api-key-here
  ```
### Running the Application
  ```bash
python main.py
```
