Developer Tools Research Agent
A powerful AI agent that helps developers research and compare programming tools, frameworks, and technologies. The agent uses web search and content analysis to provide detailed comparisons and recommendations for developer tools.

Features
Smart Tool Discovery: Automatically extracts relevant developer tools from web content
Comprehensive Analysis: Provides detailed information about each tool including:
Pricing models
Open source status
Technology stack
API availability
Language support
Integration capabilities
Developer-Focused Recommendations: Tailored suggestions based on specific development needs
Interactive CLI: Simple command-line interface for easy interaction
Prerequisites
Python 3.8+
OpenAI API key
Firecrawl API key
Installation
Clone the repository:
bash
git clone <repository-url>
cd advanced-agent
Install dependencies:
bash
pip install -r requirements.txt
Set up environment variables:
bash
cp .env.example .env
Then edit .env and add your API keys.
Usage
Run the agent:

bash
python main.py
Example queries:

"Compare React and Vue.js for large-scale applications"
"Best Python web frameworks for 2024"
"Top database solutions for real-time applications"
Project Structure
main.py
 - Entry point for the application
src/
workflow.py
 - Main workflow and state management
firecrawl.py
 - Web scraping and search functionality
models.py
 - Data models and schemas
prompts.py
 - System and user prompts for the LLM
Configuration
The following environment variables are required:

OPENAI_API_KEY: Your OpenAI API key
FIRECRAWL_API_KEY: Your Firecrawl API key for web search
