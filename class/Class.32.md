# What makes an API RESTful?

- **Resource-Centric:** Resources are at the core, identified by URIs.
- **HTTP Methods:** Standard methods (GET, POST, PUT, DELETE) for actions.
- **Stateless:** Each request contains all necessary information.
- **Client-Server:** Separate entities that communicate through an API.
- **Uniform Interface:** Consistent, well-defined access to resources.
- **Representation:** Resources can have multiple data formats.
- **Layered System:** Internal system architecture is hidden.


# What is the benefit of using GraphQL? Any downsides?

## Benefits of GraphQL

- Precise Data Retrieval: Fetch only the data you need.
- Single Endpoint: Simplifies API architecture.
- Strongly Typed Schema: Clear data structure and validation.
- Real-time Data: Supports live data updates.
- No Versioning: Reduces API versioning needs.
- Flexibility: Front-end can tailor data requests.
- Aggregation: Combine data from multiple sources.

## Downsides of GraphQL

- Learning Curve: Can be complex for newcomers.
- Query Complexity: Inefficient queries can arise.
- Over-fetching: Suboptimal queries may still fetch too much.
- Security: Requires careful access control.
- Caching: Tricky to cache effectively.
- Tools: May have fewer libraries compared to REST.


# Describe “serverless” to a new 301 Code Fellows student.



Serverless is a cloud computing approach that simplifies application development. Instead of managing servers, you focus on writing small, specific functions. These functions run automatically when needed, and the cloud provider handles all the infrastructure stuff. You pay only for the actual usage of these functions. It's like ordering a dish at a restaurant without worrying about the kitchen details – you get what you want without managing the cooking process. Serverless is a hands-off, efficient way to build apps.
