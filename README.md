# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69bb07063c34be99a019c3b3_user:Usj5y3WL%26nhryc2jdqGq5q7Qx%26r2RD%5E2@ep-dawn-union-anhcakgd.c-6.us-east-1.aws.neon.tech:5432/AppDB_69bb07063c34be99a019c3b3?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
