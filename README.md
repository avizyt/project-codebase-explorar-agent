# Project Codebase Explorer Agent

**Project Codebase Explorer Agent** is an AI-powered tool designed to analyze and interpret codebases, providing insights into their structure, functionality, and interdependencies. Leveraging advanced language models, this agent assists developers in understanding complex projects more efficiently.

## Features

- **Automated Code Analysis**: Scans the entire codebase to identify modules, classes, functions, and their relationships.
- **Natural Language Summaries**: Generates human-readable explanations of code components and their purposes.
- **Dependency Mapping**: Visualizes dependencies between different parts of the codebase.
- **Interactive Queries**: Allows users to ask questions about the codebase and receive contextual answers.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager
- OpenAI API key (for language model access)
- GEMINI API key (for language model access)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/avizyt/project-codebase-explorar-agent.git
   cd project-codebase-explorar-agent
   ```


2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```


3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```


4. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add your OpenAI API key:

   ```env
   OPENAI_API_KEY=your_openai_api_key
   GEMINI_API_KEY=your_gemini_api_key
   ```


## Usage

1. **Prepare the Codebase**

   Place the codebase you wish to analyze inside the `project_test/` directory.

2. **Run the Agent**

   ```bash
   python src/main.py
   ```


   The agent will process the codebase and generate summaries and insights.

## Project Structure


```
project-codebase-explorar-agent/
├── indexes/             # Stores indexing data
├── project_test/        # Directory containing the target codebase
├── src/                 # Source code for the agent
├── tests/               # Test cases for validation
├── .gitignore           # Git ignore file
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add YourFeature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a pull request ([Visualizing a Codebase - GitHub Next](https://githubnext.com/projects/repo-visualization/?utm_source=chatgpt.com), [Github AI Agents - Relevance AI](https://relevanceai.com/agent-templates-software/github?utm_source=chatgpt.com))

## License

MIT