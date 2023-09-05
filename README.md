# Gamification Platform

This repository serves as the main project for a gamification platform. It includes the services and apps which compose tha entire platform

- `gamification_api`: Backend API to handle data and logic.
- `gamification_frontend`: Frontend web interface for user interaction.

## Structure

```plaintext
gamification_platform/
├── gamification_api (submodule)
├── gamification_frontend (submodule)
└── README.md
```

## Run with docker-compose"
```bash
docker-compose up --build
```

### Clone with submodules

To clone this repository, including all submodules, you can use:

```bash
git clone --recursive  git@github.com:alquimistas-org/gamification_platform.git
```

If you've already cloned the repository without submodules, run:

```bash
git submodule update --init
```

### Pulling Changes Including Submodules

If you want to pull changes that affect not only the main repository but also update all the included submodules, you can use:

```bash
git pull --recurse-submodules
```

### Adding a New Submodule

To add a new submodule to the project, you can:

```bash
git submodule add <repository_url>
```
