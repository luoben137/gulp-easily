#gulp-easily

* 该项目仅仅是为了演示gulp的编译html,js,sass,image。
* 涉及到文件include，replace，版本控制等。

##使用
* 默认是不压缩代码的
* 如果需要修改build/config.js中isCompress=true
* 或者编译时传参 例如:gulp build --compress

### 插入依赖
npm install

### 编译并监视文件
npm run dev

### 编译文件
npm run build

##版本控制
* 没有找到一个好的版本控制插件，所以写了一个很简单的，有好的请留言。
* 该版本替换会吧生成的文件去计算md5值，可以很好的规避include的内容不被计算