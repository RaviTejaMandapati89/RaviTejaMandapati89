# Ravi Teja Mandapati

Product lead for agentic AI platforms in regulated financial services. I build to understand what's actually hard behind a clean product spec.

**kyc-aml-multiagent**: a governed multi-agent compliance system. Every MCP tool call passes one policy enforcement point backed by an ABAC decision engine (default-deny, rules as data). Agent-to-agent handoffs carry signed workload-identity tokens bound to the payload, tested against nine attack cases. DESIGN.md records the decisions and trade-offs; docs/verified-run.md shows it running.

Current focus: agent identity and authorisation, meaning who an agent is, who it acts for, and what it may do at each hop.

Stack in this repo: Gemini, AWS Bedrock Agents, LangGraph, MCP, A2A, OpenTelemetry, Python.

Day job: agentic AI platforms at Lloyds Banking Group. Previously Barclays and LTI/Citi. IIM Bangalore MBA. GCP Professional Cloud Architect
