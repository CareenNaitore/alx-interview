You have n number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1 and each box may contain keys to the other boxes.

Write a method that determines if all the boxes can be opened.

Prototype: def canUnlockAll(boxes)

boxes is a list of lists

1. A key with the same number as a box opens that box

2. You can assume all keys will be positive integers

3. There can be keys that do not have boxes

4. The first box boxes[0] is unlocked

5. Return True if all boxes can be opened, else return False
