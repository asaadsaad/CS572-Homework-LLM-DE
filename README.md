### CS572-Homework-LLM
 
Build an AI Agent using TypeScript and the OpenAI Response API that manages a user’s todos with date awareness and natural language date handling. 
Available Functions:
* `addTodo(dateInput: string, text: string): string` Add a todo for a specific date (supports `"today"`, `"tomorrow"`, or `"MM-DD-YYYY"`).
* `getTodos(dateInput: string): string[]` List all todos for a given date.

Requirements:
* Use in-memory storage to maintain todos organized by date.
* Detect user intent to add or list todos and call the correct function automatically.
* Accept both natural language dates ("today", "tomorrow") and explicit US format ("MM-DD-YYYY").
* Provide clear responses for each action (confirmation or list output).
* Handle invalid inputs gracefully (missing date or todo text).
* Support multiple consecutive interactions without losing in-memory context.
* Test the implementation through the CLI.
* Create an Express web server and expose API endpoints for your logic
* Create a JWT login based system (backend + frontend)
   * Save the application state as a signal in a service
   * Protect routes with Guards
   * Intercept all HTTP Client requests and add the token to all outgoing requests
* Use Angular's Resource API with the `stream` option
  
