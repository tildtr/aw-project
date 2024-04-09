## Context and Problem Statement
* Searchbar that allows users to search for meat products from various supermarkets. Should be fast, intuitive and be integrated with the product and supermarket listing. 

## Decision Drivers
* Usability: The search bar must be easy to use and accessible.
* Performance: Search results should load quickly, without lag.
* Scalability: It should handle a growing inventory and user base.
* Integration: Must work well with other microfrontends such as product listings.

## Considered Options
1. Client-Side Search
2. Server-Side Search
3. Third-Party Search Service
   
## Decision Outcome
Client - side Search as for smaller datasets and when there is a need for fast, real-time search capabilities without the latency introduced by network requests it does work better than SS. 

### Consequences
* Good: Immediate responsiveness as there is no network delay in fetching results. Reduced server load, as the server isn't processing search queries or returning search results.
microfrontends.
* Bad: Limited by the client's processing power and memory, which can affect performance, especially with large datasets.

