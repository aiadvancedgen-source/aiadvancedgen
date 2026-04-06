```mermaid
graph TD
  Lead((Inbound Lead)) -->|Trigger| n8n[n8n Logic Engine]
  n8n --> AI[Claude AI: Agentic Reasoning]
  AI -->|Action| CRM[CRM Architecture: GHL / HubSpot]
  CRM -->|Outcome| Results[15+ Hours Saved / Week]

  %% High-Contrast Styling
  style n8n fill:#4c6ef5,stroke:#fff,stroke-width:2px,color:#fff
  style AI fill:#be4bdb,stroke:#fff,stroke-width:2px,color:#fff
  style CRM fill:#343a40,stroke:#fff,stroke-width:2px,color:#fff
  style Results fill:#2f9e44,stroke:#fff,stroke-width:2px,color:#fff
