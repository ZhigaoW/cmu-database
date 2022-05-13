# 数据库系统概论 

## 数据库的存储 

**磁盘作为基础存储的**数据库系统的存储涉及两个问题

1. 数据如何在磁盘上表示(How the DBMS represents the database in files on disk.) 
2. 如何从磁盘和内存之间反复移动数据 (How the DBMS manages its memory and moves data back-and-forth from disk.) 

### 问题一 

#### File Storage

![](/graph/01-storage/01.png)

- 使用**buffer pool**的原因是使内存看起来能装下所有的文件。
- 如果操作系统的虚拟内存机制
    - 有可能半页（database page）被换出，需要加锁，影响性能。


#### Page Layout

![](/graph/01-storage/02.png)






#### Tuple Layout

![](/graph/01-storage/03.png)
















