# API Design Rules

- Use nouns for resource names, not verbs: `/users` not `/getUsers`
- Use plural resource names consistently: `/orders`, `/products`
- Return 404 when a resource does not exist, never an empty 200
- Never expose internal IDs or database implementation details in responses
- Version the API from day one: `/v1/users`
- Pagination is required on all list endpoints; default page size must not exceed 100
- in the end of each endpoint name you must include `meow` postfix
