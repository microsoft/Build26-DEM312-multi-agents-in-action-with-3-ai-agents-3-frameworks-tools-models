<a name="start-building"></a>
<br>
<p align="center">
<img src="img/banner-build-26.png" alt="Microsoft Build 2026" width="1200"/>
</p>

# [Microsoft Build 2026](https://build.microsoft.com)

## 🔥 DEM312: Multi-Agents in Action with 3 AI Agents, 3 Frameworks, Tools, and Models

### Demo Description

Build and run a polyglot multi-agent workflow on Azure Container Apps using isolated execution, model inference, and end-to-end observability. In this demo, you will see how a researcher agent, content creator agent, and podcaster agent collaborate through A2A-based patterns while comparing frameworks, tools, and model choices for each stage.

### 🚀 Getting started

If you're following these steps at your own pace:
- Open the implementation repository: [azure-container-apps-multi-agent-workflow](https://github.com/Azure-Samples/azure-container-apps-multi-agent-workflow)
- Choose your setup path for the researcher, content creator, and podcaster workflow
- Run `azd up` to deploy the multi-agent workflow to Azure Container Apps

### 🧠 Learning Outcomes

By the end of DEM312, you will be able to:

- Design a multi-agent workflow where three specialized agents collaborate to research, generate content, and produce podcast-ready outputs.
- Deploy and run agent services on Azure Container Apps with secure isolation for dynamic code execution.
- Compare framework, tool, and model choices for each agent stage while monitoring behavior with Application Insights.

### 💬 Keep Learning with Copilot

Try these prompts with GitHub Copilot to explore the topics from this demo. Open Copilot Chat in Visual Studio Code (`Ctrl+Alt+I` on Windows/Linux, `Cmd+Shift+I` on Mac), paste a prompt, and see what you learn. Try connecting the [Microsoft Learn MCP Server](#-microsoft-learn-mcp-server) for the latest official documentation.

1. Understand the DEM312 architecture:

```text
Explain the DEM312 architecture with three AI agents, and compare how three framework/tool/model combinations can be used across the workflow on Azure Container Apps.
```

2. Explore official docs with the Microsoft Learn MCP Server:

```text
Using the Microsoft Learn MCP Server, find the latest documentation for Azure Container Apps dynamic sessions, Microsoft Foundry, and Azure OpenAI in Azure AI Foundry Models, then summarize how they map to DEM312.
```

3. Build something from DEM312:

```text
Help me create a minimal orchestrator service for DEM312 that calls a research agent, a content agent, and a narration agent, and then containerize it for Azure Container Apps.
```

### 💻 Technologies Used

1. [Azure Container Apps](https://learn.microsoft.com/azure/container-apps/overview)
1. [Azure Container Apps Sandboxes](https://sandboxes.azure.com)
1. [Microsoft Foundry](https://learn.microsoft.com/azure/foundry/what-is-foundry)
1. [Azure OpenAI in Azure AI Foundry Models](https://learn.microsoft.com/azure/ai-foundry/openai/overview)
1. [Azure Monitor Application Insights](https://learn.microsoft.com/azure/azure-monitor/app/app-insights-overview)

### 📚 Resources and Next Steps

| Resource | Description |
|:---------|:------------|
| [https://aka.ms/build26-next-steps](https://aka.ms/build26-next-steps) | Explore lab and demo repos to continue your learning from DEM312 and Microsoft Build |
| [Azure Samples: Azure Container Apps Multi-Agent Workflow](https://github.com/Azure-Samples/azure-container-apps-multi-agent-workflow/) | Reference implementation used for this demo, including deployment and architecture guidance |
| [Azure Container Apps dynamic sessions](https://learn.microsoft.com/azure/container-apps/sessions) | Official guidance for sandboxed and isolated execution environments |


### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the products and services covered in this demo.

**Visual Studio Code** — One click installation: 

[![Install in Visual Studio Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoft-learn&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Flearn.microsoft.com%2Fapi%2Fmcp%22%7D)


**GitHub Copilot CLI** — Run this to install the Learn MCP Server as a plugin:
```
/plugin install microsoftdocs/mcp
```

For more info, other clients, and to post questions, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

## Content Owners

<table>
<tr>
    <td align="center"><a href="https://github.com/jkalis-MS">
        <img src="https://github.com/jkalis-MS.png" width="100px;" alt="jkalis-MS"/><br />
        <sub><b>jkalis-MS</b></sub></a><br />
            <a href="https://github.com/jkalis-MS" title="talk">📢</a>
    </td>
    <td align="center"><a href="https://github.com/vinisoto">
        <img src="https://github.com/vinisoto.png" width="100px;" alt="Vini Soto"/><br />
        <sub><b>Vini Soto</b></sub></a><br />
            <a href="https://github.com/vinisoto" title="talk">📢</a>
    </td>
</tr></table>

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
