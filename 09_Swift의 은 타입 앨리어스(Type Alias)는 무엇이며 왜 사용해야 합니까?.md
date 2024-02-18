## Swift의 은 타입 앨리어스(Type Alias)는 무엇이며 왜 사용해야 합니까?
- 타입 앨리어스: 별칭
- 기존에 선언되어 있는 타입에 새로운 별칭을 붙여 코드의 가독성을 높이기 위함
<br>

```swift
// 타입 앨리어스를 사용하지 않을 때
let name: String = "Wave" // 상수 name의 타입을 문자열로 지정

// 타입 앨리어스를 사용할 때
typealias Name = String
let name: Name = "Wave" // 상수 name의 타입을 Name으로 표현(직관적으로 타입 명시 가능)
```
