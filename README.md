# leetcode_practice
leetcode_practice for 代码随想录
## 08/27/2023 
### 203 删除链表中等于给定值 val 的所有节点。
思路： 对于节点value=val的节点，让其上一个节点直接连接到下一个节点
tricks: 可以自定义一个dummyhead， 这样只用判断current.next.value 就可以了
### 206 反转链表
思路： 双指针，初始化prev为None，然后每一步中，首先cache current.next， 然后把current指向prev，最后prev和current前进
### 707 设计链表
tricks： 当增加/减少元素时，一定不要忘记改变self.size!
### 24 两两交换链表中的节点
思路：我觉得递归比dummy head好懂多了，dummy head那个太绕了，递归这个就是一定要考虑好退出条件
### 19 删除链表的倒数第N个节点
思路：快慢指针
### 160 链表相交
给你两个单链表的头节点 headA 和 headB ，请你找出并返回两个单链表相交的起始节点。如果两个链表没有交点，返回 null 。
思路：首先尾部对齐，方法为：求出两链表长度，然后让长链表先步行长度差的步数，而后开始判断currentA是否等于currentB
### 142 环形链表
给定一个链表，返回链表开始入环的第一个节点。 如果链表无环，则返回 null。
思路，快慢指针，精髓在于数学推导过程 !high
