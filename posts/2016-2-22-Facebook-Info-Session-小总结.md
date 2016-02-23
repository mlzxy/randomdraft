## Facebook info Session 听后总结

很受用， 把一些自己记下的，有用的东西放在这里。


### 演讲者

演讲者很善于化解场上突发情况，风格很值得自己借鉴。

- slide中的一个视频由于投影机原因只能看到一半，换做自己可能会有点着急，甚至会尝试解决电脑的配置问题。 但演讲者以开玩笑而风趣的口吻说：

   *你们应该能想象到那里有一些各种各样的按钮。*

   显然是更棒的演讲能力。

- 另外演讲中提问题，扔礼物，这是不错的技巧。



### Tech Talk 中心

Tech Talk 的中心是介绍了FB在一下两点的不断改进和提升（两点是用户体验的关键）：

- Time to Interaction 
- Scroll Time

其中FB体现的把事情做好做精，积极反馈用户的精神很值得钦佩，或许也侧面体现了国外技术公司比国内在整体风气上的领先。



### Time to Interaction

指的是用户从打开app需要多久才能和app有交互（真正使用）。


Facebook发现，大部分fb mobile app用户都是短时多次，经常打开app，但一次可能不到1min，因此 **Time to Interaction** 至关重要。
涉及到的一些内容有

- 对于 GraphQL 的搜索优化（减少传输没用的数据，同时也节约了Battery Life）
- UI渲染的加速，让多个UI Widget一起渲染啥的
- Cache
- 抛弃了Html5 Hybrid App（曾经Facebook是Hybrid App）


### Scroll Time

Scroll 是最常用，也最容易出现性能瓶颈的地方（大列表）， 涉及到的内容有

- 通过底层Virtual Dom来估计计算UI Layout，之后一次性布局， 而不是一边UI渲染，一边读取UI的Pixel Value。




### Other

在演讲中介绍了很多facebook内部的开发工具，他说这些工具的巨大意义在于 *use tools to decrease the communication between people*, 
这样极大提高了效率。


这个原则感觉很赞。

 
当然演讲中还有其他内容，不太重要就没有记在这里。



