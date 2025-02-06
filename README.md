# Morpheus Transform AI

AI-powered data transformation proxy that automatically maps and transforms data between services.

## Repositories

### [morpheus-core](https://github.com/morpheustransform-ai/morpheus-core)
Core proxy and transformation engine. Handles data mapping, schema learning, and runtime transformations.

### [morpheus-client](https://github.com/morpheustransform-ai/morpheus-client)
Management UI for monitoring transformations, visualizing schemas, and configuring the proxy.

## Quick Start

```typescript
const morpheus = new Morpheus({
  provider: 'openai',
  model: 'gpt-4'
});

// Start proxy
await morpheus.start({
  source: 'http://legacy-api',
  target: 'http://new-api'
});
```

## Features

- 🤖 AI-powered data mapping
- 🔄 Real-time transformations
- 🛡️ Automatic validation
- 📊 Live monitoring
- 🔧 Zero-config setup

## Documentation
- [Core Documentation](./morpheus-core/README.md)
- [Client Documentation](./morpheus-client/README.md)
- [API Reference](./docs/api.md)

## License
MIT © Morpheus Transform AI
