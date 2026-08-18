# Lincoln Melo

Full-stack engineer based in São Paulo, Brazil.

I ship the slice myself: UI, API, data, deployment and LLM calls treated
as paid, fallible dependencies, not magic.

I am studying Computer Engineering at Insper, write in English, and work best
in small teams that own products end to end.

## Selected work

### Ecocina

Ecocina was a commercial pilot focused on reducing food waste in professional
kitchens.

I owned the product vertical end to end: a React and TypeScript application
used on the web and Android through Capacitor, a FastAPI backend, PostgreSQL
data storage, cloud infrastructure, deployment, trial and billing workflows,
and an analytics dashboard built with React and MUI.

The product used computer vision to estimate discarded food items and weight
from photos taken by kitchen staff. Because AI-generated values affected
business metrics, the workflow required human confirmation before accepting a
result.

I designed the AI workflow as a paid and fallible dependency rather than
treating model output as truth:

- AI processing stayed behind the backend API.
- Requests used access controls and timeouts.
- Recommendations were cached using a hash of the kitchen's recent
  statistical data.
- The dashboard did not invoke the model on every refresh.
- Failed recommendations produced a fallback response without polluting the
  cache.

The pilot was discontinued and had no public usage metrics. The source code
and implementation details are not public because the project was associated
with a commercial initiative.

### Other work

- [China Real Estate Regression](https://github.com/LinkolnR/china-real-state-regression-kaggle)
  — Neural network and deep learning project
- [Linguagem RPG](https://github.com/LinkolnR/LinguagemRPG)
  — Programming language implementation project

## Shipped

TypeScript · JavaScript · Python · SQL · React · FastAPI · REST · PostgreSQL ·
Docker · GitHub Actions · GCP · Capacitor

## Also used in coursework

C · C++ · C# · Jupyter · Classical machine learning

## What I am currently improving

- Building reliable AI-assisted features
- Designing clearer full-stack architectures
- Improving testing and observability
- Writing concise technical documentation
- Shipping small product iterations quickly

## Contact

[GitHub](https://github.com/LinkolnR) ·
[LinkedIn](https://www.linkedin.com/in/lincolnr-melo/) ·
[lincolnrpmelo@gmail.com](mailto:lincolnrpmelo@gmail.com)
