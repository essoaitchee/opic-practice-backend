# opic-practice-backend

Spring Boot backend for the general OPIC application domain.

Current backend role:
- authentication and user-related APIs
- question, practice, and record management
- general application business logic and persistence

STT responsibility:
- speech-to-text is no longer handled in this Spring Boot service
- frontend should call the separate `opic-practice-stt` Python server for audio transcription
- this backend remains focused on core application APIs rather than direct audio processing
