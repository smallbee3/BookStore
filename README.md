# BookStore 서적 정오표
Errata of the books one the list

<br>

[1. HTTP 완벽가이드](https://github.com/smallbee3/BookStore#1-http-%EC%99%84%EB%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C) &nbsp;&nbsp;&nbsp; (2쇄 기준, 2016.1.30) \
[2. Two Scoops of DJango](https://github.com/smallbee3/BookStore#2-two-scoops-of-django) &nbsp;&nbsp;&nbsp; (초판 1쇄 기준, 2016.8.12) \
[3. Hello Coding 알고리즘](https://github.com/smallbee3/BookStore#3-hello-coding-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98) &nbsp;&nbsp;&nbsp; (3쇄 기준, 2018.4.20) \
[4. 모던 웹을 위한 Javascript jQuery 입문](https://github.com/smallbee3/BookStore#4-%EB%AA%A8%EB%8D%98-%EC%9B%B9%EC%9D%84-%EC%9C%84%ED%95%9C-javascript-jquery-%EC%9E%85%EB%AC%B8) &nbsp;&nbsp;&nbsp; (3판 2쇄 기준, 2017.8.10) \
[5. SQL더쉽게,더깊게](https://github.com/smallbee3/BookStore#5-sql%EB%8D%94%EC%89%BD%EA%B2%8C%EB%8D%94%EA%B9%8A%EA%B2%8C) &nbsp;&nbsp;&nbsp; (3쇄 기준, 2017.8.31) \
[6. 필수 알고리즘 with 파이썬](https://github.com/smallbee3/Study-Algorithm#%ED%95%84%EC%88%98-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-with-%ED%8C%8C%EC%9D%B4%EC%8D%AC--%EC%A0%95%EC%98%A4%ED%91%9C-%EB%A6%AC%EC%8A%A4%ED%8A%B8) &nbsp;&nbsp;&nbsp; (초판 1쇄 기준, 2018.10.24) \
[7. 하루 3분 네트워크 교실](https://github.com/smallbee3/BookStore#7-%ED%95%98%EB%A3%A8-3%EB%B6%84-%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-%EA%B5%90%EC%8B%A4) &nbsp;&nbsp;&nbsp; (1판 2쇄 기준, 2017.8.4) \
[8. 그림으로 배우는 HTTP & Network Basic](https://github.com/smallbee3/BookStore#8-%EA%B7%B8%EB%A6%BC%EC%9C%BC%EB%A1%9C-%EB%B0%B0%EC%9A%B0%EB%8A%94-http--network-basic) &nbsp;&nbsp;&nbsp; (1판 4쇄 기준, 2017.4.3)
[9. 데이터베이스 개론]() &nbsp;&nbsp;&nbsp; ()


<br><br><br><br><br><br>





# 1. HTTP 완벽가이드
*2쇄 기준, 2016.1.30*


### p.87
(아래서 5줄) \
"세그먼트를 IP `패킷라고` 불리는"

> "패킷이라고"

<br>
<br>





# 2. Two Scoops of DJango
*초판 1쇄 기준, 2016.8.12*

<no content>
<br>
<br>





# 3. Hello Coding 알고리즘
*3쇄 기준, 2018.4.20*


### p.38
"가수별로 몇 곡이"

> "가수별로 몇 곡을"

<br>


### p.65
"이제 재귀 함수에서.."

> "이제 생각한 함수에서.."

<br>


### p.206

방송국의 수	정확한 알고리즘
O(n!)
-> O(2ⁿ)	탐욕 알고리즘

O(n²)
5	3.2초	2.5초
10	102.4초	10초
...	...	...

정확한 알고리즘
O(n!)

> O(2ⁿ)

<br>


### p.211

프레몬트에서 출발:

버클리가 두 번째 도시인 경우

①

.	버클리

샌프란시스코	버클리

.		프레몬트

> 버클리 -> 마린

<br>


### p.234

만약 행의 순서가 바뀌면 어떻게 되나요?
답은 바뀌지 않습니다. 즉, 행의 순서에는 영향을 미치지 않습니다.

> 답은 바뀌지 않습니다. 즉, 행의 순서에는 영향을 받지 않습니다.

<br>
<br>





# 4. 모던 웹을 위한 Javascript jQuery 입문
*3판 2쇄 기준, 2017.8.10*



### p.141
(아래서4번째줄)

`9장에서` 이벤트를 배우면 "이렇게 사용하는 것이구나!"라고 이해할 수 있습니다.

> 11장에서


<br>


### p.150

표 5-5 숫자 확인 함수
함수 이름	설명
isFinite(number)	number가 무한한 값인지 확인합니다.
isNaN(number)	number가 NaN인지 확인합니다.

'isFinite()'

> 'isFinite(number)'


<br>


'무한한'

>>

> '유한한'

<br>


###  p.174

NOTE_ 다른 프로그래밍 언어는 `두 가지` 차이가 있으므로 요소와 속성이라 불러 구분합니다.

> 요소와 속성 두 가지가 서로

<br>


### p.203

NOTE_  바벨을 활용할 때의 객체 복제

코드 6-38 전개 연산자를 사용한 객체 복제

<script>

    // `배열을` 선언합니다.  \
    const originalObject = { \
      name: '윤인성', \
      birthDay: new Date(2016, 12 - 1, 9).toString() \
    }; \

    // `배열을` 복제합니다.
    const newObject = {...originalObject}; \

</script>

> 객체를

<br>


### p.224
(아래서5번째줄) \
하지만 직접 square 객체의 constructor() 메서드를 출력해보세요.

> 하지만 직접 'alert(square.constructor)'로 square 객체의 constructor() 메서드를 출력해보세요.

<br>


### p.235
(아래서4번째줄) \
그림 8-1처럼 기본 자료형과 객체는 자료형이 분명 다릅니다. 하지만 두 가지 모두 `값을` 출력합니다.

> 같은 값을

<br>


### p.286
[코드 8-56 일반적인 배열 메서드 사용] \
```javascript
<script>
    ...

    // 과학 성적이 90점 넘는 학생을 필터링 합니다.
    var filteredA = students.filter(function (item) {
        return item > 90;
    });
    console.log(filteredA);

    ...
</script>
```

> return item.과학 > 90;

<br>


### p.286
[코드 8-57 화살표 함수를 사용한 Array 객체의 메서드 활용]
```javascript
<script>
    ...

    // 과학 성적이 90점 넘는 학생을 필터링 합니다.
    var filteredA = students.filter((item) => item > 90);
    console.log(filteredA);

    ...
</script>
```

> item.과학 > 90

<br>


### p.292
02. 1번에서 `'Hello World..!'와` 'hello world..!'가 차례대로 출력하게 하려면 무엇을 변경해야 할까요?

> 'HELLO WORLD..!'와

<br>


### p.301
(아래서2번째줄)

OOTo() 형태의 메서드는 절대적인 기준으로 속성을 `변화하는` 메서드입니다.

> 변화시키는

<br>


### p.307
코드 9-11은 `window 객체가` 로드가 완료되고 자동으로 할당한 함수를 실행합니다.

> window 객체의

<br>


### p.847
(아래서2번째줄)

페이스북이든 네이버든 크롬으로 접속하고 검사의 `Resources 탭을` 선택합니다.

> Application 탭을

<br>
<br>





# 5. SQL더쉽게더깊게
*3쇄 기준, 2017.8.31*


### p.30
(아래서2번째줄) \

실수로 열을 추가했다면 ALTER TABLE 문으로 삭제하거나 재작성해야 한다.

> 삭제해야한다.

<br>


### p.100

(HAVING 구를 사용하는 경우) \
SELECT 문 실행순서 \
SELECT -> FROM -> WHERE -> GROUP BY -> HAVING

> FROM -> WHERE -> GROUP BY -> HAVING -> SELECT

<br>


### p.106

[3-4 학습 포인트]

* ...
* ORDER BY 구에 열 번호를 사용할 수 없다.

> ORDER BY 구에 열 번호를 사용해서는 안 된다.

<br>


### p.147

[COLUMN] \
앞에서 '트랜잭션을 개시를 위한 표준 명령은 ...

> 앞에서 '트랜잭션을 개시하기 위한

<br>


### p.149

ㅁ 지속성 (Durability) \
이것은 영속성이라고도 하는데, 트랜잭션이 (커밋이든 롤백이든) 종료되면 해당 시점의 데이터 상태가 저장되는 것을 보증하는 성질이다. 시스템에 장애가 발생해서 데이터가 망가진 경우라도 데이터베이스는 어떠한 방법으로든 복구 수단을 가지고 제공해야 한다.

> "복구 수단을 제공해야 한다."

...
이 지속성을 보증하는 방법은 구현 방법에 따라 다른데, 가장 일반적인 방법은 트랜잭션 실행 기록을 디스크 등에 기록해 두었다가(이과 같은 실행 기록을 '로그'라고 한다.) ...

> (이와 같은 실행 기록을 '로그'라고 한다.) ...

<br>


### p.157

구문 5-1 \
CREATE VIEW 뷰명 (<뷰의 열명1>, <뷰의 열명22>, ⋅⋅⋅)

> <뷰의 열명2>, ⋅⋅⋅)

<br>


### p.208

'변환'이라는 용어가 가지는 의미가 많이 있지만, SQL에서는 `크기` 두 가지 의미가 있다.

> 크게 두 가지 의미가 있다.

<br>


### p.215
... 이것은 중간 일치가 전방 일치와 후방 일치 `모두` 포함하는 조건이기 때문이다.

> 모두를

<br>


### p.331
[①의 해답] \
... 또한, IN뿐만 아니라 일반 술어로 NULL과 비교하는  것이 불가능하다

> 또한, 뿐만 아니라 일반 술어 IN으로 NULL과 비교하는  것이 불가능하다

<br>


### p.331
[②의 해답] \
.. \
매입단가가 NULL인 레코드뿐만 아니다. ①에서 `선택되지 않은` 펀칭기나 도마도 없어져 버렸다.

> 선택된 펀칭기나 도마도 없어져 버렸다.

<br>


### p.269

크로스 결합에서 테이블을 연결하는 것은 `집합 연산자가` 'CROSS JOIN(직적)'이다.

> 집합 연산자인 ...

<br>


### p.270

리스트 7-16  옛날 구문을 사용한 내부 결합`(결과는 리스트 7-9와 동일)``

> (결과는 리스트 7-10와 동일)

<br>


### p.288

결과를 보면 current_avg 계산 방법은 분명히 평균을 구하고 있긴 하지만, 집계 대상은 '자신보다 위에' 있는 레코드인 것을 알 수 있다.

> 집계 대상은 '자신과 자신보다 위에' 있는 ...

<br>


### p.289

[주 8-10] \
지금 시점에서 이 기능을 사용 할 수 있는 것은 Oracle과 DB2 뿐이다.

> 지금 시점에서 이 기능을 사용 할 수 있는 것은 Oracle과 DB2, PostgreSQL이다.

<br>


### p.296

[주 8-12] \
지금 시점에 GROUPING 연산자는 PostgreSQL, MySQL에서는 지원하지 않는다(단, MySQL에서는 ROLLUP만 이용할 수 있다).

> 지금 시점에 GROUPING 연산자는 MySQL에서는 지원하지 않는다


<br>
<br>





# 7. 하루 3분 네트워크 교실
*1판 2쇄 기준, 2017.8.4*


### p.105
그림 15-3 MAC 주소 \
48비트로 16진수 12자리로 표기되는 주소

비트 16진수 표기 \
00000000  00001101 01100001 `0110110` 01101101 01101110 \
&nbsp;&nbsp; 00 &nbsp;&nbsp; 0D &nbsp;&nbsp; 61 &nbsp;&nbsp; 76 &nbsp;&nbsp; 6D &nbsp;&nbsp; 6E

> 1110110

<br>


### p.141
그렇지. `독립한` 네트워크 끼리라면 상관없다는 얘기야.

> 독립된

<br>


### p.180
(아래서6번째줄) \
`RIP는` 국가나 지역별 단체에 위탁하는 경우가 있어요.

> RIR은

<br>


### p.262
(아래서10번째줄) \
그래. 그럼 이번에는 사설 IP 주소에 대한 얘기를 하자. 보통 `사설 IP 주소는` ICANN이 관리하고 있다고 했었다.

> (글로벌) IP 주소는

<br>
<br>





# 8. 그림으로 배우는 HTTP & Network Basic
*1판 4쇄 기준, 2017.4.3*


### p.24
(그림) \
&nbsp;&nbsp;&nbsp; HTTP 데이터 \
네트워크 계층  HTTP 데이터

>

&nbsp;&nbsp;&nbsp; TCP 헤더 \
네트워크 계층  HTTP 데이터


&nbsp;&nbsp;&nbsp; HTTP 데이터 \
링크 계층  HTTP 데이터

>

&nbsp;&nbsp;&nbsp; TCP 헤더 \
링크 계층  HTTP 데이터

<br>


### p.48
PUT 메소드를 사용한 리퀘스트/리스폰스 예 \
리퀘스트  `POST` /example.html HTTP /1.1

>

PUT 메소드를 사용한 리퀘스트/리스폰스 예 \
리퀘스트  PUT /example.html HTTP /1.1

<br>


### p.49
HEAD 메소드를 사용한 리퀘스트/리스폰스 예 \
리퀘스트  `POST` /example.html HTTP /1.1

>

HEAD 메소드를 사용한 리퀘스트/리스폰스 예 \
리퀘스트  HEAD /example.html HTTP /1.1

<br>


### p.185
(위에서4번째줄) \
암호화 되지 않은 `통신도` 같습니다.

>

통신과도

<br>


### p.188
(아래서3번째줄)

`리퀘스트를 보낸` 서버가 정말로 URI에서 지정된 지정된 호스트인지 아닌지, `리스폰스를 반환한` 클라이언트가 정말로 리퀘스를 출력한 클라이언트인지

>

리스폰스를 반환한 서버가 정말로 URI에서 지정된 지정된 호스트인지 아닌지, 리퀘스트를 보낸 클라이언트가 정말로 리퀘스를 출력한 클라이언트인지..."

<br>
<br>



# 9. 데이터베이스 개론
* 기준, *


### p.100
(아래서3번째줄)

일반적으로 데이터베이스 관리 시스템은 논리적 데이터 모델만 하나만 지원한다.

> 모델을


<br>

