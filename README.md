# Next.js 15 App Directory - Unexpected Behavior with Default Export in Pages Directory

This repository demonstrates an unexpected behavior in Next.js 15's App Directory when using a default export in a file within the `pages` directory.  The issue is that the default export is not correctly recognized and may lead to an error or unexpected rendering.

## Issue Description

In a Next.js 13 app, having a default export in a file under `pages` would correctly render the component. However, in a Next.js 15 app directory, this approach may not function as expected.  The application might throw an error or simply not render the component.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior.

## Solution

Instead of using default export, utilize a named export, as shown in the `bugSolution.js` file.