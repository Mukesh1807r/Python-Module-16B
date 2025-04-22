# Constructing and Balancing an AVL Tree

## 📌 Aim
To write a Python program that constructs an **AVL Tree**, prints the tree structure **before** and **after** balancing using appropriate packages and built-in functions.

---

## 🛠 Procedure
1. Import the `AVL` class from the `TreeAVL` module.
2. Define a helper function `getDictTree(self)` that returns the dictionary representation of the tree using the `dict_tree` attribute.
3. Define the `Construct_AVL(L)` function:
   - Build the AVL tree from the input list `L`.
   - Print the tree dictionary before balancing.
   - Call the `BalanceTree()` method to balance the AVL Tree.
   - Print the tree dictionary after balancing.

---

## 💻 Program

```python
from TreeAVL.AVL import AVL

def getDictTree(self):
    return self.dict_tree

def Construct_AVL(L):
    tree = AVL(L)
    print("AVL Tree Before Balancing\n", getDictTree(tree))
    tree.BalanceTree()
    print("AVL Tree After Balancing\n", getDictTree(tree))
```
---
## Output

![image](https://github.com/user-attachments/assets/41b657d0-4eb5-4e68-accc-668368a6db7d)

---

## Result 
Thus, the program was successfully created and executed to construct and balance an AVL tree while displaying its structure before and after the balancing process.


