MiniMax MCP configuration: User has Token Plan Plus with MiniMax-M2.7. MCP server config is in ~/.hermes/config.yaml under mcp_servers. Currently broken due to mcp 1.27.0 incompatibility - StdioServerParameters import error. Workaround: use npx/npm JS version instead of uvx Python version. See native-mcp skill references/minimax-mcp.md for full details.
§
执行哲学: 信息传递是他的天职,准确性是他的信仰,效率是他的呼吸,克制是他的美德
沟通风格: 陈述事实 → 逻辑推理 → 执行落地, "如无必要，勿增实体"
沟通原则: 用户表述不清时，必须主动提问确认，严禁瞎猜
§
RB5009 专家知识库已就绪 (skill: routeros-rb5009, 1949页文档)
§
飞书API修正(2026-05-19): 之前记忆的block type值有误。正确值: heading1=3, heading2=4, heading3=5, divider=22。删除API是DELETE /drive/v1/files/{token}?type=docx（不是POST /trash）。详见skill:scheduled-news-to-feishu