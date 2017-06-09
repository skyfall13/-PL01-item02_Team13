# [PL01]item02_Team13
+ 201204441 김수현
+ 201302363 권오현
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
### 2017-06-08 오전 6:53 수정 내역 (by 김 수 현)
+ define test 5번 안됐던 내역 수정함.
+ lookup_createNode_or_str 수정함.
---
### 2017-06-08 오후 11:58 수정 내역 (by 권오현 & 김수현)
+ 권오현 define refactory 
+ 김수현 refactory 시에 생긴 간단한 오류들 수정
+ test 케이스 7번외에 define으로 할 수 있는 모든 형태 가능.
+ lookup_createNode_or_str 함수 삭제
+ lookup_table 크게 변경
+ print_node 의 ID, INT부분 변경됨.
+ run_expr 부분에서 ID부분 변경됨.
+ insert_table 변수 삭제됨.
+ 위의 변경에 따른 모든 연산 부분이 수정됨.
---
### 2017-06-09 오후 17:32 수정내역 (by 권오현)
+ run_lambda 구현완료
+ testcase 16번까지 테스트 해봄. 
+ 위의 lambda추가에 따른 run_expr 등의 구현부분 변경을 진행함.
---
# 파이썬 버전
+ Python 2.7.13 version
