# SAP Integration Suite Copilot

An expert AI agent for **SAP BTP Integration Suite**, for GitHub Copilot in VS Code, Copilot CLI and the Copilot app.

**Created by Rameshkumar Varanganti** · [agenticintegrationhub.com](https://agenticintegrationhub.com/)

[![Install agent in VS Code](https://img.shields.io/badge/VS_Code-Install_Agent-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-agent%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Frameshvaranganti%2Fsap-integration-suite-copilot%2Fmain%2F.github%2Fagents%2Fsap-integration-suite-copilot.agent.md)
[![Install agent in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install_Agent-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode-insiders%3Achat-agent%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Frameshvaranganti%2Fsap-integration-suite-copilot%2Fmain%2F.github%2Fagents%2Fsap-integration-suite-copilot.agent.md)
[![Install plugin in VS Code](https://img.shields.io/badge/VS_Code-Install_Plugin-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3A%2F%2Fchat-plugin%2Finstall%3Fsource%3Drameshvaranganti%252Fsap-integration-suite-copilot%26plugin%3Dsap-integration-suite-copilot)

## What it helps with

- **Cloud Integration (CPI):** iFlow design, routers, splitters, aggregators, exception subprocesses, JMS and data store patterns, externalized parameters
- **Adapters:** HTTP, SOAP, OData, IDoc, RFC, SFTP, AS2, Mail, JMS, AMQP, Kafka, SuccessFactors, Ariba, ProcessDirect
- **Development:** Groovy scripts, XSLT, message mapping, value mapping
- **Security:** OAuth 2.0, certificates, PGP, principal propagation, Cloud Connector
- **API Management, Event Mesh, Integration Advisor, Trading Partner Management, Edge Integration Cell**
- **AI and agentic integration:** MCP servers over SAP APIs, Generative AI Hub, API-to-AI

## Install

### Option 1: One click (VS Code)
Click **Install Agent** above. VS Code opens and asks you to confirm.

### Option 2: Plugin (VS Code, Copilot CLI, Copilot app)
In VS Code, click **Install Plugin** above, or add this marketplace:
`Chat: Open Customizations` → **Plugins** → **Browse** → **Configure Marketplaces** → **Add Marketplace** → `rameshvaranganti/sap-integration-suite-copilot`

Copilot CLI:
```bash
copilot plugin marketplace add rameshvaranganti/sap-integration-suite-copilot
copilot plugin install sap-integration-suite-copilot@agentic-integration-hub
```

### Option 3: Manual
Copy [`.github/agents/sap-integration-suite-copilot.agent.md`](.github/agents/sap-integration-suite-copilot.agent.md) into:
- your project's `.github/agents/` folder (shared with everyone on the repo, also used by Copilot cloud agent on GitHub.com), or
- `~/.copilot/agents/` (Windows: `%USERPROFILE%\.copilot\agents\`) for all your projects.

## Use
Open Copilot Chat, choose **SAP Integration Suite Copilot** in the agent picker, and try:

- *Design an async IDoc → CPI → SuccessFactors flow with retries, a dead-letter queue and alerting.*
- *Review this Groovy script for performance and error handling.* (paste your script)
- *Explain this MPL error and give me the checks:* `java.net.SocketTimeoutException` on the OData receiver.

## Disclaimer
Community project, not affiliated with or endorsed by SAP SE or GitHub. SAP, SAP BTP and SAP Integration Suite are trademarks of SAP SE. Generated designs and code are static analysis until tested on your tenant.

## License
MIT © Rameshkumar Varanganti · [agenticintegrationhub.com](https://agenticintegrationhub.com/)
