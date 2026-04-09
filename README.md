# Baekjoon Practice Log / 백준 문제풀이 기록

Baekjoon Online Judge 문제 풀이를 자동으로 기록하는 저장소입니다. 저장소 이름에 `test`가 남아 있지만 일회성 테스트 레포가 아니라, 실제 풀이 코드와 시행착오를 누적하는 알고리즘 학습 기록으로 사용하고 있습니다.

This repository is an automatically synchronized problem-solving log for **Baekjoon Online Judge**. Despite the historical `test` suffix in the repository name, it is used as a real archive of accepted solutions, failed attempts, and practice iterations rather than as a disposable test repository.

## What is stored here / 저장 내용

- BaekjoonHub로 동기화된 문제별 풀이 코드
- 문제 설명 및 메타데이터가 포함된 문제별 README
- 정답 코드와 일부 실행/오답 시도 기록
- Python 중심의 알고리즘 문제풀이 학습 이력

## Repository layout / 구조

문제는 BaekjoonHub가 생성하는 디렉터리 구조를 그대로 유지합니다.

```text
프로그래머스/
└── ...problem directory...
    ├── README.md
    └── solution.py
```

The generated directory names and filenames are intentionally preserved so new submissions can continue to sync without a custom migration layer.

## Related study repository / 관련 학습 저장소

- [`codetest-study`](https://github.com/oosuhada/codetest-study) contains broader coding-test notes, cheatsheets, and manually organized study material.
- This repository focuses on the **automatic submission history itself**, so it is not a duplicate of `codetest-study`.

## Automation

Solutions are synchronized with [BaekjoonHub](https://github.com/BaekjoonHub/BaekjoonHub).

---

이 저장소는 완성된 애플리케이션 포트폴리오가 아니라 꾸준한 문제 해결 연습과 학습 과정을 보여주는 기록용 저장소입니다.

This is a study log rather than a product portfolio project; the value is in the accumulated problem-solving history and iteration trail.

## Architecture & Topics / 아키텍처 및 주제

**Architecture / 아키텍처**<br>
[`append-only-history`](https://github.com/topics/append-only-history) · [`automated-ingestion`](https://github.com/topics/automated-ingestion) · [`repository-as-database`](https://github.com/topics/repository-as-database) · [`event-driven-automation`](https://github.com/topics/event-driven-automation)

**Project context / 프로젝트 맥락**<br>
[`algorithm-practice`](https://github.com/topics/algorithm-practice) · [`algorithms`](https://github.com/topics/algorithms) · [`coding-challenge`](https://github.com/topics/coding-challenge) · [`coding-interview`](https://github.com/topics/coding-interview) · [`coding-test`](https://github.com/topics/coding-test) · [`competitive-programming`](https://github.com/topics/competitive-programming) · [`computer-science`](https://github.com/topics/computer-science) · [`data-structures`](https://github.com/topics/data-structures) · [`learning`](https://github.com/topics/learning) · [`problem-solving`](https://github.com/topics/problem-solving) · [`programmers`](https://github.com/topics/programmers) · [`study`](https://github.com/topics/study) · [`study-log`](https://github.com/topics/study-log)

**Implementation stack / 구현 스택**<br>
[`baekjoonhub`](https://github.com/topics/baekjoonhub) · [`python`](https://github.com/topics/python)
