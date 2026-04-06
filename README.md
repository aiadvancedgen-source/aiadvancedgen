```mermaid
graph TD
  Lead((Inbound Lead)) -->|Trigger| n8n[n8n Logic Engine]
  n8n --> AI[Claude AI: Agentic Reasoning]
  AI -->|Action| CRM[CRM Architecture: GHL / HubSpot]
  CRM -->|Outcome| Results[15+ Hours Saved / Week]

  style AI fill:#f9f,stroke:#333,stroke-width:2px
  style n8n fill:#bbf,stroke:#333,stroke-width:2px
