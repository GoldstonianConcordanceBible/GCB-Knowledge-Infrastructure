# API Specification (Conceptual)

## Purpose

Defines the future API layer for the SydTek Fluency Lab platform.

## Core Objects

### User

- id
- name
- native_language
- target_language
- role (learner, mentor, instructor)
- reputation_score
- certification_level

### Session

- id
- user_a
- user_b
- date
- duration
- topic
- verified (true/false)
- recording_url

### Assessment

- id
- user_id
- speaking_score
- listening_score
- pronunciation_score
- response_speed_score
- correction_score
- instructor_id
- status (pending, passed, failed)

### Certificate

- id
- user_id
- level
- date_awarded
- instructor_id
- verification_hash (future)

### Reputation

- user_id
- reliability_score
- fluency_growth_score
- correction_score
- mentor_score

## Core Endpoints (Future)

- POST /users/create
- GET /users/{id}
- POST /sessions/log
- POST /sessions/verify
- POST /assessments/submit
- GET /assessments/{user_id}
- POST /certificates/issue
- GET /certificates/{user_id}
- GET /reputation/{user_id}

## Core Principle

Data must reflect proof, not claims.