
### vue cli

脚手架可以帮开发人员写好基础代码

vue cli 做了这些：目录结构，本地调试，代码部署，热加载，单元测试

npm install -g

### 代码结构

static/.gitkeep   --即使static目录为空也可以将static目录提交到git仓库，通常git会忽略控文件

.babelrc -- babel将ES6编译成ES5的配置

-- presets  预设 转换预先需要安装的插件
-- plugins  
-- comments :false 

.editorconfig --编辑器的配置
.eslintignore --忽略语法检查的目录文件
.eslintrc  --eslint的配置文件
-- extends ：规则
-- rules :对部分规则做修改，比如编译不通过的规则可以配置成0,

index.html --没有任何资源，在编译过程中会自动插入到index.html中

package.json 
scripts:配置脚本

devDependencies:编译过程中需要的依赖

### 代码如何运行

main.js 入口文件

单文件组件是全局注册还是局部注册？

