# SQLD_SQLP
SQL개발자/SQL전문가  certification

## 24.03.09 춘천 52회 SQLD 예상 합
1과목 10점 
2과목 64점
## 24.03.29 제 52회 SQLD 합격 후기
![image](https://github.com/chihyeonwon/SQLD_SQLP/assets/58906858/31cbd718-19f8-4dbd-9be2-edc723bba4aa)     
1과목 14점 
2과목 62점
```
SQLD 자격증 준비에 앞서 컴퓨터공학과 재학생 신분으로서 데이터베이스설계, 응용 과목을 들으면서 SQL에 관심을 가지게 되었다.
나는 인터넷에 올라온 3일 전사, 7일 전사, 1달의 전사들을 수없이 많이 봤다.
하지만 내 방법대로 기출문제와 모르는 개념을 정리하면서 공부하면 기간이 어떻게 되던간에 합격할 것이라는 자신감이 있었다.
그래서 sql 개발자 기출문제 500제를 모두 풀고 모르는 개념은 깃허브에 정리하면서 공부했다.

1과목 과락을 걱정했지만 다행히도 합격했고 후기를 쓸 수 있게 되어서 기쁘다. 현업에 나가서 공부한 내용을 적용하고 싶고
사회에서의 쓸모와 가치를 스스로 증명하고 또 더 높은 단계의 시험들도 준비해보고 싶다.
```
## 24년 하반기 SQLP전문가 접수


## 자격요건 및 합격기준
![image](https://github.com/wonttan/SQLD_SQLP/assets/58906858/cc8e8790-50c4-4efc-926a-7d4272b00a98)
```
60점 이 즉, 2점짜리 50문제 중 30문제 맞추면 합격
과락40%  1과목 데이터모델링 4/10 4문제이상
2과목 SQL 기본 및 활용 16/40 16문제이상
```

## 시험일정
![image](https://github.com/wonttan/SQLD_SQLP/assets/58906858/82367731-d736-46fc-a5ad-af98475bc1b7)

## 출제문항
![image](https://github.com/wonttan/SQLD_SQLP/assets/58906858/fbf5f40e-8648-4fe1-a0c3-b38cb424f510)

## 시험준비
[이기적 CBT SQL 개발자](https://cbt.youngjin.com/exam/index.php?no=73)
[이기적 SQL 개발자 기출문제 500제](https://license.youngjin.com/free_edu/free_edu_mp4.asp?elc_cd=2536&cate_cd=2393)
```
데이터베이스 응용 과목 들으면서 이기적 기출문제 500제 풀고 쉴 때 CBT
```
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/d0e5f82d-3df7-44aa-8c6b-29e4dc7ec7b8)
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/239539e7-daba-4887-b6aa-abb2b195f450)
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/2a753950-e317-4194-b3be-9db85738624a)

## Top N 쿼리

## Pivot vs UnPivot

## SQL 개발자 핵심 150제 틀린 문제 개념 정리
#### 24. 02.01
![image](https://github.com/wonchihyeon/SQLD_SQLP/assets/58906858/96efc438-7ad1-4d5e-9658-7bf7d41f1c8f)
```
모델링을 할 때 세 가지 관점 : 데이터, 프로세스, 데이터와 프로세스의 상관 관점

데이터 모델링의 세 가지 개념 : 업무가 관여하는 어떤 것 Things, 업무가 관여하는 어떤 것의 성격 Attributes, 업무가 관여하는
어떤 것의 관계 : Relationships

발생 시점에 따라 구분할 수 있는 엔터티의 유형 : 행위, 중심, 기본

관계를 정의할 때 주요하게 체크해야 하는 사항 : 업무기술서, 관계연결을 가능하게 하는 동사가 있는가?

식별자의 대체 여부에 따라 분류하는 방식은? : 본질-인조 식별자

비식별자 관계란 부모 엔터티로부터 속성을 받았지만 자식 엔터티의 주식별자로 사용하지 않고 일반적인 속성으로만 사용하는 것

데이터 모델링에 대한 설명 : 논리 모델링의 외래키는 물리 모델에서 반드시 구현되지는 않는다.

분산 데이터베이스의 특징 : 처리 비용의 증가, 오류 잠재성 증대, 빠른 응답 속도와 통신 비용 절감

해시 조인 기법 : 조인 작업을 할 때 결과 행의 수가 적은 것을 선행 테이블로 사용, '='로 수행하는 동등조인만 가능
적재할 수 있는 영역 크기보다 커지면 임시 영역(디스크)에 적재, 조인 칼럼의 인덱스가 존재하지 않아도 사용 가능

어떤 엔티티의 모든 속성을 참조하기를 원할 때 성능 향상과 SQL 문장을 단순화하는 가장 적절한 반정규화 방법은 ?
- 관계를 중복하는 관계의 반정규화 (1:M관계 등을 추가하는 관계 반정규화)

데이터 모델의 성능을 고려하기 위해 정규화를 적용한 데이터모델을 만든다.

분산 데이터베이스의 투명성 : 분할, 위치, 지역, 중복, 병행, 장애

논리적인 데이터 모델 슈퍼/서브 타입의 데이터 모델 성능을 고려한 물리적인 모델에서 변환하는 방법 세 가지
1:1 타입, 슈퍼+서브 타입, All in One 타입

데이터무결성을 깨뜨리지 않는 기법 : 중복관계의 반정규화
데이터무결성을 깨뜨리는 기법 : 칼럼, 테이블의 반정규화

where 절에 집계함수 불가능, 서브쿼리 절에 order by 불가능

alter table 에서 drop column, modify column 처럼 column이 붙으면 여러 속성 변경 불가
rename column 역시도

delete, 데이터 전체삭제,일부삭제 가능, 롤백 가능, DML
truncate 데이터 전체삭제(일부삭제불가능), 롤백 불가능, DDL
drop : 데이터와 구조 모두 삭제 롤백 불가능, DDL

사원 emp, 부서 dept 일때
부모 : 부서 dept에 pk키 검 add constraint 이름생략가능 primary key(deptno)
자식 : 자식 emp에 foreign 키 검 add constraint 이름생략가능 foregin key(deptno) references primary key(deptno)

부모 테이블에는 삭제제약(자식이 먼저 삭제가 되야함), 업데이트제약(자식에 값이 있기 때문에)
자식 테이블에서 삭제가능, 업데이트는 제약될 수 있음(부모에 있는 값으로 해야함)

on delete cascade
on delete set null

부모 테이블은 삭제가 안되지만 on delete cascade를 쓰면 삭제가 가능하다.(자식도 삭제)
부모 테이블에서 on delete set null이면 부모는 삭제되지만 자식에서 삭제된 데이터는 null이 된다.

DCL 여러 유저에게 권한 가능, 여러 권한 부여 가능 BUT 여러 객체 권한 X
GRANT 권한부여 ON 객체 TO 유저

이미 회수된거에 회수하면 에
REVOKE 권한부여 ON 객체 FROM 유저 

롤에 권한을 담고 grant 여러 권한을 넣어서
롤을 유저에게 주는 grant 롤 to 유저

롤은 재시작해야 반환된다.

롤을 통한 권한 부여는 직접 회수가 불가능하다.

중간권한 2개

with grant option 오브젝트 권한
중간관리자를 통해서만 회수 가능, 직접 회수 불가능, 중간권한 회수시 권한 남아 있지 않음

with admin option : 시스템/롤 권한을 부여, 중간관리자 거치지않고 직접회수 가능
중간권한 회수시 제 3자 권한 남아있음
```
#### 24.02.02
1과목 데이터 모델링의 이해
```
모델링할 때 세 가지 관점 : 데이터에 대한 관점 :업무가 어떤 데이터와 관련이 있는 지 분석
프로세스에 대한 관점 : 업무에서 실제로 하는 일은 무엇인지 또 무엇을 해야 하는 지 분석
데이터와 프로세스에 대한 관점 : 업무에서 처리하는 일의 방법에 따라 데이터가 어떻게 영향을 받는지 분석

데이터 모델링의 세 가지 중요 개념 : 업무가 관여하는 어떤 것(things),
업무가 관여하는 어떤 것의 성격(Attributes),
업무가 관여하는 어떤 것의 관계(Relationship)

발생 시점에 따라 구분할 수 있는 엔터티 유형 : 기본, 중심, 행위 엔터티 (개념 엔터티는 없음)

관계를 정의할 때 주요하게 체크 해야 하는 사항 : 업무 기술서, 장표에 관계연결을 가능하게 하는 동사(Verb)가 있는가?

식별자의 대체 여부에 따라 분류하는 방식은? : 본질 - 인조 식별자

해시 조인에서 해시 테이블을 저장할 때 메모리에 적재할 수 있는 영역의 크기보다 커지면
초과한 크기를 제외한 영역만큼 디스크에 적재한다.

해시 조인은 인덱스가 없어도 사용할 수 있다.

어떤 엔터티의 모든 속성을 참조하기를 원할 때 가장 효율성이 좋은 반정규화 방법은
관계를 중복하는(추가)하는 관계 반정규화이다.

데이터 모델링을 할 때 첫 번째 단계는 정규화를 적용한 데이터 모델을 만드는 것이다.
반정규화는 분석 단계가 아닌 확인과 검증 앞 단계임
정규화(분석) -> 반정규화 -> 검증, 확인

논리적 모델에서 슈퍼/서브 타입의 성능을 고려한 물리적인 데이터 모델 변환 방법 세 가지는
1:1 (One to One), Super/Sub Type, All in One

데이터 무결성 영향이 없는 반정규화 기법 -> 중복관계 추가
데이터 무결성 영향이 있는 반정규화 기법 -> Table, Column의 반정규화
```
2과목 SQL 기본 및 활용
```
테이블명과 칼럼명은 반드시 문자로 시작해야 하며 특수 문자는 _와 $만 가능하다 (-는 불가)
FROM 절에서 테이블에 대한 Alias를 사용하였다면 SELECT 절에서는 반드시 테이블명이 아닌 ALIAS명을 사용해야 한다.
EQUI JOIN은 반드시 기본키, 외래키 관계에서만 성립되는 것은 아니다. 조인 컬럼이 1:1로 맵핑이 가능하면 사용할 수 있다.
테이블의 개수가 N개일 때 필요한 조인 조건의 최소 개수는 N-1이다.
UNION ALL 연산자는 조회 결과에 대해 별도의 정렬 작업을 하지 않고, 중복 데이터에 대해서 삭제하지 않고 여러 번 중복 표현한다.
SELF JOIN을 수행해야할 때는 ? 한 테이블 내에서 두 칼럼이 연관 관계가 있다.
상호 연관 서브쿼리는 메인쿼리의 행 수만큼 실행되는 쿼리로서 실행 속도 상대적으로 떨어진다.
동일 SQL 내에서 실행계획은 다르다고 해도 결과는 달라지지 않는다.
규칙 기반 옵티마이저는 적절한 인덱스가 존재하면 항상 인덱스를 사용하려고 한다.
from 절에 나열된 테이블은 항상 2개씩 조인된다.
NVL(SAL, 0)문에서 NVL은 NULL에 대한 합계오류를 예방하는 것과는 관계가 없다.
NULL값은 연산에서 제외되기 때문이다.
인덱스를 효율적으로 액세스 할 수 없는 경우 -> LIKE 검색 문자열 앞 뒤에 모두 %기호가 있으므로 정상적인 인덱스 범위 스캔이 불가능하다.
where 절에는 집계함수가 올 수 없다. 집계함수는 having절에서 사용 가능
where 절에서 반환되는 행은 다중행이므로 = 기호로 받을 수 없고 다중 행 연산자 All, Any Exists로 받아야 함
인덱스가 사용되는 컬럼에 to_char() 형변환, NVL(key,0), name||''='lim 은 인덱스를 사용할 수 없는 조건이다.
|| 은 문자열을 결합하는 것이다.
하나의 행을 읽기 위해서는 인덱스를 사용하지 않고 테이블을 Full scan하는 것이 더 효율적이다.
랜덤 엑세스를 사용하는 것은 Nested Loop join 기법이다.
Sort Merge 조인이 Nested Loop join 보다 효율적으로 판단되는 경우 : 기본키와 외래키 관계에서 외래키에 인덱스가 없을 때
인덱스 칼럼 순서를 아무리 바꿔도 액세스 횟수에는 영향이 없다.
null 과 null 비교 연산자 -> 공집합(null)
coalesce 함수는 null이 아닌 첫 번째 값 반환하는 함수이다.
rownum을 1, 2, 3, 4 등으로 추출하려면 인라인 뷰를 사용해야함
SQL 개선 측면에서 서브 쿼리의 종류
1. ACCESS : 제공자 역할
2. Filter : 확인자 역할
3. Ealry Filter : 서브쿼리가 먼저 실행하여 걸러낸다.
세 개 다 쿼리의 변형이 없다.
<> any -> 하나라도 같지 않으면 참여
조인 조건이 없으면 카티션 곱을 수행한다.
ntile(4) <- data가 가질 수 있는 값의 범위는 1부터 4까지다.
LAG() 이전 행 LEAD() 다음 행
ALL -> and 조건 Any -> or 조건
기본키 값은 중복되서는 안된다.
union all 은 조회하는 데이터의 구조와 타입이 같아야 한다.
cum_dist : 0 < 결과값 <= 1
percent_rank : 0 <= 결과값 <= 1
SQL server null은 인덱스를 맨 앞에 저장, Oracle은 null을 맨 뒤에 저장
```
#### 1회기출
```
슈퍼타입과 서브타입 변환의 종류 : One To One(개별 테이블로 도출), Plus(분리해서 도출), Single Type(통합)
CONNECT BY는 부모 계층형 쿼리에서 부모 노드와 자식 노드 사이의 특정한 관계를 나타내는데 사용된다.
계층형 쿼리 start with 부모, connect by prior 자식 = 부모 꼴이면 순방향 전개이다.
dense_rank() : 중복된 순위 다음에는 바로 다음 순위를 부여, Rank() 중복된 순위 다음에는 중복된 순위 다음 순위 부여
unbounded preceding은 end point에 사용될 수 없다.
null이 null인지를 비교할 때는 알 수 없음 (오류가된다)
자동형변환 : To_char, To_date,
숫자형->Date는 자동형변환이 안된다.
SQL문을 ANSI 표준 SQL로 바꾸는 문장 -> left,right outer join, cross join이 아닌 inner join 이여야 함
(+)가 붙은 쪽이 null로 추가된다. (+)가 왼쪽에 있다면 outer join on의 왼쪽에 위치하게 한다.
스스로 생성되는 식별자 -> 내부, 다른 엔터티 간의 관계에 의해서 만들어지는 식별자 -> 외부
```
#### 2회기출
```
파티션기법의 종류: List Partition(관리자가 파티셔닝할 항목을 직접 지정), Range(범위 기준), Hash(해시 함수이용)
Compsite(Range와 Hash를 복합적으로 사용한다.)
실행 계획을 읽는 순서 : 안에서 밖으로 읽으면서 같은 레벨에서는 위에서 아래로 읽는다.
declare cursor-> open cursor -> fetch cursor -> close cursor
rownum은 oracle db, sql server에서는 top구에 with ties를 사용한다.
where 절에 같지않음이 들어가면 cross join 을 수행한다.
스칼라 -> 메인쿼리 o 메인쿼리 -> 스칼라 x
인라인 -> 메인쿼리 o 메인쿼리 -> 인라인 o
predicate information에서 행의 수를 9개로 제한 filter(ROWNUM<10)
ntile 함수 -> ntile(n) n만큼 파티션을 균등하게 분할한다. order by 1 오름차순으로 정렬후 균등하게 분할
lead(대상속성, 순서, 디폴트 값) 이후 순서(몇 칸?)에 나올 행을 출력한다. 반대는 Lag 함수 (이전 행)
nullif(a,b) a와 b가 같으면 null을 출력 같지 않으면 a를 출력한다.
Nested Loop join은 Random Access가 발생하여 성능이 떨어진다. 선행과 후행테이블을 선정하고 선행 조회 후
후행 테이블을 Random access로 조인한다.
```
#### 3회기출
```
내부 식별자란 엔티티 내부에서 스스로 생성되는 식별자, 외부 식별자는 다른 엔터티와의 관계로 인하여 만들어지는 식별자
고객 엔터티의 고객번호는 기본키로 내부 식별자에 해당, 계좌마스터의 고객번호는 외래키로 외부 식별자에 해당된다.
반정규화 절차 중 뷰 혹은 클러스터링 기법을 적용해야 하는 단계 -> 다른 방법 결정
order by 항목은 반드시 select 목록에 있는 칼럼의 자릿수를사용해야 한다. select N1 FROM <- 칼럼의 자릿수가 1이므로
order by는 1을 초과할 수 없다.
프로시저는 execute 명령어로 실행되고 트리거는 자동으로 실행된다.
SQL문의 실행 계획에서 Cardinality가 2이므로 조회되는 행의 수는 2개이다.
insert에서 특정 속성값을 지정들을 지정하지 않으면 오류가 발생한다.
window function에 대한 설명 : 성능이 느리다. group by와 window function은 병행해서 사용x, 내부 자동 튜닝 x
sum, min max와 같이 집계와 window 절과 함께 사용하면 집계의 대상이되는 레코드 범위를 지정할 수 있음 o
날짜형 데이터와 null을 더하면 null이 된다.
cube는 전체합계 1, job별 합계, deptno별 합계, job 별 합계, deptno에서의 job별 집계 -> cube(deptno, job)
```
#### 4회기출
```
업무에 의해서 만들어지는 식별자로 대체 여부로 분류되는 것은? -> 본질 식별자
natural join이 사용된 열은 식별자를 가질 수 없다.
like 연산으로 %나 _를 검색하기 위해서는 escape 명령어를 사용한다.
_와 % 앞에 escape로 특수 문자를 지정해야 검색한다.
2개의 행을 검색하고 싶으면 ROW_NUMBER() <= 2 와 같이 범위로 지정해야 한다.
데이터베이스 무결성을 확보하기 위한 방안 -> 제약조건, 트리거, 애플리케이션 무결성 검사 로직
무결성 확보 방안이 아닌 것 -> LOCK (LOCK은 동시성 제어)
Sort Merge Join은 동등조인 동등x조인에도 가능
옵티마이저는 인덱스가 존재해야 Nested Loop join을 선호한다.
Nested Loop join은 정렬을 하지 않음
SYSDATE를 To_DATE로 형변환하면 동일 타입을 반환하므로 에러가 발생한다.
```
#### 5회기출
```
순위 함수 사용 시 OVER() 내에 Order By는 필수이다.
select 구에는 group by 절에 있는 속성명만 나와야 한다.
NULL 값의 의미 : 아직 알려지지 않은 미지의 값으로 0 혹은 True와 False와는 다른 것이다.
where 절에서 사용되는 서브쿼리에서 메인 쿼리를 작성할 때 서브쿼리의 칼럼을 사용할 수 없다.
ROLE은 데이터베이스에서 Object의 권한을 묶어서 관리할 수 있다.
Random Access는 Nested Loop join 방식에서 사용하고 이로 인해 부하가 걸린다.
Inner join 이므로 join 조건을 만족하는 행만 가져와서 조건을 수행한다.
```
#### 6회기출
```
주식별자의 특징 : 최소성, 대표성(엔터티는 대표할 수 있어야 한다), 유일성(유일하게 식별한다), 불변성(자주변경되지 않아야한다)
집계함수 count(*) 함수는 조건절이 거짓일 때 0을 반환한다.
PL/SQL에서 테이블을 생성할 수 있다. 테이블을 생성하는 이유는 임시 테이블로 잠깐 사용하기 위한 용도가 많다.
<>Any:하나라도 같지 않으면 -> 모든 속성을 출력한다.
null에 사칙연산을 하면 null이다.
연산자의 우선순위 : 산술, 연결, 비교, is null, between, not , and , or (높은 것에서 낮은 것)
Decode(A.B,C,D) -> A와 B가 같으면 C 다르면 D
```
#### 7회기출
```
One to One Type : 슈퍼타입과 서브타입을 별도의 테이블로 도출한다. 테이블의 수가 많아서 관리가 어렵다 조인이 많이 발생한다.
Plus Type : 슈퍼타입과 서브타입 테이블로 도출한다. 조인이 발생하고 관리가 어렵다.
Single Type : 슈퍼타입과 서브타입을 하나의 테이블로 도출하고 조인 성능이 좋고 관리가 편하지만 IO 성능이 나쁘다.
데이터 모델링 : 추상화, 단순화, 명료화
Merge into 구문은 특정 키에 대해서 레코드가 있을 때에는 수정사항에 대해서 update, 레코드가 없을 때는 insert를 할 수 있는 구문이다.
nvl2(a,b,c) -> nvl2는 nvl과 decode를 하나로 만든 것으로 a가 null이면 c a가 null이 아니면 b를 출력한다.
decode(a,b,c) -> a와 b가 같으면 c 다르면 null을 출력한다.
not in (null) -> 공집합(null)
non equal join이란 '<=','>=','>','<'을 사용하는 조인으로 대부분 데이터베이스에서 잘 사용하지 않음
equal join이란 두 개의 테이블 간 칼럼 값이 같은것, 두 개의 테이블에서 교집합을 찾는다.
마스터 테이블과 슬레이브 테이블 간의 조인은 일반적으로 기본키와 외래키 사이에서 발생한다.
고유키(Unique Key) 제약이 설정되어도 null 값을 가질 수는 있다.
기본키로 이루어진 속성에서 unique index scan을 하려면 기본키 속성을 모두 사용해야 한다.
cross join : where 절에 join 추가 가능
natural join : where 절에 join 속성 추가할 수 없다. 
```
