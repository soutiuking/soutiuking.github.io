# 霁泽入微工作室网页

这是一个可直接发布到 GitHub Pages 的静态主页。GitHub Pages 会读取仓库根目录下的 `index.html`。

## 绑定真实 GitHub 账号

打开 `index.html`，找到：

```js
const githubConfig = {
  owner: 'soutiuking',
  featuredRepos: [
    'HX711-load-cell-amplifier-module',
    'tof200c-st-api',
    'tof200c-self',
    'Wireless-debugging-tool',
    'Remote-controlled-wheelbarrow-cart'
  ],
  maxRepos: 5
};
```

当前绑定的 GitHub 用户名是 `soutiuking`，主页会优先展示 `featuredRepos` 中列出的 5 个仓库。

如果保持空数组，页面会自动展示该账号下最近更新的公开非 fork 仓库。

## 推送到 GitHub

第一次推送：

```bash
git init
git branch -M main
git add .
git commit -m "Initial studio website"
git remote add origin https://github.com/soutiuking/你的网页仓库名.git
git push -u origin main
```

后续更新：

```bash
git add .
git commit -m "Update website"
git push
```

## 开启 GitHub Pages

进入 GitHub 仓库页面：

1. 打开 `Settings`
2. 进入 `Pages`
3. `Build and deployment` 选择 `Deploy from a branch`
4. 分支选择 `main`
5. 目录选择 `/ (root)`
6. 保存后等待 GitHub 生成访问地址

公开仓库数据通过 GitHub REST API 在浏览器端读取，不需要手动更新页面。私有仓库不要把 token 写进前端页面里。
这就是一个普通的大学生在尝试使用 GitHub Pages 来展示他的项目。我对生活的理解是，生活是一个过程，而不是一个结果。
我通过这个项目，学习到了很多新的知识，也知道了如何使用 GitHub 来管理代码，可能这个项目做的不是很好，但是这是一个开始，我会继续努力，来完善这个项目。可能目前只是一个开始，后续我会持续更新和优化，学会如何脱离ai去管理这一个项目。我经常说的一句话就是少一点抱怨和多一些行动，干中学，学中干，这个也算是自己的一个博客，分享和记录自己的开发生活，很多其实都是很简单一些课设难度的小项目，可以给一些初学者去学习编写，工程的创建。
他的原始网页是我使用mimo进行创作的，因为我的经常开发的是嵌入式项目，并不是很会去写网页和前端，我的嵌入式开发的显示屏的界面设计也是直接去使用ai来完成的，我是一个艺术细胞很差的人，mimo创建的这个网页是我很喜欢的风格。源文件是code.html。
这个霁泽入微这个名字其实是我的嵌入式学习的想法，我们学习过程中在刚刚起步的时候，都是迷迷糊糊，只有一次一次的学习，霁泽也就是我们攻克问题后的那个时刻，入微就是我们成功解决了那个问题我们能够进行更近一步的学习。一起加油，嵌入式的学习是一件很漫长的路，没有一步登天，也没有功德圆满，都是我们慢慢学习的过程。