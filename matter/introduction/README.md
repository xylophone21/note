# Matter简介及准备工作

工作的原因，大概从今年(2021）1月就开始关注Matter。各种原因一直只下载了一份规范文档在啃，直到6月份，Apple在WWDC上发布了这么一个视频，我感觉应该是时候深入了。

https://developer.apple.com/videos/play/wwdc2021/10298/

一句话说，就是Apple在HomeKit里计划用下图这样的方式实现Matter，并且计划在21.9月iOS15发布时，就抢跑发布。之所以说是抢跑，是因为彼时Matter的发布计划还是22年1月。当然现在这个计划以及延迟到明年4月了。后来也尝试过在iOS15上给Matter添加Matter的设备，确实是6月份的一个版本，基本能跑，因为和最新的版本差异较大，又不支持我们关注的放心，就没有深入。

从这张图及视频不难看出，对于用户及App开发者来说，在iOS上，Matter设备基本上与HomeKit设备一致，只是设备端的认证更灵活，一次认证，可以支持更多的控制端。

![Apple Arch](./apple_arch.png)
