# DIARY APP
This web application helps users record, visualize, and reflect on their daily life. It’s built around simple daily forms that let you log personal information such as sleep, water consumption, mood, emotions, and daily activities.

You can also create detailed profiles for the people you know to summarize your relationship with them — including notes, memories, and important information.

All collected data can be explored through interactive graphs and timelines, allowing you to observe trends, review past periods, and better understand your habits, emotions, and relationships over time.

---

## Features

### **MVP (v1.0.0)** *incoming*
- User account
- Daily forms for tracking activities, habits, and mood
- Daily text note (markdown supported)
- Relationship profiles with personal notes and details

### **Mobile Update (v1.2.0)** *planned*
- Mobile app
- Retrospectives (movies, TV shows, games)
- Dark mode

### **Pictures Update (v1.3.0)** *planned*
- Souvenir pictures in daily entries
- Profile and contact pictures
- Media gallery view

### **Import / Export Update (v1.4.0)** *planned*
- Export (`.csv`, `.pdf`)
- Import (`.csv`)

## Requirements

- [Docker](https://docs.docker.com/engine/install/)
- [Docker compose](https://docs.docker.com/compose/install/)

## Tech Stack

- **Backend:** Symfony
- **Database:** Mongodb
- **Frontend:** React
- **Containerization:** Docker Compose
- **Visualization:** Chart.js

## Installation

1. Clone this repository
    ```bash
   git clone https://github.com/Koaden/diary.git
2. Remove `.git` folder
3. Duplicate `.env.dist` and rename it `.env` and change sensitive data
4. Run docker compose
    ```bash
    make start