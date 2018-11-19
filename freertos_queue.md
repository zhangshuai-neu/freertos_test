# FreeRTOS的Queue

### 队列功能

FreeRTOS的所有的通信和同步机制都通过队列来实现。

###　队列阻塞

1. 读取阻塞

队列为空的阻塞，等到队列内有数据或者超过了阻塞时间，任务会切换到ready状态。

哪个任务优先解除阻塞的任务？
优先级最高，或者同优先级的等待时间最长

2. 写入阻塞

队列为满的阻塞，


### 队列API

|函数|功能|描述|
|--|--|--|
|xQueueCreate|创建队列||
|--|--|--|
|--|--|--|