# Agent: A2A-SIN-WebChat

**Team:** OpenSIN-AI
**Protocol:** A2A (Agent-to-Agent)
**Status:** Active
**Repository:** https://github.com/OpenSIN-AI/A2A-SIN-WebChat

## Capabilities

A2A agent for WebChat integration within the OpenSIN ecosystem.

## Communication

- **Input:** A2A messages from orchestrator
- **Output:** A2A messages to other agents
- **MCP:** Standard OpenSIN MCP servers

## Security

- All operations logged to the approved artifact storage surface
- Requires authorization token
- Guardrails enforced on all inputs/outputs

## Setup

```bash
git clone https://github.com/OpenSIN-AI/A2A-SIN-WebChat.git
cd A2A-SIN-WebChat
bun install
bun start
```

## Boundary Guidance

When modifying this repo:

- Prefer WebChat messaging integration and embed work.
- Do not turn this repo into a generic messaging bucket.
- Do not redefine organization docs, architecture, runtime canon, or product ownership here.
- Move non-WebChat behavior back to the repos that own those surfaces.

## License

Apache-2.0
