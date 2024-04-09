## Context and Problem Statement
Host application capable of integrating various microfrontends. 

## Decision Drivers
* Consistency: Users should have a unified experience across all microfrontends.
* Performance: The host application must load microfrontends quickly and manage resources effectively.
* Flexibility: It should be easy to add, update, or replace microfrontends without significant downtime or rework.
* Scalability: The host must handle increased load as the app grows in popularity.

## Considered Options
1. Use Single Page Applications
2. Use Server-Side Rendering
3. Mix of SPA and SSR (Hybrid Approach)

## Decision Outcome
Hybrid approach in order to leverage the benefits of both architectural patterns. 

### Consequences
* Good: The initial load is fast, improving the perceived performance of the app.
* Bad: Additional complexity in development and deployment, requiring both server-side and client-side expertise.
