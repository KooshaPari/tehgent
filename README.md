# TehGent

AI-powered code review and development assistant that integrates with your development workflow.

## Overview

TehGent is an intelligent code review assistant that leverages multiple AI providers to provide comprehensive code analysis, suggestions, and automated improvements.

## Features

- **Multi-Provider Support**: Works with OpenAI, Claude, Gemini, and more
- **Smart Code Review**: Intelligent analysis of code changes
- **Automated Suggestions**: Actionable improvement recommendations
- **PR Integration**: Seamless pull request workflows
- **Customizable Rules**: Define your own review criteria
- **Real-time Feedback**: Fast, streaming responses

## Quick Start

```bash
# Install
go install github.com/KooshaPari/tehgent@latest

# Configure
tehgent config init

# Run review
tehgent review --pr 123
```

## Documentation

- [Implementation Plan](docs/IMPLEMENTATION_PLAN.md)
- [Architecture Decision Records](docs/adr/)
- [API Reference](docs/API.md)

## License

MIT License - see [LICENSE](LICENSE) for details.
