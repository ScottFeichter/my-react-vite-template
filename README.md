# My React Vite Template

Use it as a starting point.

## How To Clone

In desired directory run:

```sh
npx tiged https://github.com/ScottFeichter/my-react-vite-template.git react-vite-template
```

- This clones repo main branch in the directory where it is run.

## How To Track

From root run:

```sh
git init
git add .
git commit -m "initial"
```

- The .gitignore is already provided in the clone.

## How To Install

From root run:

```sh
npm install
```

## How To Run

From root run:

```sh
npm run dev
```

- This runs the `dev` script from your __package.json__ file.

- You will run this command whenever you want to start your app.

- To end the app press ctr + c in running shell.

## Running App

When it runs, you should see something like this in the terminal:

```bash
VITE v4.5.0  ready in 592 ms

  ➜  Local:   http://127.0.0.1:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```
- Might also read as `Local: http://localhost:5173/`

## Open Running App In Browser

[http://localhost:5173](http://localhost:5173)

- Or type `o` in running shell

  - You should see `Hello from App`

## Change Or Convert Files

__index.html__

- change `title`

__package.json__

- change `"name"`

__README.md__

- customize to the project

## Here is some info from the previous README.md

### React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
