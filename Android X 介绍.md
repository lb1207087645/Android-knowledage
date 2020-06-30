 # Android X 介绍
 阅读区

1.AndroidX 的来龙去脉？
    google为了向下兼容，使旧的android 系统也能使用新的API,提供了向下兼容库，
Android Support Library 等，
1.比如,4在这里指的是Android API版本号，对应的系统版本是1.6。
那么support-v4的意思就是这个库中提供的API会向下兼容到Android 1.6系统
2.appcompat-v7指的是将库中提供的API向下兼容至API 7，也就是Android 2.1系统。

     Android 团队意识到support-v4、appcompat-v7这种命名方式不合适，推出AndroidX，AndroidX 本质是对Android Support Library 进行的一次升级。

2.使用AndroidX 好处
     AndroidX 重新设计了包结构，旨在鼓励库的小型化，支持库和架构组件包的名字也都简化了；而且也是减轻 Android 生态系统碎片化的有效方式。

