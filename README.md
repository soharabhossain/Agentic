# Agentic
Test

graph TB
  A[User Task Input] --> B[Task Parser & Decomposer]
  B --> C[Agent Profile Registry]
  C --> D[Assignment Engine]
  D --> E[Agent Execution Layer]
  E --> F[Result Aggregator & Evaluator]

  style A fill:#cdeaff,stroke:#3399cc,stroke-width:2px
  style B fill:#def9c5,stroke:#7fba00,stroke-width:2px
  style C fill:#fff2b2,stroke:#e0a800,stroke-width:2px
  style D fill:#fde0dc,stroke:#f44336,stroke-width:2px
  style E fill:#e1bee7,stroke:#8e24aa,stroke-width:2px
  style F fill:#dcedc8,stroke:#558b2f,stroke-width:2px
