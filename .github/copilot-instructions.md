# Custom Copilot Instructions for Kayrzex's Personal Website

## Project Overview
You are assisting in the development of Kayrzex's personal website. This website is being built using the following technologies:
- **Astro (v5.x)**: A modern web framework for building fast, content-focused websites.
- **Tailwind CSS (v4.x)**: A utility-first CSS framework for styling.

## Project Goals
The website should:
1. Showcase Kayrzex's portfolio, skills, and projects.
2. Include a personal blog where posts can be published.
3. Be highly performant, accessible, and responsive across devices.
4. Feature a clean, minimalistic, and modern design aesthetic.

## Development Guidelines
- **Astro**:
  - Use Astro's file-based routing for pages.
  - Components should be modular and reusable, following Astro's component conventions.
  - Leverage Astro’s support for partial hydration and server-side rendering where applicable.

- **Tailwind CSS**:
  - Utilize Tailwind's utility classes for styling.
  - Follow a consistent design system, using custom colors, spacing, and typography defined in the Tailwind configuration.
  - Use Tailwind plugins when necessary (e.g., typography and forms plugins).

- **Responsive Design**:
  - Ensure the website looks and works great on mobile, tablet, and desktop devices.
  - Use Tailwind's responsive utilities to handle breakpoints.

- **Accessibility**:
  - Follow accessibility best practices (e.g., ARIA roles, semantic HTML).
  - Ensure the site passes an accessibility audit using tools like Lighthouse.

- **Performance**:
  - Optimize images, fonts, and other assets for fast load times.
  - Use Astro’s built-in optimization features and lazy-loading where feasible.

## Features to Implement
1. **Homepage**:
   - Include a hero section with a brief introduction and a call-to-action.
   - Display key projects or sections (e.g., portfolio, blog posts, about).
2. **Portfolio Page**:
   - Showcase Kayrzex's projects with descriptions, screenshots, and links.
3. **Blog**:
   - Support Markdown/MDX for writing and formatting blog posts.
   - Add a blog index page to display blog posts with metadata (e.g., title, date, tags).
4. **About Page**:
   - Include a personal bio, skills, and contact information.
5. **Contact Form**:
   - Use a simple form for visitors to send messages (can integrate with email or a serverless function).

## Coding Style
- Write clean, readable, and maintainable code.
- Use descriptive names for components, variables, and classes.
- Follow Tailwind's convention of grouping related utilities logically.
- Comment where necessary to clarify complex logic.

## Copilot Interaction
- Prioritize generating Astro components and Tailwind-based styling.
- Suggest accessible and responsive design patterns.
- Generate Markdown/MDX snippets for blog posts where relevant.
- Assist in debugging or optimizing Astro templates and Tailwind CSS configurations.

## Deployment
- The website will be deployed using a modern hosting platform (e.g., Vercel, Netlify).
- Ensure the site is production-ready, with all build errors and warnings resolved.

By following these instructions, you will help create a fast, beautiful, and functional personal website for Kayrzex!