### vue3 auth

#### how to mock data

- install mockjs and vite-plugin-mock --save-dev
- configure vite-plugin-mock in the vite.config.js
- make dir name 'mock'

#### how to standardize your code

##### use eslint

- install eslint
- npx eslint --init

##### use Prettier

- install perttier
- detail: https://www.prettier.cn/docs/install.html

**attention**

There will be conflicts between eslint and predictor，resolvent：

- add eslint-config-prettier(Close rules in eslint that conflict with prettier) eslint-plugin-prettier(The ability to allow eslint to format code with prettier
  ) -D

see: https://cloud.tencent.com/developer/article/2346141
