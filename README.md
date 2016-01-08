CSS is handled by Less.


Compile Less source files into min CSS

  lessc app/css/main.less dist/css/styles.css

To watch file and autocompile, use: https://github.com/jonycheung/deadsimple-less-watch-compiler

  npm install -g less-watch-compiler

Then watch main.less file:

  watch-run -p 'app/css/*.less' npm run less
