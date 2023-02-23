## Arrays

### reverse array
```javascript

function reverseArray(arr, start, end) {
    while(start < end) {
        let temp = array[start]
        array[start] = array[end]
        array[end] = temp
        start++
        end--
    }
}

function printArray(array, len) {
    for (let i = 0; i < len; i++) {
        console.log(array[i])
    }
}
```
