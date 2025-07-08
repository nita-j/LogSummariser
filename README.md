# LogSummariser

LogSummariser is an advanced log analysis and summarization platform powered by LangChain and LLMs. It transforms verbose application logs into meaningful insights — enabling fast diagnosis, traceability, and decision-making across tech teams.

🔍 Core Features:
📄 Log Summarization
Condenses large volumes of application logs into human-readable summaries, highlighting critical events and anomalies.

🔗 CID Identification & Trace Audit
Automatically detects Correlation IDs (CIDs) across logs and reconstructs end-to-end transaction flows for complete CID audits.

✅ CID Compliance Validation for Banking Applications
Ensures that every log entry in critical workflows includes a valid Correlation ID (CID) — a key requirement for auditability, traceability, and compliance in banking and financial systems. Flags missing, duplicated, or malformed CIDs to help meet internal policies and regulatory standards (e.g., RBI, PCI DSS, SOX).

🧠 CTO-Level CID Validation
Provides governance insights by highlighting non-compliant services, helping enforce CID logging standards across distributed systems.

🛠️ Support-Focused Analysis
Designed for Production Support teams, the tool surfaces actionable error summaries, root cause clues, and service-level patterns for faster incident resolution.

💬 Conversational Interface
Ask questions like “What failed in the last hour?” or “Show all logs for CID 123abc” and receive contextual answers using LangChain-powered agents.

🧩 Seamless Integration
Connects easily with existing log pipelines (e.g., ELK, Loki, Splunk) and can run as a standalone or embedded tool.

