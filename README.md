# ct-gulp-seajs-combo

***
> seajs(CMD) Module combo pulgin for gulp

## Install

```
$ npm install --save-dev ct-gulp-seajs-combo
```

## Usage

```
var gulp = require( 'gulp' ),
    seajsCombo = require( 'ct-gulp-seajs-combo' );
    
gulp.task( 'seajscombo', function(){
    return gulp.src( 'src/js/main.js' )
        .pipe( seajsCombo() )
        .pipe( gulp.task('build/js') );
}); 
```

## API

### seajsCombo( options )

add

moudles:root

//设置 node_moudles 真实路径 可在模块内使用 /node_moudles 来引用内容