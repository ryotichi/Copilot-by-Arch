# Security Policy

## Reporting Security Issues

Please do not publish API keys, tokens, credentials, or other sensitive information in public issues or pull requests.

If you find a security-related problem in this repository, please open an issue with a minimal description that does not expose secrets or private data.

## Sensitive Information

Do not commit:

- API keys
- Access tokens
- Passwords
- Private SSH keys
- Personal configuration files
- .env files
- Production credentials

Use example files such as .env.example or config.example.md instead.

## AI Tool Usage

When using AI-assisted development tools, all generated code, commands, and configuration should be reviewed before use.

Generated content should not be trusted blindly, especially when it involves:

- Shell commands
- Package installation
- System configuration
- Authentication
- Network access
- Security settings
