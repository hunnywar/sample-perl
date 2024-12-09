# Perl Hello World Project

## Project Structure
```
perl-hello-world/
│
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
│
├── src/
│   └── main.pl
│
├── t/
│   └── main.t
│
├── lib/
│   └── HelloWorld.pm
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── Makefile.PL
├── cpanfile
├── .gitignore
└── README.md
```

## Setup and Development

### Prerequisites
- Docker
- Visual Studio Code
- Docker Extension for VSCode

### Installation
1. Clone the repository
2. Open in VSCode
3. Reopen in container

### Running Tests
```bash
prove -v t/
```

### Project Details
This is a comprehensive Perl project demonstrating best practices in Perl development.
