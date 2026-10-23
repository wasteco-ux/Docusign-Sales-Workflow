# Docusign-Sales-Workflow
Sales workflow - Docusign API key for facilitating data export

# OpsLevel Components

This project collects VS Code Copilot prompt files (`.prompt.md`) for resolving **OpsLevel critical check failures** across Wasteco / Geotab components.

Because OpsLevel rubric requirements change frequently, prompts live here as versioned, reusable files rather than one-off chat history.

## How to use

1. Open any prompt file from the `.github/prompts/` folder in VS Code.
2. In the Copilot Chat panel, type `#` and select the prompt by name, or open the file and click **Run prompt**.
3. Answer any follow-up questions the prompt generates.

## Structure

```
OpsLevel Components/
└── .github/
    └── prompts/
        └── resolve-ktlint-configuration.prompt.md   # Kotlin / ktlint Gradle plugin check
```

## Adding new prompts

Create a new `.prompt.md` file in `.github/prompts/` following the naming convention:

```
resolve-<check-name-kebab-case>.prompt.md
```

Include a `description:` in the YAML front matter so VS Code surfaces it in the prompt picker.

## OpsLevel checks covered

| Prompt file | OpsLevel check | Rubric |
|---|---|---|
| `resolve-ktlint-configuration.prompt.md` | ktlint Configured | Deployment Frequency – KOTR (QA/DEVOPS COE) |
