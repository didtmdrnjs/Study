**DML 성능에 영항을 미치는 요소**

- 인덱스
- 무결성 제약
- 조건절
- 서브쿼리
- Redo 로깅
- Undo 로깅
- Lock
- 커밋

**대량 데이터 일괄 UPDATE하는 배치 프로그램 튜닝**

- update되는 컬럼을 포함한 인덱스를 Unusable상태로 변경 후, 작업완료 후에 재생성
- PK, FK 등 제약을 해제하고, 작업 완료 후에 재설정
- 병렬 처리 활용