# Node Angular Seed

Another MEAN seed app with Webpack

## Tools
- Angular (ES6)
- Express
- Webpack
- Gulp
- SASS
- Karma (Jasmine/Chai)

## Setup

For development tools and building:

1. Install the latest [Node.js and NPM](https://nodejs.org). This config is built with Node V6.2.0.
2. Run `npm install` within the project root directory in Terminal.
3. Change directory `cd ./public` and run `npm install ` again for the client side dependencies.
4. Back to project root `cd ../`
5. Run `npm start:dev` to start the server.
6. Run `npm run build:watch` to run webpack and watch for changes.
6. Run `npm test` to run Karma tests and watch for changes.
7. Run `gulp build:watch` to process our stylesheets. Webpack also sees there changes and modifies the bundle.

## Structure

- `/public/components` contains a sub-directory for each component, holding source JS, styles and views.
- `/public/dist` is the directory for compiled JS and CSS
- `/.config/.env` stores global variables for the server

## Scripts

| Command               | Purpose                                              |
|:----------------------|:-----------------------------------------------------|
| `npm run clean`       | Delete `/public/dist/*`.                             |
| `npm run build`       | Compile JS and CSS to `/public/dist/bundle`.         |
| `npm run build:watch` | Build, rebuilding on source file changes.            |
| `npm run start:dev`   | Start the server, restarting on source file changes. |
| `npm start`           | Start the server.                                    |
| `npm test`            | Start Karma testing watching for file changes.       |

Developed by [Jimmy Cann](mailto:mail@jimmycann.com) and licensed under MIT.
