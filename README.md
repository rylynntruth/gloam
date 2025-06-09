# Gloam Monorepo

This repository contains a minimal monorepo structure for a blog application
using **Next.js** for the web frontend and **NestJS** for the API backend.

## Structure

- `apps/web` – Next.js application
- `apps/api` – NestJS application

Both projects are managed using **Yarn** workspaces.

## Getting Started

1. Install dependencies for both apps from the repository root:

   ```bash
   yarn install
   ```

2. Start the applications in development mode:

   ```bash
   yarn dev:web   # starts the Next.js frontend
   yarn dev:api   # starts the NestJS backend
   ```

3. Build the applications for production:

   ```bash
   yarn build:web
   yarn build:api
   ```

This repository provides a simple starting point—you can extend each app
with additional pages, components, controllers and services to build your blog.
