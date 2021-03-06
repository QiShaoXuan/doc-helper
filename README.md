# doc-helper

动态文档辅助器

## 需求

如何使一个组件容易推广，让更多人使用。

当我们历尽艰苦（实力不行）的开发出一个（自认为很好用的）组件时，却发现使用者寥寥，并非是他们不想用，而是阅读一大篇 README 真的十分心累，除非强制要求，不然基本不想考虑。

而因为业务需求，我开发组件有一很多配置项是暴露给产品同学进行下发配置的，那么如何让一个不懂开发的产品更好更方便的配置出一个他想要的组件形式呢？

其实使用者只是想快速的复制粘贴一下就能直接使用自己需要的组件和想要的配置，而不是先看组件说明，再研究组件 API，最后发现其实并不支持他想要的效果。

## 为什么不是 [react-docgen](https://github.com/reactjs/react-docgen#readme)

对于一个底层开发来说，实力还不允许我在写组件的时候就已经想好暴露的 API ，并能够在开发中想好类型写全注释，而懒惰也阻止了我在开发结束后一行一行的按照规定方式去补充注释，并且我更希望的是能够将组件的 API 与对应的 UI 形式完整的暴露出来，而非对着 README 去想象。




