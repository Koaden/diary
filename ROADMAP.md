# ROADMAP
This document outlines the current and planned development tasks for the project. It’s meant to guide contributors and help track progress.

---

## MVP (v1.0.0)
**Focus:** Core features and project's backbone

All features need to have **front and back implemetation**

### Documentation
- [X] README.md
- [X] CONTRIBUTION.md
- [X] ROADMAP.md
- [ ] TECHNICAL_SHEET.md
  - [ ] Class diagram
- [ ] NAMING_REFERENCE.md
- [ ] UI mockups
  - [ ] Color palette and typography
  - [ ] Figma mockups:
    - [ ] Home
    - [ ] Daily Form
    - [ ] Relationship Profile
    - [ ] Calendar View

### DevOps
- [X] Docker Compose setup (backend, frontend, db)
- [X] Makefile commands (`make start`, `make stop`, etc.)
- [X] Environment variables setup
- [ ] Fixtures

### Features
- [ ] REST api + JWT
- [ ] User authentication
  - [ ] Register
  - [ ] Login
  - [ ] Logout
- [ ] Daily form
  - [ ] Mood indicator (based on emotions)
  - [ ] Sleep periods
  - [ ] Water consumption
  - [ ] Activities
- [ ] Contact cards
  - [ ] Profil
    - [ ] Name
    - [ ] Birthday (or age if birthday unknown)
    - [ ] Working status (and get information about it)
  - [ ] Mardown notes
  - [ ] Relationship (Chart.js)
- [ ] Calendar
- [ ] Homepage

## Mobile Update (v1.2.0)
**Focus:** Improvements and code testing 

All features need to have **front and back implemetation**

### Documentation
- [ ] Update `TECHNICAL_SHEET.md`

### DevOps
- [ ] CI/CD
- [ ] Linter
- [ ] Tests

### Features
- [ ] Markdown support
- [ ] Dark/light mode

## Pictures Update (v1.3.0)
**Focus:** Adding pictures

All features need to have **front and back implemetation**

### Documentation
- [ ] Update `TECHNICAL_SHEET.md`
  - [ ] Pictures database
  - [ ] Update archintecture

### Features
- [ ] Souvenir pictures in daily entries
- [ ] Profile and contact pictures
- [ ] Media gallery view (Masonry.js)


## Import / Export Update (v1.4.0)
**Focus:** megrate data and share

All features need to have **front and back implemetation**

### Documentation
- [ ] Update `TECHNICAL_SHEET.md`
  - [ ] CSV interpretor
  - [ ] CSV and PDF maker

### Features
- [ ] Export
  - [ ] `.csv`
  - [ ] `.pdf`
- [ ] Import
  - [ ] `.csv`