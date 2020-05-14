# vue-welcome

This is a Vue element to show a custome modal before you enter some routed

## 功能设计

定义进入某个页面的时候 显示的欢迎页面

## 使用方法

```js
import VueWelcome from 'vue-welcome';
Vue.use(
  VueWelcome({
    container: '#welcome',
  })
);
```

## 选项

container :string
