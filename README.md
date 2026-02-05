# Graphing and Plotting Agent

This project is a Jupyter Notebook-based agent that uses Google's Gemini API to generate and execute Python code for creating graphs, plots, and diagrams. 

## Prerequisites

-   Python 3.x
-   A Google Gemini API Key

## Installation

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository_url>
    cd graphing-and-ploting-agent
    ```

2.  **Install dependencies**:
    It is recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up Environment Variables**:
    Create a `.env` file in the root directory and add your Gemini API Key:
    ```env
    GEMINI_API_KEY=your_actual_api_key_here
    ```

## Usage

1.  **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook main.ipynb
    ```

2.  **Run the Cells**:
    -   Execute the initialization cells to load libraries and define functions.
    -   Locate the cell defining `user_prompt` to customize your request.
    -   Run the final cell to generate and display the graph.

## Example

The notebook works by taking a user prompts like:

> "Make a line chart comparing the GDP of India and China from 2010 to 2025."


> "Make chart of the trigectery of the rocket in projectile motion and trigectory in presence of friction."

And generating the corresponding Python code to plot this.
## Project Structure

-   `main.ipynb`: The core notebook containing the logic for the agent.
-   `requirements.txt`: List of Python dependencies.
-   `.env`: (You create this) Stores secrets like your API key.
