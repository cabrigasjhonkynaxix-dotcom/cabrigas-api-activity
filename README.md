Markdown
# RESTful API Activity - Jhon Kyn Axix H. Cabrigas
## Best Practices Implementation
**1. Environment Variables:**
 -Why did we put `BASE_URI` in `.env` instead of hardcoding it?
    -Answer: This is to avoid repetition. 

**2. Resource Modeling:**
 - Why did we use plural nouns (e.g., `/dishes`) for our routes?
    - Answer: Because we are referring to more than one of that item. This is to ensure precision and avoid confusion for directions.

**3. Status Codes:**
 - When do we use `201 Created` vs `200 OK`?
    - Answer: We use 201 Created when a request successfully creates a new resource, while 200 OK is for general success where no new resource is created.

 - Why is it important to return `404` instead of just an empty array or a generic error?
    - Answer: This preserves the semantic meaning of the API, which this will indicates that the resource was nowhere to be found.
**4. Testing:**
    - (Paste a screenshot of a successful GET request here)