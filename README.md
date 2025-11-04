# DIARY APP
This web application helps users record, visualize, and reflect on their daily life. It’s built around simple daily forms that let you log personal information such as sleep, water consumption, mood, emotions, and daily activities.

You can also create detailed profiles for the people you know to summarize your relationship with them — including notes, memories, and important information.

All collected data can be explored through interactive graphs and timelines, allowing you to observe trends, review past periods, and better understand your habits, emotions, and relationships over time.

---

## Features

### **MVP (v1.0.0)** *incoming*
- User account
- Daily forms for tracking activities, habits, and mood
- Relationship profiles with personal notes and details

### **Improvements Update (v1.2.0)** *planned*
- Dark mode
- Daily text note (markdown supported)

### **Pictures Update (v1.3.0)** *planned*
- Souvenir pictures in daily entries
- Profile and contact pictures
- Media gallery view

### **Import / Export Update (v1.4.0)** *planned*
- Export (`.csv`, `.pdf`)
- Import (`.csv`)

### **Mobile Update (v2.0.0)**
- Mobile app

## Requirements

- [Docker](https://docs.docker.com/engine/install/)
- [Docker compose](https://docs.docker.com/compose/install/)

## Tech Stack

- **Back:** `Symfony`
- **Front:** `React + Vite`
- **Database:** `Mongodb`
- **Containerization:** `Docker Compose`
- **Visualization:** `Chart.js` 

## Installation

1. Clone this repository
    ```bash
   git clone https://github.com/Koaden/diary.git
2. Duplicate `.env.dist` and rename it `.env` and change sensitive data
3. Run docker compose
    ```bash
    make start