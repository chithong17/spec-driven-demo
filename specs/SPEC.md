\# SPEC — AI Chat Learning Assistant



\## Problem

Người học tiếng Nhật gặp khó khăn khi luyện phản xạ hội thoại và không biết dùng từ đúng ngữ cảnh.



\## Goal

Xây dựng tính năng “AI Chat” giúp người học trò chuyện tiếng Nhật với chatbot và nhận phản hồi kèm bản dịch.



\## User Story

Là sinh viên học tiếng Nhật, tôi muốn nhập câu hỏi và nhận phản hồi tiếng Nhật + bản dịch tiếng Việt để luyện phản xạ.



\## Acceptance Criteria

1\. Khi nhập câu tiếng Nhật, chatbot phản hồi trong ≤2s bằng tiếng Nhật.

2\. Có nút “Dịch sang tiếng Việt”.

3\. Lưu lại lịch sử hội thoại trong session hiện tại.



\## In Scope

\- Giao diện chat cơ bản (frontend React)

\- API `/api/chat` (backend Spring Boot gọi OpenAI)

\- Translation button (FE gọi API translate)



\## Out of Scope

\- Đăng nhập, lưu trữ tài khoản, giao diện mobile



