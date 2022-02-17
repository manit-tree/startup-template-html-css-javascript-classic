## Startup Template for Classic Web Development

This is a startup template for developer who develop web applicaiton in old style, where many JavaScript files are still imported via many script tag. This template comes with script for bundle JavaScript and CSS files.

## How to use

- clone this template
- move into folder
- run npm i [to install dependencies]
- run npm run sass:watch [make sass genrating css files automati when chaged]
- run live-server [to start development server]
- when ready to deploy, run npm build
- change script src to ./dst/index.js (the bundle file)

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
