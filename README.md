![analysis preview](https://github.com/user-attachments/assets/3b2a8dea-366b-40b0-88ca-280bc0530c20)

# 🤖 ChatGPT Conversation Analysis
![Python](https://img.shields.io/badge/python-3.12+-blue.svg)
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

Analysis of **89,000 ChatGPT conversations** to understand interaction patterns and response behaviors.

## 🔍 Overview

This project analyzes ChatGPT conversation data to extract insights about language usage, topic distribution, and user interaction patterns. The analysis includes sentiment evaluation, topic categorization, and prompt technique examination.

## ✨ Analysis Components

- Conversation pattern analysis
- Language usage metrics
- Sentiment evaluation
- Topic classification
- User feedback assessment
- Prompt technique analysis

## 🚀 Quick Start

### View the analysis

To view the analysis, simple open notebook [chatgpt_analysis.ipynb](chatgpt_analysis.ipynb).

### Development Setup

1. Clone the repository:
```bash
git clone https://github.com/Fybex/chatgpt-conversations-analysis.git
```

2. Create a new virtual environment in the root directory:
```bash
python -m venv venv
```

3. Activate the virtual environment:
```bash
source venv/bin/activate
```

4. Environment setup
```bash
cp .env.sample .env
# Set your OpenAI API key to .env
```

## 📊 Dataset

This analysis utilizes [ChatGPT Conversations Dataset](https://www.kaggle.com/datasets/noahpersaud/89k-chatgpt-conversations/data) from Kaggle containing approximately 89,000 conversations.

## 🛠️ Technical Requirements

- Python 3.12+
- OpenAI API key (for specific cells)
- Required packages are listed in [requirements.txt](requirements.txt) and will be installed in one of the first cells of the notebook.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
