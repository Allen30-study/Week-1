## Swift에서 switch 문은 어떻게 작동합니까?
```swift
switch condition {
	case 1: ...
		break
	case 2: ...
		break
	case 3: ...
		break
}

// if - else와 마찬가지로 분기를 처리하는 구문
// 해당 condition의 값과 일치하는 case의 구문이 실행된다.
// continue(어떤 조건일 때 continue가 있으면 해당 블럭 넘기기), break로 제어도 가능
// break가 없으면 fallthrough라고 하여 해당 조건을 만족하는 블럭뿐만 아니라 다음 블럭도 실행한다.
// condition에 여러가지 분기가 있을 경우에 사용한다.
```