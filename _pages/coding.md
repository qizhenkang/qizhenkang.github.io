---
# layout: archive
title: "Coding"
permalink: /coding/
author_profile: true
language: English
language_ref: coding
---

This is an INTRODUCTION about my coding skills.

## code

<!--
```python
class Solution:
    def mergeTwoLists(self, l1: ListNode, l2: ListNode) -> ListNode:
        head = ListNode(-1)
        tail = head
        while l1 and l2:
            if l1.val < l2.val:
                tail.next = l1
                l1 = l1.next
            else:
                tail.next = l2
                l2 = l2.next
            tail = tail.next

        tail.next = l1 if l1 else l2

        return head.next
``` -->
