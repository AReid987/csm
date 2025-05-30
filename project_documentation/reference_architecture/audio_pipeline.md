```mermaid
graph TB
A[Wake Word] --> B[Record Audio]
B --> C[STT: Speech-to-Text]
C --> D[Process Text]
D --> E[Generate Response]
E --> F[TTS: Synthesize Voice]
F --> G[Play Audio]
```