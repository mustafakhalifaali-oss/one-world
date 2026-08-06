# Database Schema

## Users

Stores user accounts.

Fields:
- id
- full_name
- email
- password_hash
- language
- country
- created_at

---

## Goals

Stores the user's primary goal.

Fields:
- id
- user_id
- goal_type
- target_country
- target_city
- status

---

## Journeys

Stores each user journey.

Fields:
- id
- user_id
- goal_id
- progress
- current_step

---

## Tasks

Stores journey tasks.

Fields:
- id
- journey_id
- title
- description
- status

---

## Saved Items

Stores saved jobs, hotels, properties and universities.

Fields:
- id
- user_id
- item_type
- item_id

---

## Notifications

Stores notifications.

Fields:
- id
- user_id
- title
- message
- created_at
