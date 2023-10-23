# DATABASE
study for database

## 질문으로 시작하자.
- "어떤 데이터베이스 혹은 데이터베이스들의 어떤 조합이 우리 문제를 가장 잘 해결해 주는가?"
- "반드시 이것을 사용해야 하나?"

- 어떤 현태로 데이터를 저장하는가?
| 관계형(relational) | PostgreSQL |
| 키-값(key-value) | Riak, Redis |
| 컬럼형(column-oriented) | HBase |
| 문서형(document-oriented) | MongoDB, CouchDB |
| 그래프(graph) | Neo4J |

## PostgreSQL
- 집합 이론을 기반으로 하는 시스템인 관계형 데이터베이스 관리 시스템이다.
- 뛰어난 오픈 소스 RDBMS

### 관계형 데이터베이스가 널리 보급된 이유
1. 방대한 툴킷(트리거, 저장 프로시저, 진보된 인덱스)
2. ACID 준수에 따른 데이터 안정성 및 마인드 쉐어
3. 쿼리 능력

- ACID란?
- 트랜잭션 단위의 데이터 변경에 따른 데이터의 일관성과 안전성을 위지하기 위한 규약
  - Atomic(원자성)
  - Consistent(일관성)
  - Isolated(독립성)
  - Durable(지속성)
