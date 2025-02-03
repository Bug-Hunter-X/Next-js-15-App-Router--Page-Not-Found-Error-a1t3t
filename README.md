# Next.js 15 App Router: Page Not Found Bug

This repository demonstrates a common bug encountered when using the Next.js 15 App Router: a page not found error despite having seemingly correct routing configuration.

## Bug Description

The issue arises when the App Router fails to locate a page, usually due to a mismatch in the file name, directory structure, or incorrect usage of layout components within the `app` directory.  This is different from traditional Next.js routing, and special attention must be paid to the conventions.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the error message, which should indicate that the page cannot be found, despite the presence of `pages/index.js`.

## Solution

The provided solution demonstrates correct file structure and page declaration, resolving the page not found error.
