Space for ARCHER Connect Test Automation
- UI Tests
- API Tests

Usage:
Run tests against a defined environment on a browser type from the command line 

Environments: QA, Stage, PreProd

Browser Type: Chrome, Edge, Headless

Run command: dotnet test -e Env=QA -e Browser=Chrome --filter "Category=Shakeout"
