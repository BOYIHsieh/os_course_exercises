# lec19: lab7 同步互斥　在线练习
## 选择题

---

ucore为支持内核中的信号量机制，需用到的支撑机制包括（） s2 底层支撑

- [x] 处理器调度
- [x] 屏蔽中断
- [x] 等待队列
- [ ] 动态内存分配

> 需用到前三个，动态内存分配不是必须的


ucore实现的信号量机制被用于（） s3 信号量设计与实现
- [x] 条件变量实现
- [x] mm内存管理实现
- [x] 哲学家问题实现
- [ ] 中断机制实现

> 中断机制是支持信号量的，所以不选


关于ucore实现的管程和条件变量的阐述正确的是（） s4 管程和条件变量设计实现
- [x] 管程中采用信号量用于互斥操作
- [x] 管程中采用信号量用于同步操作
- [x] 管程中采用条件变量用于同步操作
- [x] 属于管程的共享变量访问的函数需要用互斥机制进行保护

> 都对



