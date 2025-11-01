# PLAN — AI Chat Learning Assistant

## Architecture
- Frontend: React + Vite
- Backend: Spring Boot 3 (Java 21)
- Model: Azure OpenAI API
- Communication: REST (JSON)

## API Contract
POST /api/chat  
req: { "message": "..." }  
res: { "reply": "..." }

## Sequence
```mermaid
sequenceDiagram
  User ->> FE: nhập câu hỏi
  FE ->> BE: POST /api/chat
  BE ->> OpenAI: gửi prompt
  OpenAI -->> BE: trả lời
  BE -->> FE: { reply }
  FE -->> User: hiển thị chat
