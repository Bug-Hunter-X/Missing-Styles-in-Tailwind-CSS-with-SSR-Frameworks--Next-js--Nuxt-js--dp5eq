# Missing Styles in Tailwind CSS with SSR Frameworks

This repository demonstrates a common issue encountered when using Tailwind CSS with server-side rendering (SSR) frameworks like Next.js or Nuxt.js. The problem is characterized by missing styles, even when Tailwind classes are correctly implemented. This is often due to incorrect configuration of Tailwind's JIT (Just-In-Time) mode or issues with build processes.

The `bug.js` file shows a basic example with missing styles, while `bugSolution.js` provides a corrected version.  The core issue revolves around ensuring Tailwind properly processes your components during the build process.

## Setup

1. Clone the repository.
2. Install dependencies: `npm install`.
3. Run the application (instructions specific to the framework you're using will need to be added here, depending on whether we use next.js or nuxt.js).

## How to fix
Refer to the solution file, `bugSolution.js`, for correct implementation.