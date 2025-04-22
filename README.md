# NextJS Template

A modern Next.js template with Shadcn UI components and Markdown support.

## Features

- Next.js 15.3.1
- Shadcn UI 2.4.1
- Markdown support
- Modern UI components
- Responsive design

## Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn

## Quick Start

1. Fork this repository
2. Update project name in `package.json`
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Setup

### Next.js Setup

This project was created using:

```bash
npx create-next-app@latest
```

### Shadcn UI Components

The following Shadcn UI components are included:

```bash
npx shadcn@latest add accordion alert alert-dialog aspect-ratio avatar badge breadcrumb button calendar card carousel chart checkbox collapsible command context-menu dialog drawer dropdown-menu form hover-card input input-otp label menubar navigation-menu pagination popover progress radio-group resizable scroll-area select separator sheet sidebar skeleton slider sonner switch table tabs textarea toggle toggle-group tooltip
```

### Markdown Support

Note: There is a known issue with Turbopack and MDX integration. The project is currently using Webpack configuration.

### UIBeats Integration

This project integrates with UIBeats for enhanced UI components and design patterns:

- Visit [UIBeats](https://www.uibeats.com/) for more information
- Components can be easily copied and pasted into your project

## Development

### Running the Development Server

```bash
npm run dev
```

Note: You might see the following warnings:

```
⚠ The config property `experimental.turbo` is deprecated. Move this setting to `config.turbopack` as Turbopack is now stable.
⚠ Webpack is configured while Turbopack is not, which may cause problems.
```

For Turbopack configuration, refer to the [Next.js documentation](https://nextjs.org/docs/app/api-reference/next-config-js/turbo).
