# [Havefive](https://havefive.github.io)

## 前言

前端高能。。。定个小目标，力求逐步完善自己的前端知识体系，也希望对大家有所帮助。

如果你也有类似的想法或者不一样的见解，可以提PR或issue啊。

做了前端3年，经常看到别人分享的，自己总有些经验和体会，这里也分享一下，总结些别人没有的，比如前端工作职位、面试、技术实践等等。


## 主要内容

* 1.解读和分析常见前端岗位岗位职责和岗位要求
* 2.剖析常见前端面试题。
* 3.解读分析常见前端技术问题。

注：前端岗位主要来源Google,Apple,阿里巴巴,腾讯等大公司的招聘要求。分析时会举例和动手实践来阐述。


### 岗位职责类

1. 优化客户端页面代码的性能

```
解答：这个是前端的常见工作内容之一，指优化现有前端页面，为了让用户访问起来更快，和交互更加友好。
面试官常常会问怎么去优化前端的页面，雅虎曾提出来前端优化十四条规则，这里可以结合自己的实践来进行回答。
```
2. 解决不同浏览器和不同版本的兼容性问题

```
解答：这个是前端工作面临的主要问题之一，指让前端页面兼容用户使用的不同浏览器，熟悉各种浏览器平台的特性，这里可以谈一下怎么避免发生和解决问题。可以结合自己解决的来进行回答。
```
3. 协助设计师实现页面及交互，协助研发完成前后端合并

```
解答：前端工作是一份承前启后的工作，前面配合设计师实现页面和交互，后面协助服务端完成前后端合并，完成数据交互和展现。所以做好前端工作需要很好的沟通和合作能力，需要与各种背景的人进行通力合作。
```
4. 不断学习研究新的技术，并能迅速转化到潜在项目中。

```
解答：前端的技术发展相对比较快的，从nodejs出现后发展更是非常迅猛，而且有很多都开源共享了，比如angular,vue,react等等,有空就需要学习，而且它们本身也在不断迭代，不要老看热闹，要去使用，去做项目才能发现它们真正能解决的问题和优化了什么，当然也存在一定的坑，多去github上提提pr,与大牛们一起完善，相信会学到很多。
```
5. 对开源项目或行业有输出和贡献者优先
```
解答：近年来前端领域在开源方面很突出，github上大概有五分之二的项目是前端相关，所以是提高自己和发挥自己的好去处。这个岗位需求需要自己在github上活跃，对近段时间的比较热火的前端框架、项目、类库有自己的贡献和反馈，比如多提pr,多解决些issue等等，目前来看reactjs,vuejs,angularjs2.0，weex,小程序比较热门和常用。
```
6. 在理解前端开发流程的基础上，结合前端实际建立或优化提升工作效率的工具
```
解答： 我们知道程序员经常加班，除了任务繁多，项目紧急，开发流程和开发效率也是比较耗时耗精力的部分，如果调整或优化工作流程，有好用的开发工具，那前端工作会轻松不少，我们可以花一些时间改善开发流程和提炼方法工具，减轻自己和团队的工作量和提高效率。
```
### 岗位要求类

1. 有大型网站开发经验

```
解答：怎样的网站是大型网站，可以基于访问量和页面复杂度等指标来阐述，也许访问量国内排名500名以内，才算吧。
```

2. 熟悉http的工作原理

```
解答：这个必须的，面试也常被问到：http/https的原理是什么？http2是什么。
```
3. 区分对技术的了解/熟悉/掌握
```
解答：它们的区别是什么呢？举个例子，了解相当于知道1+1=2，熟悉相当于1+1+1=3，掌握相当于知道1+1是因为十进制加法才等于二，二进制加法不会等于2，而是等于10.所以对技术来说，了解的程度相当于知道可以做什么，熟悉相当于运用于实践，掌握相当于明白原理，知根知本。

常见岗位要求：对流行的前端技术有深刻理解；
```
4. 能够写原生组件，对前端工程化与模块化开发有一定了解，并有实践经验

举个例子：
console.log('hello'.repeatify(3));要求打印hellohellohello
```
String.prototype.repeatify = String.prototype.repeatify || function(times){
  var str = '';
  for(var i = 0; i < times; i++){
      str += this;
  }
  return str;
};

```

5. 最近学习了什么

* react ,参考https://github.com/havefive/react-tmpl
* ant-design
* mobile-ant-design
* weex
* vue，参考https://github.com/havefive/vue-teml
* next.js
* 小程序,参考https://github.com/havefive/xiaochengxu

6. 学习渠道
* 站点：github,stackoverflow,掘金,阿里云,codepen,segmentdefault,开源中国,dribble...
* 论坛：云栖大会，d2,alloyteam,segmentdefault,开源中国...
* 技术大牛的博客、微信文章等等

7. 相关能力
```
希望你能够快速响应和解决各类移动端疑难问题。
并能够带动身边的人一起进步。
```

8. 熟练或精通一种编程语言（如：Node.JS／Java／PHP） 
```
前后端分离的情况下，前端免不了和后端进行数据交互，如果会一种或多种倒是不错的，
```

### 面试题目类

1. sessionStorage 和 localStorage
2. css 动画 和 js 动画
3. 对前端工程师（Front End Engineer）工作的理解
4. CSS 的垂直居中 参考http://gold.xitu.io/post/582c04032f301e00594327d4
5. 学习前端的几本书籍《编写可维护的Javascript》，《图解HTTP》，《Javascript设计模式与开发实践》，《Web前端开发最佳实践》，《技术之瞳》等等

