The screenshot below demonstrates the error handling implemented in the Student REST API. Here, a GET request was made to fetch a student by ID using an invalid MongoDB ObjectId format.

As designed, the API correctly responds with a 400 Bad Request status and returns a clear error message:

{ "error": "Invalid ID format." }

This ensures that users and developers can easily identify mistakes in their requests and handle them appropriately.# restapi-exp9-error-handling
