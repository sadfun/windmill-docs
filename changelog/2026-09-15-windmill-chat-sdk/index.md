---
slug: windmill-chat-sdk
version: v1.812.0
title: Chat SDK for flows in chat mode
tags: ['AI', 'Flow editor']
description: The @windmill-labs/chat-sdk npm package puts a chat over a deployed chat mode flow in any frontend or full-code app. It is headless - it runs the flow per message, follows the streamed answer and keeps conversation history - with entry points for the Vercel AI SDK, assistant-ui, React and framework-agnostic stores.
features:
  [
    'Install with npm install @windmill-labs/chat-sdk; no runtime dependencies.',
    '@windmill-labs/chat-sdk/ai-sdk is a transport for the Vercel AI SDK useChat hook, @windmill-labs/chat-sdk/assistant-ui a runtime for assistant-ui, @windmill-labs/chat-sdk/react a hook, and the root export a store that follows the Svelte store contract.',
    'Inside a full-code app only the flow path is needed: the chat runs as the viewer against the instance serving the app.',
    'Outside Windmill, a token scoped to jobs:run:flows:<path> is enough to run the flow and follow its answer.',
    'Conversation history is read from Windmill per user, or kept in the browser when one token is shared by every visitor.',
  ]
docs: /docs/flows/flow_as_chat#chat-sdk-for-your-own-frontend
---
