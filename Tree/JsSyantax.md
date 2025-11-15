## Node declration
```c++
class TreeNode {
  constructor(value) {
    this.value = value;
    this.children = [];
  }

  addChild(node) {
    this.children.push(node);
  }
}
const root = new TreeNode("A");
const b = new TreeNode("B");
const c = new TreeNode("C");

root.addChild(b);
root.addChild(c);
```


## Solution of stack and queue 
| Method        | Definition                                       |
| ------------- | ------------------------------------------------------- |
| **push()**    | Adds elements **to the end** of the array.              |
| **pop()**     | Removes and returns the **last element** of the array.  |
| **shift()**   | Removes and returns the **first element** of the array. |
| **unshift()** | Adds elements **to the front** of the array.            |
