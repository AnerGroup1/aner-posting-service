# Posting Service

## Overview

The Posting Service is an internal microservice responsible for recording financial posting events for the FinTech platform. It provides a centralized interface for writing monetary transactions into the platform ledger.

This service is designed to be consumed only by internal platform services and is not exposed publicly.

---

## Repository Information

| Property | Value |
|----------|-------|
| Repository | aner-posting-service |
| Organization | AnerGroup1 |
| Visibility | Private |
| Default Branch | main |

---

## Repository Structure

```
aner-posting-service
│
├── .github
│   ├── CODEOWNERS
│   ├── pull_request_template.md
│   └── workflows
│
├── docs
│
├── src
│
├── tests
│
├── README.md
│
├── CONTRIBUTING.md
│
└── requirements.txt
```

---

## Development Workflow

1. Create a feature branch.
2. Implement the required changes.
3. Commit changes using the defined commit convention.
4. Push the branch to GitHub.
5. Create a Pull Request.
6. Complete code review.
7. Merge into the main branch.

---

## Branching Strategy

- main
- feature/*
- bugfix/*
- hotfix/*
- release/*

---

## Code Ownership

Repository ownership is managed through the `.github/CODEOWNERS` file.

---

## Pull Requests

All changes must be submitted through Pull Requests.

---

## Code Reviews

Every Pull Request should be reviewed before merging.

---

## License

Internal Company Repository.