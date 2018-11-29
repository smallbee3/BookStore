# BookStore 서적 정오표
Errata of the books one the list

<br>

[1. HTTP 완벽가이드](https://github.com/smallbee3/BookStore#1-http-%EC%99%84%EB%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C) \
[2. Two Scoops of DJango](https://github.com/smallbee3/BookStore#2-two-scoops-of-django) \
[3. Hello Coding 알고리즘](https://github.com/smallbee3/BookStore#3-hello-coding-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98) \
[4. 모던 웹을 위한 Javascript jQuery 입문](https://github.com/smallbee3/BookStore#4-%EB%AA%A8%EB%8D%98-%EC%9B%B9%EC%9D%84-%EC%9C%84%ED%95%9C-javascript-jquery-%EC%9E%85%EB%AC%B8) \
[5. SQL더쉽게,더깊게](https://github.com/smallbee3/BookStore#5-sql%EB%8D%94%EC%89%BD%EA%B2%8C%EB%8D%94%EA%B9%8A%EA%B2%8C)
[6. 필수 알고리즘 with 파이썬](https://github.com/smallbee3/Study-Algorithm#%ED%95%84%EC%88%98-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-with-%ED%8C%8C%EC%9D%B4%EC%8D%AC--%EC%A0%95%EC%98%A4%ED%91%9C-%EB%A6%AC%EC%8A%A4%ED%8A%B8)


<br><br><br><br><br><br>



# 1. HTTP 완벽가이드


### p.87 아래서 5줄
"세그먼트를 IP 패킷라고 불리는"

> "패킷이라고"

<br>
<br>



# 2. Two Scoops of DJango


<br>
<br>



# 3. Hello Coding 알고리즘


### p.38
"가수별로 몇 곡이"

> "가수별로 몇 곡을"

<br>


### p.65
"이제 재귀 함수에서.."

> "이제 생각한 함수에서.."

<br>


### p.206
180928
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
180929

프레몬트에서 출발:

버클리가 두 번째 도시인 경우

①

.	버클리

샌프란시스코	버클리

.		프레몬트

> 버클리 -> 마린

<br>


### p.234
181003

만약 행의 순서가 바뀌면 어떻게 되나요?
답은 바뀌지 않습니다. 즉, 행의 순서에는 영향을 미치지 않습니다.

> 답은 바뀌지 않습니다. 즉, 행의 순서에는 영향을 받지 않습니다.

<br>
<br>



# 4. 모던 웹을 위한 Javascript jQuery 입문


### p.150
181024

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
<br>



# 5. SQL더쉽게더깊게


### p.30 (아래서 두번 째)
181116

실수로 열을 추가했다면 ALTER TABLE 문으로 삭제하거나 재작성해야 한다.

> 삭제해야한다.

<br>


### p.100
181117

(HAVING 구를 사용하는 경우) \
SELECT 문 실행순서 \
SELECT -> FROM -> WHERE -> GROUP BY -> HAVING

> FROM -> WHERE -> GROUP BY -> HAVING -> SELECT

<br>


### p.106
181120

[3-4 학습 포인트]

* ...
* ORDER BY 구에 열 번호를 사용할 수 없다.

> ORDER BY 구에 열 번호를 사용해서는 안 된다.

<br>


### p.147
181120

[COLUMN] \
앞에서 '트랜잭션을 개시를 위한 표준 명령은 ...

> 앞에서 '트랜잭션을 개시하기 위한

<br>


### p.149
181120

ㅁ 지속성 (Durability) \
이것은 영속성이라고도 하는데, 트랜잭션이 (커밋이든 롤백이든) 종료되면 해당 시점의 데이터 상태가 저장되는 것을 보증하는 성질이다. 시스템에 장애가 발생해서 데이터가 망가진 경우라도 데이터베이스는 어떠한 방법으로든 복구 수단을 가지고 제공해야 한다.

> "복구 수단을 제공해야 한다."

...
이 지속성을 보증하는 방법은 구현 방법에 따라 다른데, 가장 일반적인 방법은 트랜잭션 실행 기록을 디스크 등에 기록해 두었다가(이과 같은 실행 기록을 '로그'라고 한다.) ...

> (이와 같은 실행 기록을 '로그'라고 한다.) ...

<br>


### p.157
181120

구문 5-1 \
CREATE VIEW 뷰명 (<뷰의 열명1>, <뷰의 열명22>, ⋅⋅⋅)

> <뷰의 열명2>, ⋅⋅⋅)

<br>


### p.208
181120

'변환'이라는 용어가 가지는 의미가 많이 있지만, SQL에서는 크기 두 가지 의미가 있다.

> SQL에서는 크게 두 가지 의미가 있다.

<br>


### p.215
... 이것은 중간 일치가 전방 일치와 후방 일치 모두 포함하는 조건이기 때문이다.

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
매입단가가 NULL인 레코드뿐만 아니다. ①에서 선택되지 않은 펀칭기나 도마도 없어져 버렸다.

> 선택된 펀칭기나 도마도 없어져 버렸다.

<br>


### p.269
181123

크로스 결합에서 테이블을 연결하는 것은 집합 연산자가 'CROSS JOIN(직적)'이다.

> 집합 연산자인 ...

<br>


### p.270
181122

리스트 7-16  옛날 구문을 사용한 내부 결합(결과는 리스트 7-9와 동일)

> (결과는 리스트 7-10와 동일)

<br>


### p.288
181123

결과를 보면 current_avg 계산 방법은 분명히 평균을 구하고 있긴 하지만, 집계 대상은 '자신보다 위에' 있는 레코드인 것을 알 수 있다.

> 집계 대상은 '자신과 자신보다 위에' 있는 ...

<br>


### p.289
181123

[주 8-10] \
지금 시점에서 이 기능을 사용 할 수 있는 것은 Oracle과 DB2 뿐이다.

> 지금 시점에서 이 기능을 사용 할 수 있는 것은 Oracle과 DB2, PostgreSQL이다.

<br>


### p.296
181124

[주 8-12] \
지금 시점에 GROUPING 연산자는 PostgreSQL, MySQL에서는 지원하지 않는다(단, MySQL에서는 ROLLUP만 이용할 수 있다).

> 지금 시점에 GROUPING 연산자는 MySQL에서는 지원하지 않는다


<br>
<br>