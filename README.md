# Android-Handler
Android Handler 消息处理机制 Looper, MessageQueue,Message 

几个要素：

消息的表示：Message

消息队列：MessageQueue

消息循环，用于循环取出消息进行处理：Looper

消息处理，消息循环从消息队列中取出消息后要对消息进行处理：Handler

Handler中分发消息的一些方法

post(Runnable)

postAtTime(Runnable，long)

postDelayed(Runnable long)

sendEmptyMessage(int)

sendMessage(Message)

sendMessageAtTime(Message，long)

sendMessageDelayed(Message，long)

以上post类方法允许你排列一个Runnable对象到主线程队列中，

sendMessage类方法， 允许你安排一个带数据的Message对象到队列中，等待更新。



