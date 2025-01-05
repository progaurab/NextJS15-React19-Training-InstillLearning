## Next.js App Router Course - Starter - https://nextjs.org/learn/dashboard-app
This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.


### Creating a new project
#### install npmp (as it is faster than npm and yarn)
```shell
$ npm install -g pnpm
```

#### create starting app using create-next-app
```shell
$ npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm

$ cd nextjs-dashboard
```
## Folder Structure

- **`/app`**  
  Contains all the routes, components, and logic for your application. This is where you'll be working most of the time.

- **`/app/lib`**  
  Contains functions used in your application, such as reusable utility functions and data fetching functions.

- **`/app/ui`**  
  Contains all the UI components for your application, such as cards, tables, and forms. These components are pre-styled to save development time.

- **`/public`**  
  Contains all the static assets for your application, such as images.

- **Config Files**  
  At the root of your application, you'll find config files like `next.config.js`. These files are created and pre-configured when you start a new project using `create-next-app`.


## Dependencies and Their Uses

### Dependencies
1. **`@heroicons/react`**  
   A library of free SVG icons designed for React. Useful for adding consistent and visually appealing icons to your application.

2. **`@tailwindcss/forms`**  
   A Tailwind CSS plugin that provides better default styling for form elements like inputs, selects, and buttons, making forms look more consistent and polished.

3. **`@vercel/postgres`**  
   A library to interact with PostgreSQL databases directly, optimized for serverless environments on Vercel. Perfect for integrating database operations in your Next.js app.

4. **`autoprefixer`**  
   A PostCSS plugin that automatically adds vendor prefixes to your CSS, ensuring compatibility across different browsers.

5. **`bcrypt`**  
   A library for hashing passwords securely. Commonly used for user authentication and securely storing passwords in the database.

6. **`clsx`**  
   A small utility for conditionally joining class names. Useful for dynamically applying CSS classes in React components.

7. **`next`**  
   The Next.js framework itself. Provides features like server-side rendering, static site generation, API routes, and more.

8. **`next-auth`**  
   A library to manage authentication in your Next.js app. Supports various providers like Google, GitHub, email/password, and custom credentials.

9. **`postcss`**  
   A CSS processor that transforms styles with plugins. Tailwind CSS uses it internally for processing your CSS.

10. **`react`**  
    The core library for building user interfaces in a declarative way.

11. **`react-dom`**  
    Provides DOM-specific methods for React. Used to render React components to the DOM.

12. **`tailwindcss`**  
    A utility-first CSS framework for building modern, responsive designs efficiently.

13. **`typescript`**  
    A superset of JavaScript that adds static typing, making your code more robust and less prone to errors.

14. **`use-debounce`**  
    A React hook for debouncing values or functions. Useful for improving performance in search inputs or API calls by reducing the frequency of executions.

15. **`zod`**  
    A TypeScript-first schema validation library. Useful for validating and parsing data, ensuring type safety.

---

### DevDependencies
1. **`@types/bcrypt`**  
   Type definitions for the `bcrypt` library, providing IntelliSense and type-checking in TypeScript.

2. **`@types/node`**  
   Type definitions for Node.js, helping with type safety and IntelliSense when working with Node.js APIs.

3. **`@types/react`**  
   Type definitions for React, ensuring proper type support for React components and hooks in TypeScript.

4. **`@types/react-dom`**  
   Type definitions for `react-dom`, enabling type safety for React's DOM rendering APIs in TypeScript.

---

### How These Work Together
- **Styling:**  
  `tailwindcss`, `autoprefixer`, and `@tailwindcss/forms` handle styling, ensuring modern and responsive designs.

- **Authentication and Security:**  
  `bcrypt` and `next-auth` handle secure password hashing and user authentication.

- **Database and Backend:**  
  `@vercel/postgres` integrates database operations seamlessly with Vercel.

- **React Ecosystem:**  
  `react`, `react-dom`, and `clsx` support the core UI functionality, while `@heroicons/react` adds icons.

- **Validation and Performance:**  
  `zod` ensures data integrity, and `use-debounce` optimizes performance.

- **TypeScript:**  
  `typescript` and related `@types/*` packages provide type safety and improved developer experience.

This setup offers a robust foundation for building a modern, scalable, and secure Next.js application.
