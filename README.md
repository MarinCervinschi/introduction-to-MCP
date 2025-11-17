# Introduction to Model Context Protocol (MCP)

This repository contains practical examples from the [Anthropic Academy](https://anthropic.skilljar.com/) courses on Model Context Protocol (MCP). These examples demonstrate how to build MCP servers and clients with various features and capabilities.

## 📚 About MCP

The Model Context Protocol (MCP) is an open protocol that enables seamless integration between AI applications and external data sources and tools. It provides a standardized way for AI models to interact with various services while maintaining security and context.

## 🗂️ Repository Structure

### [`cli_project/`](./cli_project)
A command-line chat application demonstrating core MCP concepts including:
- Document retrieval using `@` references
- Command-based prompts with `/` prefix
- Tool integration via MCP architecture
- STDIO transport communication

**Course**: Introduction to Model Context Protocol

### [`roots/`](./roots)
Advanced MCP implementation featuring:
- File system access with controlled root directories
- Video conversion capabilities using FFmpeg
- Security constraints for file operations
- Multiple root directory support

**Course**: Model Context Protocol: Advanced Topics

### [`notifications/`](./notifications)
Demonstrates MCP notification system:
- Progress tracking and reporting
- Logging mechanisms
- Real-time status updates

**Course**: Model Context Protocol: Advanced Topics

### [`sampling/`](./sampling)
Shows MCP sampling capabilities:
- Model sampling through MCP
- Request/response handling
- STDIO transport patterns

**Course**: Model Context Protocol: Advanced Topics

### [`transport-http/`](./transport-http)
HTTP transport implementation:
- Alternative to STDIO transport
- HTTP-based MCP communication
- Web-based integration patterns

**Course**: Model Context Protocol: Advanced Topics

## 📖 Learning Resources

### Anthropic Academy Courses

- **[Introduction to Model Context Protocol](https://anthropic.skilljar.com/introduction-to-model-context-protocol)** - Core concepts, server/client architecture, and basic implementations
- **[Model Context Protocol: Advanced Topics](https://anthropic.skilljar.com/)** - Advanced features including roots, sampling, notifications, and HTTP transport

### Official Documentation

- [MCP Documentation](https://modelcontextprotocol.io/)
- [MCP Specification](https://spec.modelcontextprotocol.io/)
- [MCP GitHub Repository](https://github.com/modelcontextprotocol)
- [Anthropic Documentation](https://docs.anthropic.com/)
