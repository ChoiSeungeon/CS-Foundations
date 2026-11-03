# ARCH-07 CPU 캐시 — 연결 설명 기록

- 목차: [컴퓨터구조](../curriculum/tracks/01-computer-architecture.md).
- 세션: [2026-11-03](../sessions/2026-11-03-01.md#연결-주제).
- 답변 원문과 예시 조건: [ARCH-06](ARCH-06-memory-hierarchy.md).
- 현재 상태는 [진도표](../tracking/progress.md)에서 관리한다.

## 실제 다룬 범위와 증거

L1·L2 캐시의 목적을 학습자가 먼저 설명했다. 캐시 라인의 블록 전송과 캐시에 있으면 RAM에서 다시 가져오지 않아도 되는 흐름을 다뤘다.

교육용 16바이트 라인, 빈 캐시, 미리 읽기와 교체가 없는 조건에서 32→36→40→44→48의 라인 가져오기가 2번이라고 답했다. 32→48→64→80→96을 각 한 번 읽으면 함께 가져온 다른 위치를 활용하지 못한다는 이유도 설명했다. 기본 교체·쓰기 정책의 이해로 확대하지 않는다.

## 원문 확인

- URL: https://computationstructures.org/lectures/caches/caches.html
- 제목·절: L14: The Memory Hierarchy, SRAM cache, hit/miss, block size 설명 단락.
- 확인일: 2026-11-03(Asia/Seoul), 웹 도구로 직접 확인.
- 적용 범위: 일반 원리와 교육용 조건. 16바이트를 실제 CPU의 고정 라인 크기로 일반화하지 않는다.

## 남은 목표

hit·miss를 용어와 흐름으로 재설명하기, 기본 교체·쓰기 정책, 용량·지연 절충, 서로 다른 조건 변화 2개, 원문과 대조한 독립 재설명, 간격 복습. 주제 전체의 필수 과정이 남아 있으므로 N1로 기록한다.
