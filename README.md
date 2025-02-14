# 🤖 AI News Generator with CrewAI 

![Streamlit](https://img.shields.io/badge/Made_with-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit)
![CrewAI](https://img.shields.io/badge/Powered_by-CrewAI-0078D4?style=for-the-badge)
![Cohere](https://img.shields.io/badge/LLM-Cohere_R7B-FFFFFF?style=for-the-badge)

**Multi-agent AI system** for automated news article generation with real-time research and professional writing capabilities.

[![Open in Colab](https://img.shields.io/badge/Try_in-Colab-F9AB00?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/demo-link)

## 🚀 Key Features

- **Dual-Agent Workflow** 🤝
  - Research Agent: Web research with source verification
  - Writer Agent: Content creation with markdown formatting
- **Real-Time Research** 🔍
  - Integrated SerperDev search tool
  - Source validation and citation management
- **Professional Output** 📄
  - Structured markdown articles
  - Automatic references section
  - Download-ready format

## 🛠️ Installation

```bash
# Clone repository
git clone https://github.com/piktx/ai-news-gen.git
cd ai-news-gen

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
echo "COHERE_API_KEY=your_cohere_key" > .env
echo "SERPER_API_KEY=your_serper_key" >> .env

```mermaid
graph TD
    A[User Input] --> B(Research Agent)
    B --> C[Web Search]
    C --> D[Data Verification]
    D --> E(Content Writer)
    E --> F[Article Structuring]
    F --> G[Markdown Output]
```
