# A. "유/무형" 으로 분류

## 1. 유형 엔티티

- 물리적 형태 O
- 안정적이고 지속적으로 활용됨.
- ex) 사원, 물품

## 2. 개념 엔티티

- 물리적 형태 X
- 개념적 정보로 구분됨
- ex) 조직

## 3. 사건 엔티티

- 업무를 수행함으로써 발생함
- 발생량이 많고 각종 통계에 이용됨
- ex) 주문



# B. "발생시점" 으로 분류

## 1. 기본 엔티티

- 업무에 원래 존재하는 정보
- 독립적으로 생성 가능
- 타 엔티티의 부모 역할 수행
- 주식별자를 상속받지 않고 자신의 고유한 주식별자 가짐
- ex) 사원, 부서, 상품

## 2. 중심 엔티티

- 기본엔티티에서 발생
- 업무에서 중심적인 역할
- 데이터의 양이 많이 발생함
- 다른 엔티티와 관계를 통해 많은 행위엔티티(밑) 생성
- ex) 계약, 주문, 매출

## 3. 행위 엔티티

- 2개 이상의 부모 엔티티로부터 발생
- 자주 내용이 바뀌고 데이터량 증가함
- 분석초기 단계에서 잘 나타나지 않고, 상세 설계나 프로게스와 상관모델링을 진행하며 도출됨.
- ex) 주문목록, 사원 변경 이력

출처:[https://brunch.co.kr/@ambler/55](https://brunch.co.kr/@ambler/55)
