# Q3 Findings and Analysis

## LLM Performance

The ESG triage prompt successfully classified environmental, social and governance issues into structured JSON outputs. The model consistently identified urgency, sentiment, escalation requirements and responsible teams.

## Comparison with Rule-Based Baseline

The rule-based approach relied on simple keyword matching and predefined rules. While effective for basic classification, it lacked contextual understanding.

The LLM demonstrated stronger reasoning capabilities by:
- Identifying workplace safety implications
- Recognising accessibility concerns
- Linking supplier compliance issues to governance risks
- Producing richer escalation explanations

## Limitations

- Possible hallucinations
- Classification inconsistencies
- Dependence on prompt quality
- Sensitive organisational data concerns

## Recommendation

The solution is suitable for limited enterprise deployment with human review. High-risk classifications should require manual validation before escalation.

## Cloud Deployment

Azure Logic Apps, Azure OpenAI, Azure Functions, Azure SQL Database and Power BI provide a scalable cloud architecture capable of supporting ESG message triage at enterprise scale.
