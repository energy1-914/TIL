# 2022.08.09 

## 얕은 복사(Shallow copy) 깊은 복사(Deep copy)

```shell
- 얕은 복사 : 같은 메모리 주소 사용. 
              둘 중 어떤 것의 값을 변화시켜도 나머지 하나도 동일하게 변화가 일어남.

- 깊은 복사 : 속성을 복사하여 다른 메모리 주소에 저장. 하지만 딱 1 depth 까지만.
              객체데이터 안의 배열 데이터는 얕은 복사가 되어 같은 메모리 주소를 갖게 된다.
	      이 경우에 모든 속성의 깊은 복사를 위해서는 spread(...) 연산자나 object.assign() 메소드가 아닌 lodash 기능 중 하나인 .cloneDeep 을 사용해야한다.
```

## DOM API(Document Object Model, Application Programming Interface)
- 자바스크립트에서 HTML을 제어하는 여러가지 명령들 
  # ex) queryselector, classList.add 등

## JSON(JavaScript Object Notation)

- 자바스크립트의 데이터를 표현하는 하나의 포맷.(속성-값 쌍)


## fetch() 함수 사용법

- fetch(API, options)
  .then((response) => console.log(response)
  .catch((error) => console.log(error)

  # fetch() 함수는 첫번째 인자로 API 주소를, 두번째 인자로 옵션 객체를 받는다.
  # 또한, promise 타입의 객체를 반환한다 .
  # 성공적으로 실행되면 then() 실행.

