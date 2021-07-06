## 代码规范
eslint + prettier
1. npm install prettier -D
在项目根目录新建`.prettierrc`，进行规则配置
2. npx eslint --init 创建eslint规则文件
3. npm i eslint-plugin-vue -D

### 解决eslint 与 prettier 冲突的规则
4. eslint-plugin-prettier
5. eslint-config-prettier
> eslint-plugin-import

## git提交规范
1. git init
2. npx husky-init && npm install
3. npx lint-staged
4. commitlint
4.1 npm install --save-dev @commitlint/{config-conventional,cli}
4.2 echo "module.exports = {extends: ['@commitlint/config-conventional']}" > commitlint.config.js
4.3 npx husky add .husky/commit-msg 'npx --no-install commitlint --edit "$1"'
> 自定义 commitlint 的 type: [自定义type](https://github.com/commitizen/cz-cli)

husky git钩子

## 安装Ant-design-vue 
npm install ant-design-vue@2 -S

## 安装Vue-router
npm i vue-router@4 -S
