# ROADMAP
This document outlines the current and planned development tasks for the project. It’s meant to guide contributors and help track progress.

---

## MVP (v1.0.0)
**Focus:** core features and project's backbone

All features need to have **front and back implemetation**

### Documentation
- [X] README.md
- [X] CONTRIBUTION.md
- [X] ROADMAP.md
- [ ] TECHNICAL_SHEET.md
  - [ ] Class diagram
  - [ ] Tests
    - [X] Backend
    - [ ] Frontend
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
- [ ] CI/CD
- [ ] Linter
- [ ] Fixtures

### Features
- [ ] REST api + JWT
- [ ] User authentication
  - [ ] Register
  - [ ] Login
  - [ ] Logout
- [ ] Daily form
  - [ ] Mardown notes
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
**Focus:** mobile app

All features need to have **front and back implemetation**

### Documentation
- [ ] Update `TECHNICAL_SHEET.md`
  - [ ] Mobile apk generator process
  - [ ] Movies and tv shows api
  - [ ] Video games api
  - [ ] Board games api

### Features
- [ ] Retrospectives
  - [ ] Movies
  - [ ] TV shows
  - [ ] Video games
  - [ ] Board games
- [ ] Dark/light mode

## Pictures Update (v1.3.0)
**Focus:** adding pictures

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