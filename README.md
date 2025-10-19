# MerchantHaus website

This repository contains the source code for the **MerchantHaus** website.
The site is built with **React**, **TypeScript**, **Vite**, and
Tailwind CSS (via [shadcn/ui](https://ui.shadcn.com/)).  A custom 3D
carousel is used to highlight the services MerchantHaus offers to its
customers.  All Lovable‑specific content from the original scaffold
has been removed so that this project stands independently.

## Getting Started

To work with this project locally you will need an up‑to‑date
installation of **Node.js** and **npm**.  Once those tools are
installed, clone the repository and install dependencies:

```sh
git clone <REPO_URL>
cd <PROJECT_DIR>
npm install
```

Start a local development server using Vite:

```sh
npm run dev
```

This will serve the application at a local address such as
`http://localhost:5173`.  As you edit the source files the browser
will reload automatically.

## Building for Production

To create an optimised production build run:

```sh
npm run build
```

The compiled assets will be written to the `dist/` directory.  You can
use `npm run preview` to serve the production build locally for
testing.

## Directory Structure

```
.
├── public/            # Static assets served at the root (favicon, placeholder images)
├── src/
│   ├── components/    # React components including the 3D carousel
│   ├── pages/         # Top‑level pages such as the homepage
│   ├── assets/        # Local images used by the components
│   └── index.css      # Tailwind import and global styles
├── index.html         # HTML template used by Vite
└── package.json       # Project metadata and scripts
```

## Technologies Used

- **React** for building the user interface
- **TypeScript** for type safety
- **Vite** for tooling and local development
- **Tailwind CSS** and **shadcn/ui** for styling
- **Embla carousel** for the 3D slider functionality

## Contributing

Feel free to fork this repository and submit pull requests.  When
contributing please ensure that your changes are tested locally and
that you follow the existing project coding style.

## License

This project is provided without any specific license.  Please
contact the repository owner if you wish to use this code for
commercial purposes.