# Docker Interview Questions & Answers

## 🔹 General Questions

### 1. What is Docker?
Docker is a containerization platform.

### 2. Container vs VM?
- Container → Lightweight
- VM → Full OS

---

## 🔹 Scenario-Based Questions

### 1. Container crashing?
- Check logs: docker logs
- Check Dockerfile
- Verify dependencies

### 2. Reduce image size?
- Use Alpine image
- Multi-stage build
- Remove unnecessary files

### 3. Data persistence?
- Use Docker volumes