# Starter gulpfile.js for Front-End Development
This is a common, reusable Gulp file tailored towards front-end focused projects. It can be used as-is or customised to fit your development environment.

## Features
| Features          | NPM Modules                                              |
| ----------------- |--------------------------------------------------------|
| General           | [Util](https://www.npmjs.com/package/gulp-util), [Changed](https://www.npmjs.com/package/gulp-changed), [Run sequence](https://www.npmjs.com/package/run-sequence), [Del](https://www.npmjs.com/package/del) |
| Sass `sass`       | [Libsass](https://www.npmjs.com/package/node-sass), [Autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer), [CSS Nano](https://www.npmjs.com/package/gulp-cssnano), [Sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps), [Combine media queries](https://www.npmjs.com/package/gulp-combine-mq), [Clip Empty Files](https://www.npmjs.com/package/gulp-clip-empty-files) |
| JavaScript `js`   | [Uglify](https://www.npmjs.com/package/gulp-uglify) |
| Images `img`      | [Imagemin](https://www.npmjs.com/package/gulp-imagemin) |

## Getting Started
1. Clone the project / Download the zip.
```
git clone git@github.com:JakeCobley/gulpfile.js.git projectname
```
2. Navigation to the working directory
```
cd projectname
```
3. Install npm modules
```
npm i
```
4. Update variables, folder names and file paths at top of the gulpfile.js file to suite your project.

## Gulp Tasks
* `$ npm run default` - Default task, builds assets and watches directories for changes.
* `$ npm run default-dev` - Same as above, but with added dev tools enabled (Sourcemaps, browserSync etc).
* `$ npm run build` - Builds all assets.
* `$ npm run build-production` - Builds all assets in production format (Minified etc).


# Example Project Structure
*This can be easily changed to suit your project.*
```
+-- dist/
|   +-- css
|   +-- js
|   +-- img
+-- src/
|   +-- scss
|   +-- js
|   +-- img
+-- node_modules/
+-- package.json/
+-- gulpfile.js/
```

## License
The MIT License (MIT)

Copyright (c) 2015 Jake Cobley

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
