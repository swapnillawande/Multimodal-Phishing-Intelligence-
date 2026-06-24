# Framework Architecture

## Input Modalities

Email Content
↓
Email Classifier

URL Features
↓
URL Classifier

Webpage Features
↓
Webpage Classifier

## Fusion Layer

Email Score
+
URL Score
+
Webpage Score
↓
Weighted Multimodal Fusion

## Output Layer

Risk Score
↓
Final Classification

- Phishing
- Legitimate

## Explainability

- Email feature importance
- URL feature importance
- Webpage feature importance

## Decision Support

- Risk prioritization
- Alert ranking
- Analyst support