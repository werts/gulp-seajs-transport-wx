gulp-seajs-transport-wx
=======================

基于gulp的插件，用于对seaj模块进行transport

##感谢 and Note
本插件在[gulp-seajs-transport](https://github.com/guilipan/gulp-seajs-transport)的基础上进行了修改，对原作者表示感谢


## install
$ npm install --save-dev gulp-seajs-transport-wx

## Usage

```
const transport = require('gulp-seajs-transport-wx');
const gulp = require('gulp');

gulp.task('default', () => {
    return gulp.src('*.js')
        .pipe(transport())
        .pipe(gulp.dest('.dest'));
});

```

## License

MIT