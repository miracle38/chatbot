# Changelog

이 프로젝트의 모든 주요 변경사항을 이 파일에 기록합니다.

형식은 [Keep a Changelog](https://keepachangelog.com/ko/1.1.0/)을 따르며,
[유의적 버전(SemVer)](https://semver.org/lang/ko/)을 사용합니다.

- **MAJOR**: 기존 사용자 데이터/사용 흐름과 호환되지 않는 변경
- **MINOR**: 하위 호환되는 기능 추가
- **PATCH**: 하위 호환되는 버그 수정

## [Unreleased]

## [1.0.0] - 2026-08-20

### Added
- OfficeAgent 챗봇 위젯 연동 (카드 형식으로 여러 개 등록 가능)
- 카드 제목/설명을 OfficeAgent 봇 설정에서 실시간으로 가져와 표시
- 탭 파비콘 추가
- 하단 푸터 + 버전 정보 모달 추가

### Changed
- API 호출 결과를 10분 캐시해 새로고침 시 rate limit에 걸리는 문제 완화
