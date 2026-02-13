# 🤖 AI Agent Framework

Production-ready AI agent starter with OpenAI Agents SDK integration.

## Features

- OpenAI Responses API / Agents SDK
- Tool calling (functions)
- Conversation memory
- Streaming responses
- TypeScript + Zod validation

## Quick Start

```bash
npm install
npm run dev
```

## Usage

```typescript
import { Agent } from "./src/agent";

const agent = new Agent({
  model: "gpt-4o",
  instructions: "You are a helpful assistant"
});

const response = await agent.run("Hello!");
```
