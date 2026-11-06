# Implementation Checklist

Build the application yourself using `PROJECT_BRIEF.md`.

## Initial setup

- [ ] Read the project specification.
- [ ] Review the architecture and data model.
- [ ] Create a Python virtual environment.
- [ ] Install and pin the required dependencies.
- [ ] Configure credentials through environment variables.
- [ ] Review the data privacy and security requirements.

## Project acceptance criteria

- [ ] Upload succeeds (200 OK)
- [ ] All top‑level callables indexed
- [ ] Embedding stored with UUID
- [ ] Generated at least 3 syntactically correct tests
- [ ] Tests import the target function without errors
- [ ] Explanation ≤ 2 sentences
- [ ] Mentions at least one line number or variable
- [ ] Feedback recorded in DB
- [ ] Prompt‑tuning data size updates correctly
- [ ] Dashboard loads in <2 s
- [ ] All API calls appear in trace viewer
- [ ] Set up FastAPI project
- [ ] Design PostgreSQL schema with pgvector
- [ ] Implement file upload & AST extraction
- [ ] Integrate OpenAI embedding API
- [ ] Store vectors in pgvector
- [ ] Build similarity query endpoint
- [ ] Create LangChain prompt templates
- [ ] Implement test generation endpoint
- [ ] Add explanation sub‑prompt
- [ ] Design React UI for review
- [ ] Add feedback POST endpoint
- [ ] Persist feedback & update prompt‑tuning set
- [ ] Add OpenTelemetry instrumentation
- [ ] Write Dockerfile & docker‑compose stack
- [ ] Configure GitHub Actions CI/CD
- [ ] Unit test FastAPI routes with pytest‑asyncio
- [ ] Integration test embedding‑search round‑trip
- [ ] Mock LLM responses to verify parsing logic
- [ ] E2E test full UI flow with Playwright
- [ ] Dockerize backend & frontend
- [ ] Use docker‑compose for local dev (Postgres, Redis, OpenTelemetry Collector)
- [ ] Deploy to Render/railway (free tier) or Azure Container Apps
- [ ] Enable HTTPS via Let’s Encrypt

## Before completion

- [ ] Implement the planned MVP features.
- [ ] Add unit and integration tests.
- [ ] Run the test suite.
- [ ] Measure the evaluation metrics in the brief.
- [ ] Record actual results and known limitations.
- [ ] Document setup and deployment.
- [ ] Update the README to reflect the implemented features.
- [ ] Add only verified outcomes to your resume.
