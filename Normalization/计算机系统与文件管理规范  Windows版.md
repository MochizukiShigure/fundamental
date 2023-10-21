# Management specification for computer system and documentation - Windows edition

# 计算机系统与文件管理规范-Windows版





## 1.磁盘管理

### 1.1 单个物理硬盘

#### 1.1.1 单个固态硬盘

* 动态分配法：分为**C盘**和**D盘**两盘。**系统、软件安装在C盘，文件存储在D盘。**给予D盘少量初始空间（如100G），**当D盘空间不足时，从C盘压缩部分闲置空间至D盘**。



#### 1.1.2 单个机械硬盘

暂无



### 1.2 多个物理硬盘

#### 1.2.1 多个固态硬盘

* 一个物理盘对应一个虚拟盘
* 系统与数据不在同一个盘中
* 若存在两个以上的大内存盘，则软件应储存在系统盘、数据盘外的物理盘中。此外，可以将软件、数据分别存储在多个物理盘中。



#### 1.2.2 多个机械硬盘

暂无



### 1.3 总结

核心思想：系统与数据分治，C盘空间优先。



## 2.数据盘文件夹



| D：            |                    |
| -------------- | ------------------ |
| **achieve**    | **按阶段归档文件** |
| **document**   |                    |
| learning       |                    |
| media          |                    |
| **resource**   | **下载的代码**     |
| **repository** | **自己写的代码**   |
| **search**     | **论文文献**       |
| **shelves**    | **电子书**         |
| **temp**       | **临时文件**       |



| D:/document：      |                |
| ------------------ | -------------- |
| **SlidesTemplate** | **幻灯片模板** |
| **saves**          | **游戏存档**   |
|                    |                |
|                    |                |



**Candidate：**

~~Article、~~Backup、Collection、Database、Entertain、~~Library、Literature、~~Material、Package、~~Paper、~~Project、~~Reading、~~scholar、~~Research、~~



## 3.软件管理







## 4.系统设定

### 4.1 任务栏

#### 4.1.1 Windows 10
* 在桌面模式下自动隐藏任务栏

