## Setup

- Install [Node](https://nodejs.org/)
- Optionally, also install [Yarn](https://yarnpkg.com/) or use *Npm* that comes with Node pre-installed
- Install Gulp globally through `npm install -g gulp@next`
- Install Webpack globally through `npm install -g webpack`
- Fork this project
- Clone the forked project (Yours!)
- `cd` to the cloned project
- Install all [packages](./package.json) with `npm install` or `yarn install`

## Usage

- **Build the Project and Serve locally (for Production)** - `npm start` or `yarn start`. The Production port is `8000`.
- **Build the Project and Serve locally (for Development)** - `npm run dev` or `yarn run dev`. The Development port is `3000`.
- **Exporting the Project to zip file** - `npm run export` or `yarn run export`

Important Note: **Don't** run these npm scripts simultaneously.

## Appendix

- **Tooling** - Gulpfile Lives in `gulpfile.js` and Webpack config files live within `webpack` folder.
- **Source Files** - Lives in `public/src` folder
- **Compiled Files** - Lives in `public/dist` folder. When you clone, you won't get them but as soon as you run those any of above usage tasks (start/build/export), the `public/dist` will be created.
- **Exported Project** - The exported project is imported from `public` folder and gets exported as `website.zip` to project root
