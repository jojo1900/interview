# 数据结构与算法
<!-- GFM-TOC -->
- [数组(array)](#---array-)
  * [数组下标为何从0开始：](#数组下标为何从0开始：)
  * [数组如何支持随机访问：](#数组如何支持随机访问：)
  * [数组删除操作的时间复杂度及优化：](#数组删除操作的时间复杂度及优化：)
  * [数组插入操作时间复杂度及优化：](#数组插入操作时间复杂度及优化：)
  * [python中数组的动态扩容：](#python中数组的动态扩容：)
- [链表(LinkedList)](#链表(LinkedList))
  * [数组插入操作时间复杂度及优化：](#----------------1)

### 数组(array)
#### 数组下标为何从0开始：
<details>
<summary>展开</summary>
数组寻址的方式是首地址＋偏移量，首地址为a[0]的地址，从0开始时：

` a[k]_address = base_addr + k * type_size ` 

从1开始时：

` a[k]_address = base_addr + (k-1) * type_size ` 

可以看出，从0开始可以减少一次减法操作。
</details>

#### 数组如何支持随机访问：
<details>
<summary>展开</summary>
内存空间连续并且存储的数据类型相同
</details>

#### 数组删除操作的时间复杂度及优化：
<details>
<summary>展开</summary>
时间复杂度O(n)
优化方法：先标记为删除，达到一定数量后统一删除。
</details>

#### 数组插入操作时间复杂度及优化：
<details>
<summary>展开</summary>
时间复杂度O(n)
优化方法：如果存储无序的数据，可以交换插入位置的数据。例如：
a,b,c,d,e 要在b后插入一个x，可以变为：a,b,x,d,e,c
</details>

#### python中数组的动态扩容：
<details>
<summary>展开</summary>
1.初始化的数组有四个元素的存储空间，当数组填满时，list类自动申请一个新的两倍的内存空间
2.旧数组中元素将被一次存入新的数组
3.回收旧数组，初始化新数组。
</details>


### 链表(LinkedList)

#### 
<details>
<summary>展开</summary>

</details>

#### 链表的应用
<details>
<summary>展开</summary>

</details>
