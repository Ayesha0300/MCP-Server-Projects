# 🧠 MCP Wiki Reader

A simple MCP tool for extracting and converting Wikipedia article content to Markdown using a FastMCP server. Built with `uv` for fast and modern Python package management.

## 🚀 Features

- Fetch a Wikipedia article via URL
- Parse its main content using BeautifulSoup
- Convert HTML content to Markdown
- Robust error handling with custom MCP error types

## 📂 Project Structure

src/ └── mcp_wiki/ └── server.py # MCP tool implementation for Wikipedia article reading

markdown
Copy
Edit

## 🛠 Requirements

- Python 3.10+
- `uv` for managing dependencies
- MCP framework (FastMCP, McpError, etc.)

Install dependencies:

```bash
uv pip install -r requirements.txt
You can also use uv venv and uv pip for full environment isolation.

▶️ Running the Server
To start the MCP server, run:

bash
Copy
Edit
mcp dev src/mcp_wiki/server.py
This will launch the FastMCP server on:

🔗 http://127.0.0.1:6274

Registered as the wiki tool, the server exposes the following method:

python
Copy
Edit
read_wikipedia_article("https://en.wikipedia.org/wiki/Python_(programming_language)")
📦 Package Info
This project uses uv – a super fast Python package manager:

Speedy installation and resolution

Native support for pyproject.toml

Great for modern Python workflows

📝 License
MIT License

yaml
Copy
Edit

---

Let me know if you'd like this saved as a file (`README.md`) or if you want to auto-generate the `requirements.txt` based on your code.







