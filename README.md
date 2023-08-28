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
