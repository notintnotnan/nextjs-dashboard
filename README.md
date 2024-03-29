## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Course Chapters

### Chapter 1 - Intro

- Initialized the project by copying the example from an URL.
- Installed libraries running _npm i_.
- Initialized the git repo (had to delete the .git folder and run _git init_ from scratch).
- Pushed the master branch upstream of the remote to start GitHub management.

### Chapter 2 - Styling

- Imported global.css file into app/layout.tsx to inherit styles to the whole app.
- Created a CSS module (_home.module.css_) to style a div within app/page.tsx (black tringle).
- Learned about the _clsx_ library for conditional styling (example at app/ui/invoices/status.tsx).

### Chapter 3 - Optimizing fonts and images

- Used _next/font/_ folder to import fonts and store the into a .tsx file (/app/ui/fonts.tsx) for later use.
- Used the **Image** component from _next/image_ to render image components optimally.

### Chapter 4 - Layouts and Pages

- Explored nested routing by creating the app/dashboard folder and adding a page.tsx file in it.
  - Did the same with the app/dashboard/customers and app/dashboard/invoices folders.
- Explored the layout functionality and partial rendering by creating the layout.tsx file within the app/dashboard dir.
- Saw the effect of using the **RootLayout** function within a layout file.

### Chapter 5 - Navigating withing pages

- Replaced default a tags in _/app/ui/dashboard/nav-links.tsx_ for Link tags imported from _next/link_ to avoid full page rendering while navigating.
- Applied the _use client_ directive to the same component to allow the usage of hooks to display active link (using clsx and usePathname hook).
