# 1. Console Shortcuts
---

`'Cmd + Shift + C'` : 콘솔로 포커 옮기기

`'Cmd + K'` : 콘솔 Clear

`'Cmd + \'` : 현재 라인 브레이크 포인트 추가/삭제

`'Cmd + Y'` : 브레이크 포인트 활성/비활성


# 2. Changing debug steps
---

`'n'` : step over, 다음 라인 실행

`'s'` : step in

`'fin'` : step out

`'c'` : continue, 다음 브레이크로 이동


# 3. Print Something
---


### 변수 출력

```
let car = Car(year: 2014, name: "BMW", color: .red)
```

`p car`, `expr -o -- car` : print object.

`po car`, `expr -- car` : object의 description 함수를 출력.

### 프레임 출력

`thread backtrace`, `bt`, `bt N` : 현재 스레드의 프레임을 출력.

`frame select N`, `fr select N`: N 번째 프레임으로 디버깅 포커스 이동

`frame info`, `fr info` : 현재 프레임의 정보 출력.

`frame variable`, `fr var` : 현재 프레임의 변수들을 출력. VC, CustomView, UIView!@# 등의 정보 볼때 아주 유용하게 사용.

`frame variable NAME`, `fr var car` : 현재 프레임 중 NAME의 변수 출력.





# 4. Modify values at runtime
---



