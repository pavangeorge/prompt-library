# My Prompt Library

A personal collection of reusable prompts, organized by category.

---

## Coding — Convert HTML to Next.js Project

I have an existing HTML file that I want to convert into a Next.js project. Please help me with the following:

Set up a Next.js project structure (App Router) with TypeScript.
Convert my HTML into a proper Next.js page component (app/page.tsx), splitting reusable parts into separate components where it makes sense (e.g., Header, Footer, Navbar, etc.).
Convert inline/internal CSS into either CSS Modules or Tailwind CSS — [specify which you prefer].
Replace plain <img> tags with the Next.js <Image> component and <a> tags with the <Link> component where appropriate.
Move any JavaScript logic into React hooks/client components ("use client") as needed.
Keep all assets (images, fonts) organized in the public/ folder.
Tell me the exact commands to create the project, install dependencies, and run it locally.

Here is my HTML file:

*Added: 2026-06-12*
---

## Coding — Define API Contract for Frontend

Now that my Next.js frontend is set up, I need to define the API contract that the backend team will implement. Based on the data my frontend components consume, please produce only the API definitions and response structures — do not implement any backend logic, database code, or server setup.
For each endpoint, provide:

Endpoint definition — HTTP method, path (e.g., GET /api/users/:id), and a short description of its purpose.
Request structure — path params, query params, and request body schema (with field names, types, and whether required/optional).
Response structure — the success response body as a typed schema/JSON shape, including nested objects and arrays, with field names and data types.
HTTP status codes — expected success and error codes for each endpoint.
Error response structure — a consistent error shape (e.g., { error: { code, message } }).
TypeScript interfaces/types — matching the response structures so I can use them in the frontend.

Format the output clearly per endpoint. Use realistic example values where helpful. Keep it to definitions and schemas only — no controller code, no implementation.
Here are the frontend pages/components that need data:

*Added: 2026-06-12*
---