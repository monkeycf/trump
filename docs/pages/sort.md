# 排序

## QuickSort
* 参数：
    * {Array\<any>} array
    * {Function} SortComparisonMethods
* 返回值：有序数组
* 示例
```javascript
  trump.quickSort([1, 5, 3], (a, b) => a < b);
  
  // 也可以省略比较函数（升序）
  trump.quickSort([7, 4, 8]);

  trump.quickSort([{ id:5 }, { id: 6 }], (a, b) => a.id < b.id);
```
## HeapSort
* 参数：
    * {Array\<any>} array
    * {Function} SortComparisonMethods
* 返回值：有序数值
* 示例
```javascript
    trump.heapSort([1, 5, 3], (a, b) => a < b);

    // 也可以圣洛比较函数（升序）
    trump.heapSort([7, 4, 8]);

    trump.heapSort([{ id:5 }, { id: 6 }], (a, b) => a.id < b.id);
```
