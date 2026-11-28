ngrok

```
.\.local\bin\ngrok.exe http 8000 --config .local/ngrok.yml --traffic-policy-file .local/ngrok-policy.json
```

server
```
$env:EMAIL_MCP_DATA = "sqlite-mock"
.\.venv\Scripts\mcp.exe run <filepath>:mcp --transport streamable-http

```