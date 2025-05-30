```mermaid
graph TB
A[Wake Word] --> B[RealtimeSTT Stream]
B --> C{LLM Processing}
C --> D[RealtimeTTS Stream]
D --> E[WebRTC/FastRTC]
E --> F[User's Speaker]
```