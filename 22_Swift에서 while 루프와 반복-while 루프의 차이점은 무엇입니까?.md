## Swift에서 while 루프와 반복-while 루프의 차이점은 무엇입니까?

- while: condition을 먼저 판단한 후(T/F) 조건을 만족할 때까지 해당 블럭을 반복
- repeat-while: 해당 블럭을 조건과 관계 없이 블럭을 실행한 후, condition을 검사하여 참이 경우에 블럭을 반복 실행
    
    ```swift
    var count = 0
    
    repeat {
        print("Count: \(count)")
        count += 1
    } while count < 5
    ```