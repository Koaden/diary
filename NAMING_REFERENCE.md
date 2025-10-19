# NAMMING REFERENCE
This document defines the naming conventions used throughout the project.
It ensures consistency across all codebases (backend, frontend, and documentation), making the project easier to read, maintain, and scale.

## Table of contents
- [NAMMING REFERENCE](#namming-reference)
  - [Table of contents](#table-of-contents)
  - [General Principles](#general-principles)
  - [Dictionary](#dictionary)
  - [Backend (Symfony)](#backend-symfony)
  - [Frontend (React)](#frontend-react)
  - [File Naming](#file-naming)
---

## General Principles
- Always prefer **English**.
- Use **clear, descriptive, and consistent** names.
- **Avoid abbreviations** unless standard or self-evident (`id`, `url`, `api` are fine).
- Use **singular** nouns for entity and class names (User, Entry, Contact).
- Follow **consistent casing** conventions across layers (see below).

## Dictionary
| Term | Description |
| --- | --- |
| `visitor` | A non-authenticated person browsing the app (not logged in). |
| `user` | An authenticated person using the app — owner of the data. |
| `dailyEntry` | The daily form filled by the user to record mood, emotions, sleep, water, and notes. |
| `contact` | A person the user knows — used to represent relationships and shared history. |
| `activity` | A specific action, habit, or event performed during a day (e.g. sport, reading, meeting). |
| `emotion` | A discrete emotional state experienced during the day (e.g. joy, stress, calm). |
| `mood` | The global feeling or general state of mind of the user for a given day. |
| `retrospective` | An entry describing a consumed or discovered media (movie, show, game, etc.). |
| `souvenir` | An image or visual memory saved by the user — can be attached to entries or contacts. |
| `chart` | A visual representation of data. Three types are used: `radar`, `prism`, and `bar`. |
| `timeline` | The view allowing users to scroll back through past data (mood, emotions, relations). |
| `relationship` | A connection between the user and a contact, defined by three pillars: **friendship**, **romance**, and **sexual attraction**. |
| `calendar` | The interactive view used to navigate through time and make summaries of daily entries. |


## Backend (Symfony)
| Element | Convention | Example |
| --- | --- | --- |
| **Classes** | `PascalCase` | `UserController`, `DailyEntryService` |
| **Methods** | `camelCase` | `getUserEntries()`, `saveMood()` |
| **Properties** | `camelCase` | `$userRepository`, `$dailyForm` |
| **Constants** | `UPPER_SNAKE_CASE` | `DEFAULT_MOOD_VALUE` |
| **Routes** | `kebab-case` | `/api/daily-entry`, `/api/contact-profile` |
| **Entities** | Singular, `PascalCase` | `User`, `DailyEntry`, `Contact` |
| **Repositories** | Entity name + `Repository` | `UserRepository` |

## Frontend (React)
| Element | Convention | Example |
| --- | --- | --- |
| **Components** | `PascalCase` | `DailyForm.jsx`, `MoodIndicator.tsx` |
| **Hooks** | `useCamelCase` | `useFetchEntries()`, `useAuth()` |
| **Functions & Variables** | `camelCase` | `getUserData()`, `isLoading` |
| **Constants** | `UPPER_SNAKE_CASE` | `DEFAULT_MOOD`, `API_URL` |
| **Folders** | `kebab-case` | `components/`, `daily-form/`, `profile-view/` |
| **CSS classes (BEM)** | `block__element--modifier` | `card__header--highlighted` |

## File Naming
| File Type | Convention | Example |
| --- | --- | --- |
| **Markdown docs** | `UPPER_SNAKE_CASE.md` | `TECHNICAL_SHEET.md` |
| **Source files (code)** | `kebab-case` | `daily-form.jsx`, `contact-service.ts` |
| **Config files** | `kebab-case` | `.env`, `compose.yml` |
| **Tests** | `kebab-case.test.[language]` | `daily-form.test.ts` |