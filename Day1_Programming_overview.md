# 프로그래밍 개요

## 추상화란?
### 
- 복잡한 디테일을 숨기고 주요 기능에만 집중
### 
- 변수, 함수, 객체

- 변수 : x = 254, y= 487 와 같이 어떤 값에 이름을 붙여 놓는 것, 숫자 , 문자, 리스트 등을 할당 받고 이를 이용할 수 있는 객체
- 함수 : 특정 동작을 수행하는 코드를 모아 놓은 코드 블록

#### **예시**
print()


Def hello() :
print()

##### 파라미터 = 매개변수, 
```
ex) x(a, b, c) <- a, b, c가 파라미터
옵셔널 파라미터
Def myself(name, age, nationality=“한국”)
여기서 myself(이름, 나이, 국가)를 제공하면 한국은 표시 안됨
국가를 제공하지 않으면, 한국이라고 표기됨.
옵셔널파라미터는 반드시 파라미터 중 맨 뒤로 와야 함.
```

##### return문의 역할
함수 즉시 종료
값 돌려주기
반환값
```
Def hell(3) :
Return 3 * 3
Print(hell(3))

= 9
```

**나머지 계산**
%
```
Ex) 7%3 = 1
```

**거듭제곱**
**
```
Ex) 2**3 = 8
```

소수형과 정수형의 만남은 소수형으로 결과값이 나옴
나눗셈은 정수형으로 해도 무조건 소수형으로 결과값

**floor division(버림 나눗셈)**
//
```
Ex)print(8 // 3) = 2
```

**반올림**
round
```
print(round(3.145926535 , 4) = 3.1459
```

**문자열(string)**
‘ ’ 혹은 “ ”
**따옴표를 문자취급 하고 싶으면 \ 역슬래시를 앞에 붙여줌**

**형변환**
정수 -> 소수 
문자 -> 숫자 등
- int정수로 변환시켜주거나 숫자로 만들어주는
- float은 소수로 변환 시켜주는 (문자도)
- Str 은 문자열로 변환
```
Ex) print(int(3))
print(float(“3.7”))

year = xxxx
month = xxxx
day = xx
print(“오늘은 ” + str(year) + “년 ” + str(month) + “월 “ + str(day) + “일입니다.”)
=
print(“오늘은 {}년 {}월 {}일 입니다.” .format(year, month, day))
=
어떤변수 = “오늘은 {}년 {}월 {}일 입니다.”
print(어떤변수.format(year, month, day))
```

참고 : 코딩할 때 숫자는 0부터 셈

순서 바꾸고 싶으면,
print(“오늘은 {1}년 {0}월 {2}일 입니다.” .format(year, month, day))
이런식으로.

어느 부분 소수점까지만 나타내고 싶으면
.xf 로 나타냄. 예를들면 “”.3f
{:.3f}

**진리값** 
true / false
And or not
명제 : 참 또는 거짓이 확실한 문장


**boolean**
True 대문자
False 대문자

== <-같다
!= <- 같지 않다

**자료형 확인할 때**
print(type(확인필요한것))

=는 같다라는 의미 x 지정연산자.
x = x +3 이게 같냐는 의미가 아니고 먼지 알지


자주 쓰이는 표현을 더 간략하게 쓸 수 있게 하는 문법을 'Syntactic Sugar'

다음 두 줄은 같습니다
x = x + 1
x += 1

다음 두 줄은 같습니다
x = x + 2
x += 2

다음 두 줄은 같습니다
x = x * 2
x * = 2

다음 두 줄은 같습니다
x = x - 3
x -= 3

다음 두 줄은 같습니다
x = x / 2
x / = 2

다음 두 줄은 같습니다
x = x % 7
x %= 7

**범위**
- 글로벌변수 : 모든 곳에서 사용 가능
- 로컬변수 : 변수를 정의한 함수 내에서만 사용 가능

- 상수 : 절대로 바뀌지 않는 값
**대문자로 적어주기**

**주석처리**
shift로 문자 싹 긁어서
커맨드 슬래쉬

**반복문 : while**
조건부분 + 수행부분 -> 조건부분은 boolean
Ex) 다운 받지 않은 이미지가 있다면
다음 이미지를 보고 다운받아라

**조건문**
If, else <-2가지 옵션만 가능
￼

**Elif <-여러 옵션**
￼
￼
￼
