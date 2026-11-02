# 기준 자료와 출처 사용법

2026-11-02에 아래 입구 페이지의 공개 목차·제공 범위를 확인했다. 자체 학습 목차를 교차 점검하는 출발점이며, 각 세부 주제가 해당 페이지에서 모두 검증됐다는 뜻이 아니다. 수업 전에 해당 절을 실제로 읽고 노트에 URL·절 제목·확인일·버전을 추가한다. 특정 책 구매나 강의 완주가 필수는 아니다.

| 키 | 자료 | 사용할 범위 |
|---|---|---|
| CS50 | [Harvard CS50 syllabus](https://cs50.harvard.edu/x/syllabus/) | 자료 표현·메모리·자료구조·SQL·인터넷 입문의 목차 확인 |
| MIT-ARCH | [MIT 6.004](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/) | 컴퓨터구조의 추상화·명령·메모리·I/O 관련 자료 선택 |
| OSTEP | [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) | 가상화·동시성·영속성 영역의 무료 공개 장 |
| MIT-DS | [MIT 6.006](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) | 복잡도·자료구조·탐색·정렬의 원리. 코딩 테스트 과제는 제외 |
| KUROSE | [저자 온라인 강의](https://www-net.cs.umass.edu/kurose_ross/lectures.php) | 응용·전송·네트워크·링크·보안 계층. 전체 교재 무료 제공과 혼동하지 않음 |
| CMU-DB | [CMU Spring 2026 schedule](https://15445.courses.cs.cmu.edu/spring2026/schedule.html) | 관계 모델·저장·인덱스·실행·트랜잭션·복구의 범위 확인 |
| MYSQL | [MySQL 8.4 manual](https://dev.mysql.com/doc/refman/8.4/en/) | SQL·InnoDB의 구체 동작. 설치 버전 확인 후 해당 버전 문서 선택 |
| MYSQL-INDEX | [Optimization and Indexes](https://dev.mysql.com/doc/refman/8.4/en/optimization-indexes.html) | 인덱스 선택과 비용의 원문 입구 |
| MYSQL-TX | [InnoDB Transaction Model](https://dev.mysql.com/doc/refman/8.4/en/innodb-transaction-model.html) | 격리·일관 읽기·잠금 읽기·커밋과 롤백 |
| DEVJAVA | [Dev.java tutorials](https://dev.java/learn/) | 언어·객체·컬렉션·JVM 등 설명의 입구 |
| JLS | [Java Language Specification SE 25](https://docs.oracle.com/javase/specs/jls/se25/html/index.html) | 타입·표현식·예외·메모리 모델의 기준. 실행 JDK 버전에 맞춰 대조 |
| JVMS | [JVM Specification SE 25](https://docs.oracle.com/javase/specs/jvms/se25/html/index.html) | JVM 실행·런타임 데이터 영역·클래스 로딩. 구현 세부와 구분 |
| JUNIT | [JUnit user guide](https://docs.junit.org/current/user-guide/) | 테스트 작성·실행의 실제 기능. 단위/통합 경계는 검증 대상과 의존성으로 설명 |
| OWASP | [Web Security Testing Guide](https://owasp.org/projects/web-security-testing-guide) | 인증·인가·세션·입력 검증 등 보안 검증 관점 |
| SPRING | [Spring Framework reference](https://docs.spring.io/spring-framework/reference/index.html) | DI·프록시·트랜잭션·테스트·웹 실행. 프로젝트 버전에 맞춰 선택 |
| KAFKA | [Apache Kafka documentation](https://kafka.apache.org/documentation/) | 메시징·전달·설계·설정. 실제 버전 선택 필요 |
| REDIS | [Redis docs](https://redis.io/docs/latest/) | 자료형·캐시·원자 실행과 운영 기능. 개별 절 추가 확인 |

소프트웨어 설계·형상 관리·분산 시스템 확장 등 위 입구만으로 근거가 부족한 항목은 수업 전 별도 1차 자료를 선정한다. 미선정 상태를 숨기지 않는다. 참고 자료의 목차와 자체 목차를 주기적으로 대조하되, 모든 CS 학문 영역을 완전히 포괄한다고 주장하지 않는다.

## 영어 자료

먼저 한국어 예시로 질문을 이해한다. 해당 절의 핵심 정의·그림·문단을 짧게 읽고 원어 키워드와 한국어 의미를 연결한다. 전체 영어 강의를 먼저 완주시키지 않는다. 저작물 전체를 저장소에 복제하지 않고 링크와 자신의 설명을 남긴다.

## Codex 환경 인계 참고

- [공식 Cloud 안내](https://learn.chatgpt.com/docs/cloud): 저장소 선택과 Cloud 환경 준비의 기준.
- [공식 AGENTS.md 안내](https://learn.chatgpt.com/docs/agent-configuration/agents-md): 저장소 단위 지침의 기준.

공식 문서는 이 채팅의 대화 기억·로컬 파일·설치 프로그램이 다른 채팅으로 자동 전달됨을 보장하지 않는다. 본 저장소는 파일로 맥락을 재구성하는 방식을 사용한다. 이는 이 학습을 위한 설계 선택이다.
