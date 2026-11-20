# EcoTravel — Frontend

> Bachelor team project for the *Web Frameworks* course (3 students, Nov. 2024 – Jan. 2025) · **Archived, not maintained**

EcoTravel is a fictional platform built for a course project. It lists **eco-friendly accommodations and activities** and lets travellers combine them into **itineraries**. The original goal was also to estimate the CO₂ footprint of each itinerary.

This repository contains the **Angular client**. The REST API is in [ecotravel-backend](https://github.com/LucasB152/ecotravel-backend), and its README describes the features in detail.

## Project status

The project was delivered at the end of the course and has not been worked on since. **Some features are incomplete**. In particular, the CO₂ estimation of itineraries was never implemented.

## Pages

- Sign-up, login and email verification
- Search for destinations by type and tags, destination details and reviews
- User profile and profile editing
- Itinerary details: add, remove and reorder steps
- Host area: host account request, create and edit destinations
- Admin dashboard

## Tech stack

Angular 18 (with SSR) · TypeScript · Tailwind CSS · Docker + Nginx

## Running locally

Requirements: Node.js 20 and the backend running on `http://localhost:8081`.

```bash
npm install
npm start          # http://localhost:4200
```

or with Docker:

```bash
docker build -t ecotravel-front .
docker run -p 80:80 ecotravel-front
```
