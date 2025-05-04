# 🧪 Test Plan for Breach Application

## 1. Overview
This test plan covers **functional, exploratory, API, UI, load, and WebSocket testing** for the Breach application. The goal is to identify bugs, UX issues, and performance bottlenecks.

## 2. Test Objectives
- Verify core user flows: registration, login, filtering, onboarding, and real-time updates.
- Ensure correct API functionality and WebSocket connectivity.
- Assess UX across browsers and screen sizes (web/mobile).
- Discover and document any bugs with supporting evidence (screenshots/videos).
- Automate key flows where feasible.

## 3. Scope

### ✅ In Scope
- Functional testing (frontend and backend)
- Exploratory UI testing
- API and WebSocket testing
- Cross-browser/device testing
- Load testing
- Bug documentation and reporting

### ❌ Out of Scope
- Backend code review

## 4. Features to Test

### Frontend
- Register and login
- Display of blog posts
- Filter posts by category
- Onboarding topic selection
- Live news feed from WebSocket

### Backend (via Swagger/Postman)
- Registration/login APIs
- Blog posts and categories APIs
- Interest saving API
- WebSocket news stream

## 5. Test Types
- Functional Testing  
- Exploratory Testing  
- Cross-browser Testing  
- Load Testing  
- API Testing (via Postman)  
- WebSocket Testing  

## 6. Test Environments
- **Frontend:** `https://breach-fe.qa.mvm-tech.xyz/`  
- **Backend API:** `https://breach-api.qa.mvm-tech.xyz/swagger/`  
- **WebSocket:** `wss://breach-api-ws.qa.mvm-tech.xyz`

## 7. Tools & Frameworks
- **Postman** – API testing  
- **WebSocket Client (Postman)** – Real-time connection tests  
- **Google Sheets** – Bug tracking  
- **Google Drive** – Test session videos  

## 8. Risk Assessment

| Risk                   | Impact | Mitigation                                                  |
|------------------------|--------|--------------------------------------------------------------|
| No PRD (Product Doc)   | High   | Derive requirements through UI/design and exploratory testing |
| Real-time event failure| High   | Thorough WebSocket tests with connection and event logging   |

### 9. Test Deliverables

- [Test Plan (this document)](#)
- [Test Report](https://docs.google.com/document/d/1-22Rgb_DDprAjDOcMPzGb3BYaupV0HO26tm1NwLjHdw/edit?tab=t.0)
- [Bug Report](https://docs.google.com/spreadsheets/d/1PWOIr8a3VSpLuOjDzqtTWsXJ0ZcL1aTld5_dhFMq7Z4/edit?gid=555480705#gid=555480705)
- [Test Execution Videos](https://docs.google.com/document/d/1oNfh2xM44T57D8colIqiv6Zegwzit9Uu5suNUZI_CFc/edit?tab=t.0)
  
  
## 10. Timeline

| Phase                  | Estimated Time |
|------------------------|----------------|
| Exploratory Testing    | 1–2 days        |
| API/WebSocket Testing  | 2 days          |
| Documentation & Report | 1 day           |
