# ALMA PhD Trial Task: Collaborative LLM Prototype

This repository contains the source code for **Part 1** of the ALMA PhD trial task. It implements a "Collaborative Partner" application designed to shift Human-LLM interaction from passive consumption to active collaborative learning.

The prototype utilizes the **Google Gemini API** to demonstrate pedagogical behaviors such as constructive friction, reflective questioning, and role adaptation (Novice vs. Professional).

## 📂 Project Structure
#### 📄 Part 1:
* `elheyba.ipynb`: The main Jupyter Notebook containing the application prototype, system architecture, and design rationale.
#### 📄 Part 2: The Reflection Report
* `report.pdf`: The accompanying theoretical report.
    * **Content:** Defines the learning scenario (High-Level Software Architecture), analyzes the "Oracle Trap," and provides the pedagogical justification for the design choices (e.g., why the AI refuses to answer "lazy" prompts).

> **Note:** Detailed explanations of the system architecture and the educational design choices are embedded directly within the notebook's Markdown cells.

## 🛠️ Requirements

* **Python:** 3.10 or higher
* **API Key:** A valid Google Gemini API Key (Free Tier supported)

### Dependencies
* `google-generativeai` (Official Google Gemini Python Client)
* `ipykernel` (If running inside a Jupyter environment)

## 🚀 Setup & Usage

1.  **Clone the repository:**
    

2.  **Install the dependencies:**
    ```bash
    pip install google-generativeai
    ```

3.  **Run the Notebook:**
    Open `elheyba.ipynb` in Jupyter Lab, Jupyter Notebook, or VS Code.

4.  **Configure Authentication:**
    The first cell of the notebook will prompt you to enter your Google API Key. Follow the instructions inside the notebook to obtain one if you haven't already.

## 📜 License
Submitted as part of the ALMA Project PhD recruitment process.
