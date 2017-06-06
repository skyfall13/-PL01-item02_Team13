# [PL01]item02_Team13
+ 201204441 김수현
+ 권오현
+ 201102448 사명기

---
# 변경사항
### 2017-06-06 (by 김수현)
+ define, insert_table, lookup_table 정의 및 1단계 구현완료 
+ ex) (define a 1) 형태의 1단계 define이 구현됨.
+ 추후 2단계 (define a (+ 1 3)) 형태 구현 예정.
+ 추후 3단계 (define a '(1 2 3)) 구현 예정.
+ 테스트를 위한 print 문(log대신 넣은)을 제거할 예정.
---
### 2017-06-07 오전 3:14 내역 (by 김 수 현)
+ lookup_createnode_or_str 함수 새로 만듬.
+ define 1단계 2단계 사직연산까지 완료함.
+ define 3단계에서 cdr car등에서 생기는 문제 수정중.
---
### 2017-06-07 오전 4:33 수정 내역 (by 김 수 현)
+ lookup_createNode_or_str 함수에 flag를 넣음. 
+ null_q에서 문제 발생 (define a 1) 후 (null? a)시 문제 발생. LIST노드로 반환 필요. 
+ null_q, eq_q, atom_q 와 lt, et, rt 등 define이 적용되도록 할 필요가 있음.
---
# 파이썬 버전
+ Python 2.7.13 version
