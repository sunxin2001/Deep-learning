create two pointer with different speed.  
example1  
![image](https://user-images.githubusercontent.com/111692657/210189680-f94aa846-e6e0-470a-99e3-533dcbe6851c.png)  
The problem involves a linked table or an array containing "loops"  
Need to solve for the position of an element in a chain table or the length of a chain table  
leetcode 141:
![image](https://user-images.githubusercontent.com/111692657/210189892-01ce916f-3177-41a3-9484-08d89121df7c.png)  
Using fast and slow pointers, the fast pointer moves forward two steps at a time, the slow pointer moves forward one step at a time, and the two pointers meet only when there is a ring in the chain table.
<br>
<br>
<br>
example 2  
![image](https://user-images.githubusercontent.com/111692657/210190543-88ebb874-d719-4595-8f42-8faaccdd0bf0.png)  
![image](https://user-images.githubusercontent.com/111692657/210190532-c51ac17b-1519-4c3a-82b1-246b89e10867.png)  
```
class Solution:
    def detectCycle(self, head: ListNode) -> ListNode:
        slow, fast = head, head
        while fast and fast.next:
            slow = slow.next
            fast = fast.next.next
            if slow == fast:
                current = head
                while current != slow:
                    current = current.next
                    slow = slow.next
                return slow
        return None
```
First reach the position where the fast and slow pointers are equal, then create a new pointer and start moving from the beginning until the position where it meets the slow pointer is the starting node of the loop.


