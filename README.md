# 🛡️ Agentic DevTool CLI
### The black box recorder for your AI agents.

Building AI agents is easy. Debugging them is hard. The **Agentic DevTool CLI** is a mission-critical utility for observability and secret management in agentic workflows. Built for developers who need to know exactly what their agents are doing—and keep their keys safe while doing it.

## 🚀 The Product Experience
No more hunting through logs. The Agentic CLI provides a standardized bridge between your agent's execution and your observability stack, streaming traces and managing secrets with a single command.

### 📐 Logical Flow
```text
[ Agent Workflow ] ----(Secret Request)----> [ Agentic CLI Vault ]
       |                                            |
       +-------(Trace Stream)------> [ Honeycomb / Observability ]
                                            |
                                            v
[ Developer ] <---(Real-time Debugging)-----+
```

## 🛠️ Technical Stack
- **CLI Engine**: Built with **Node.js** and **Commander.js** for a robust developer experience.
- **Security**: Integrated secure secret management for agent-specific credentials.
- **Observability**: Direct telemetry streaming to **Honeycomb** for deep-dive performance analysis.
- **Lifecycle Management**: Standardized hooks for agent initialization and trace capture.

## 📈 Engineering Impact
- Dramatically accelerated the debugging cycle for complex agentic loops.
- Standardized secret management, reducing the risk of credential leakage in dev environments.
- High-performance trace streaming with minimal overhead on the host agent.

---

## 🏗️ Infrastructure
Managed via Infrastructure as Code (Terraform).
See the [terraform/](./terraform/) directory for configuration.

## 📥 Installation
```bash
npm install
npm run build
npm link
```

## 🎮 Usage
```bash
# Initialize secure storage for your agent
agentic-cli secret-init

# Start streaming traces for real-time debugging
agentic-cli trace-stream
```
