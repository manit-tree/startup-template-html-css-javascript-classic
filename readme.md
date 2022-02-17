## Startup Template for Classic Web Development

This is a startup template for developer who develop web applicaiton in old style, where many JavaScript files are still imported via many script tag. This template comes with script for bundle JavaScript and CSS files.

## How to use

clone this template
```
git clone https://github.com/manit-tree/startup-template-html-css-javascript-classic.git
```

move into folder
```
cd startup-template-html-css-javascript
```

install live server (globally) or use liver server extention in your VS Code

```
npm i -g live-server
```

install dependencies
```
npm i
```

start watching css and scss files
```
npm run sass:watch
```

start live server
```
live-serever
```

bundle everything when ready to deploy
```
npm run build
```

change src or your script tag to the bundle file
```
<script src="/dist/index.js"></script>
```

## Scripts

- **npm run sass** [bundle all css files - for development]
- **npm run sass:watch** [bundle all css files automatically when aynthing chages
for development]
- **npm run build** [bundle all javascript and css files - for production]

## NPM Package References

- **sass** [sass compiler]
- **uglify-es** [use for bundling javascript files]
- **rimraf** [use for clean up files and directory]
- **concurrently** [allow running multiple command in one script]
