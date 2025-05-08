# Node.js Simple Server
This repository contains examples of simple Node.js servers for learning purposes. Each example demonstrates basic server functionality, routing, and handling HTTP requests.

### EX-2: Basic Routing
- File: `EX-2/server.js`
- Demonstrates basic routing with `GET` requests.
- Routes include:
  - `/` - Home Page
  - `/about` - About Page
  - `/contact-us` - Contact Us Page
  - `/products` - Products Page
  - `/projects` - Projects Page
  - Any other route returns a `404 Not Found`.

### EX-3: Handling Form Submissions
- File: `EX-3/server.js`
- Demonstrates handling `GET` and `POST` requests.
- Features:
  - A simple form at `/contact` for submitting names.
  - Saves submitted names to `submissions.txt`.
  - Validates input and handles errors gracefully.
