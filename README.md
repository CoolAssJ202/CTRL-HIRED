# Ctrl+Hired

A single-page business site for an IT resume and cover letter writing service, built and deployed end to end.

**Live site:** https://coolassj202.github.io/CTRL-HIRED/

## What I built

- Responsive marketing site (HTML, CSS, vanilla JavaScript) with services, pricing, process, and contact sections
- Contact form connected to Formspree so inquiries go straight to my email
- A rule-based help desk chatbot widget that answers visitor questions about services, pricing, turnaround, and ordering
- Hosted on GitHub Pages

## The chatbot

**How it works:** The widget matches keywords in a visitor's message against a set of intents (pricing, services, process, payment, credentials) and returns a pre-written response. If nothing matches, it falls back to my contact info. Quick-reply chips guide visitors to common questions.

**Why rule-based first:** It runs with no backend, no API keys, and no cost, which is the right trade-off for a new business with no traffic yet.

**Limitations:** It can't handle phrasing it wasn't written for, it has no memory of the conversation, and it can't answer questions outside its script.

## Roadmap: upgrading to a generative AI assistant

- [ ] Add a serverless backend (AWS Lambda behind API Gateway) so API keys stay off the client
- [ ] Call a foundation model through Amazon Bedrock with a system prompt grounded in my services and pricing
- [ ] Keep the rule-based flow as a fallback if the model call fails
- [ ] Add basic guardrails (topic limits, no invented prices) and log conversations to review failures
- [ ] Compare answer quality and cost against the current rule-based version

## Skills demonstrated

Front-end development, form integration, static hosting, intent-based conversation design, and deployment troubleshooting (case-sensitive `index.html` on GitHub Pages).

## Author

Jerrett Harrington, IT support professional (CompTIA A+, Cisco CCST), pursuing AWS AI Practitioner.
