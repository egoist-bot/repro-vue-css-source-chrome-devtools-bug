# Repro

This project is created from `vue create` with only `Babel` as the selected feature.

0. Enable CSS source map, see [vue.config.js](./vue.config.js)
1. Run `yarn serve` and open it in Chrome
2. Right click on the text `Installed CLI Plugins` and try to add a new CSS rule like `color: red`:
![img](https://ws1.sinaimg.cn/large/006tKfTcgy1g1aihfqooxj31640fw7a0.jpg)
3. Then you will notice that `h3 {font-size: 4rem}` no longer takes effect.

![preview](https://user-images.githubusercontent.com/8784712/54741557-d2f93c80-4bf9-11e9-9dc8-4fa83acf6a70.gif)


