# Next.js 15 App Router Blank Page Bug

This repository demonstrates a bug encountered in Next.js 15's App Router where a page fails to render, resulting in a blank page.  The issue is related to a missing or incorrectly configured component within the app directory structure.

## Bug Description

When navigating to the home page, a blank page is displayed instead of the expected 'Hello World!' message. This occurs despite seemingly correct setup of the page component.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the Next.js development server.
4. Navigate to `http://localhost:3000`.  A blank page will be displayed.

## Solution

The solution involves ensuring that the `app` directory is structured correctly and that the necessary component is exported correctly.