<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../darkModeLogo.png">
  <img alt="Pluni" src="../lightModeLogo.png" width="230">
</picture>

# Pluni

Dein akademisches Cockpit für Studium, Module, Noten und Mensa.

Den aktuellen Stand könnt ihr immer hier sehen: **https://pluni.net**

## Wichtige Hinweise für die Entwicklung

#### [Conventional Commits](https://www.conventionalcommits.org/de/v1.0.0/)

Der komplette Code liegt in einem Monorepo: **[pluni/app](https://github.com/pluni/app)** (`api/`, `frontend/`, `mensa-scraper/`, `infra/`). Die früheren getrennten Repos (`app-api`, `app-frontend`, `infra`) sind archiviert.

Arbeitet standardmäßig immer auf dem `development`-Branch, wenn ihr Änderungen vornehmt, damit wir immer einen stabilen und funktionsfähigen Stand auf dem `main`-Branch haben. Wenn eure Änderungen auf dem `development`-Branch gut genug funktionieren und ihr keine Bugs gefunden habt, könnt ihr den `development`-Branch in den `main`-Branch mergen, um die nächste stabile Version zu veröffentlichen.

| Branch | Frontend | API | API-Docs |
|---|---|---|---|
| `development` | https://dev.pluni.net | https://dev-api.pluni.net | https://dev-docs.pluni.net |
| `main` | https://pluni.net | https://api.pluni.net | https://docs.pluni.net |
