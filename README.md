# Array
Properties and methods of arrays


**Array**

```
let arrayString = [12, 23, 34, 345, 1]
print(arrayString.count)


var array = ["First index of array"]
print(array.count)
array.append("Second index of array")
array.firstIndex(of: "Second index of array") // true because it "Second index of array" is existed in the array
print(array.sorted()) // ["First index of array", "Second index of array"]
array.remove(at: 0) //  "First index of array"


var arrayProperty = [Int]()
for index in 2...8 {
    arrayProperty.append(index) // append index values
}
arrayProperty.count > 6. //true //index number of the arrayProperty


let arrayProperty2 = ["1", "2","3", "4"]
arrayProperty2.firstIndex(of: "1") == 3 // false, because "1" is 0th index

var arrayProperty3 = ["1", "4"]
arrayProperty4.contains("4") // true

var arrayProperty4 = [17, 46, 9]
arrayProperty5.sorted() == [9, 17, 46] // true
```
