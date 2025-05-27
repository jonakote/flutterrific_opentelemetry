# Development Setup Instructions

After cloning the repository, you'll need to make some scripts executable:

```bash
chmod +x run_coverage.sh
```

Then you can use the Makefile for common development tasks:

```bash
make help          # Show available commands
make install       # Install dependencies  
make test          # Run tests
make coverage      # Run tests with coverage
make analyze       # Analyze code
make format        # Format code
make all           # Run all checks
```
