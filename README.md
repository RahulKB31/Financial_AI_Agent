# Multiagent Models and Phidata Playground

## Overview
This repository demonstrates the implementation of multiagent models using the Phi library. It includes:

1. **Web Search Agent**: An agent that searches the web for information and provides sources.
2. **Finance AI Agent**: An agent that gathers financial data, including stock prices, analyst recommendations, stock fundamentals, and company news.
3. **Multi-AI Agent**: A composite agent combining the capabilities of the Web Search Agent and Finance AI Agent to perform tasks collaboratively.
4. **Phidata Playground**: A web-based platform to interact with these agents.

## Features
- Integration with **Groq LLM (Llama-3.1-70b-versatile)** for robust AI capabilities.
- Tooling support for web search using **DuckDuckGo**.
- Financial analysis using **YFinanceTools**.
- Interactive playground for multiagent collaboration.
- Instructions-based response customization (e.g., use of markdown, inclusion of sources).
- Live reloading for seamless development.

---

## Prerequisites
Ensure the following dependencies are installed:

- Python 3.8+
- `phi`
- `dotenv`
- Any other library dependencies as specified in the project.

### Environment Variables
Create a `.env` file and include the following keys:

```
GROQ_API_KEY=<your_groq_api_key>
PHI_API_KEY=<your_phi_api_key>
```

---

## Setup and Usage

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Playground
1. Run the `playground.py` file:
   ```bash
   python playground.py
   ```
   This will launch the interactive playground app.

2. Access the app at `http://localhost:8000` in your browser.

### Using Multi-AI Agent
To test the Multi-AI Agent, use the `main.py` file:

```bash
python main.py
```

The Multi-AI Agent will fetch financial data and summarize analyst recommendations while including sources.

---

## File Descriptions

### `playground.py`
This script defines and serves the Phidata Playground application. It integrates the Web Search Agent and Finance AI Agent for interactive exploration.

### `main.py`
This script demonstrates the use of the Multi-AI Agent by executing a sample task, such as summarizing analyst recommendations and fetching news for a specific stock ticker.

---

## Example Screenshot

Below is a sample screenshot of the playground app:

![Playground Screenshot](https://github.com/RahulKB31/Financial_AI_Agent/blob/main/phidata_playground.jpg "Phidata Playground in action")


---

## Acknowledgments
- [Phi Library Documentation](https://phi.docs.url)
- [Groq LLM Documentation](https://groq.docs.url)
- [YFinanceTools Documentation](https://yfinance.tools.docs.url)
- [DuckDuckGo API](https://duckduckgo.com/api)

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contributions
Contributions are welcome! Please open an issue or submit a pull request to propose improvements or report bugs.

---

## Contact
For further inquiries, please contact:

- **Author**: Rahul K B

---

