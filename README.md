# Copilot Template

A VSCode project template with pre-configured extensions and resources to quickly bootstrap new development projects with AI-powered tools.

## Repository Structure

```text
copilot-template/
├── README.md                 # This file - project documentation
├── vscode-extentions.txt    # List of recommended VSCode extensions
├── LICENSE                  # Project license
└── .github/                 # Vscode templates
```

## Getting Started

### 1. Clone the Template

Use this repository as a template for your new projects:

```bash
# Option 1: Use GitHub's template feature (recommended)
# Click "Use this template" button on GitHub

# Option 2: Clone directly
git clone https://github.com/fusionet24/copilot-template.git your-new-project
cd your-new-project
rm -rf .git  # Remove template git history
git init     # Initialize new git repository
```

### 2. Install VSCode Extensions

Install all recommended extensions automatically:

```bash
# Windows PowerShell
Get-Content vscode-extentions.txt | ForEach-Object { code --install-extension $_ }

# Windows Command Prompt / Linux / macOS
cat vscode-extentions.txt | xargs -L 1 code --install-extension
```

### 3. Customize for Your Project

1. Update this `README.md` with your project details
2. Modify `vscode-extentions.txt` if you need different extensions
3. Add your project files and structure
4. Update the LICENSE file with your information

## Included Extensions

This template includes extensions for:

- **AI Development**: GitHub Copilot, Azure AI Studio, AI Foundry
- **Python Development**: Python, Pylance, Jupyter notebooks
- **Azure Integration**: Azure tools and functions
- **Data & Analytics**: Databricks, SQL tools
- **Code Quality**: Markdown linting, YAML support

## Usage Tips

- Use GitHub Copilot Chat for code assistance and explanations
- Leverage Azure tools for cloud development and deployment
- Utilize Jupyter notebooks for data analysis and prototyping
- Take advantage of integrated debugging and testing tools

See the github [https://docs.github.com/en/copilot/tutorials/copilot-chat-cookbook](copilot cookbook) for more ideas 