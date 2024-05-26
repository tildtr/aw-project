## Context and Problem Statement
Microfrontend that allows to save products clients are interested in for later reference, necessitating a reliable and user-friendly feature for managing saved items. This functionality must allow users to easily save, view, and manage their saved meat products from various supermarkets.

## Decision Drivers
* User Engagement: Encourage users to return to the app by saving products they are interested in.
* Usability: Provide an intuitive and accessible way to save and review products.
* Performance: Ensure the saved products feature does not negatively impact the app performance.
* Data Persistence: Ensure that the saved products are stored reliably and persist between app sessions.

## Considered Options
1. Local Device Storage 
2. Cloud Synchronization Service 
3. Hybrid Storage Solution
   
## Decision Outcome
* Hybrid Storage Solution, because it provides a balance between offline access (local storage) and data persistence across devices.

### Consequences
* Good: Users can access their saved products even when offline.
* Good: User saved products are backed up in the cloud, allowing access across multiple devices.
* Bad: Increased complexity in managing data synchronization and conflicts.
* Bad: Potential increase in development and maintenance costs due to the dual nature of the system.
