---
title: 梦
date: 2019-02-18 06:13:37
---

睡觉做梦，梦见换老板了。新老板随意看了看我以前写的code，问了很多问题，都一一给他解释了一翻。突然，老板发现有两个project里面有两个类似的函数，
都是在状态改变的时候会触发一个event。只是一个函数加锁了，一个函数没有。老板问，为啥这两个地方不一样呢？我扫了一眼说，可能一个地方的事件是异步触发的，
一个地方的事件是同步触发的。所以一个地方需要锁，一个地方不需要。老板仔细翻了翻代码，说没发现这个事件是同步的。

醒来后把梦里老板翻看的project找了出来。很老的code了，七八年前写的。仔细找出那段代码看了看，还真是缺一个锁。在某些情况下会有race condition。
应该是当时写的是候漏掉了，是个bug。

人的大脑真是一个神奇的东西。梦这种东西我觉得是神奇中的神奇。很多时候梦到的事情都不是真实发生的，但是真实感又特别强。很多时候，当你做某件事情的时候，
会有一种似曾相似的感觉。好像此情此景曾经梦到过。也有很多时候梦是反着的。梦中好事不断，现实中却恶运连连。关于梦是反的，好像听很多人都说过，应该不是孤例。

梦是怎么形成的？为什么么会梦到这些事而不是那些事？我相信至今科学上还没有给出令人信服的解释。关于脑科学人类还知之甚少。梦、意识、性格，
等等这些的成因和发展都还搞不清楚原因。也正是这样，才留给了我们巨大的想象空间。上初中那会儿和同班还有同年级几个要好的朋友都很迷恋《科幻世界》这本杂志。
这应当是当时中国唯一一本专门的科幻杂志了。也曾经脑洞大开，构思了一篇以梦为背景的科幻小说。在这篇小说里，因为梦的质量为零，所以它可以追上光，带你回到从前，
去到未来。也可以任意的在多维空间和平行宇宙间来回穿梭。你梦见的东西其实是在另一个平行宇宙另一个多维空间里真实发生的事情。

这篇小说后来被投给了《科幻世界》杂志，最后被无情的据稿:joy:。写这篇小说到现在已经快二十年了。这二十年发生了无数的变化。当年一起追着看《科幻世界》
的小伙伴们有些就一直再也没有联系。有些后来虽然有联系，却又不知为什么又断了联系。也许在另一个多维世界的平行宇宙里，这些小伙伴们仍然是在一起的好朋友吧。

二十年，弹指一挥间。梦依然如此神秘多婀，但我已不再年轻。很多事情已经注定了在我有限的人生中，只会在梦里发生。

人生如梦，一樽还酹江月。
