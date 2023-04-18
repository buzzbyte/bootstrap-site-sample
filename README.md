# Creaba - Bootstrap Sample Site
A simple Bootstrap-powered site made for Year Up's Learn To Code program.

Currently, this site only uses HTML and CSS. NPM is only used to download
bootstrap dependancies and spin up a convenient webserver to view the site.

## Installation
This project makes use of NPM to install dependencies and simple web server,
but you can also manually download and copy them.

**Using pnpm** (preferred method)
```bash
pnpm install
pnpm build

# run webserver
pnpm start
```

**Using yarn**
```bash
yarn
yarn build

# run webserver
yarn start
```

**Using npm**
```bash
npm install
npm run build

# run webserver
npm start
```

### Manually
1. Download the latest [Bootstrap 5.3](http://getbootstrap.com)
2. Create a folder called `dist` in the working directory
3. Extract the bootstrap zip file into the `dist` folder you just created and rename it to just `bootstrap`
   * Make sure there are no double directories (path to bootstrap css should be `dist/bootstrap/css/bootstrap.min.css`)
4. Run a local webserver on the working directory and visit the site
