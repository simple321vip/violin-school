#### Modern Operating Systems

##### ③.内存管理
经过多年探索，人们提出分层存储体系memory hierarchy

    几种存储管理方案：<br/>
      - 无存储器抽象
        最简单的存储器抽象就是没有抽象，每个程序都直接访问物理内存。
        存储器模型就是简单的物理内存：从0到某个上限的地址集合，每个地址容纳1个字节的大小
        
        IBM360 早期模型
        2KB 内存 作为一个块，被配给一个 4位的保护键
        PSW Program Status Word 程序状态字（也叫程序状态寄存器）。
        保护键 存储在CPU的特殊寄存器中
            