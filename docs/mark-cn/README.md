Apache RocketMQ 持续源码解析
--------
##### 持续更新优化

### 0.组件关系

### 1.IO-网络
    1.1网络层的抽象
    1.2网络包数据结构
    
### 2.IO-文件
    1.MappedFile
    2.CommitLog
    3.ConsumeQueue
        MappedFileQueue mappedFileQueue
            CopyOnWriteArrayList<MappedFile>
    4.IndexService
        ArrayList<IndexFile> indexFileList
    
### 3.特性-延迟消息

### 4.特性-事务消息