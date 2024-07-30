# SourceSprout 🌱

SourceSprout는 오픈소스 프로젝트를 위한 크라우드펀딩 플랫폼입니다.

## 핵심 기능

- [ ] 사용자 인증
    - 회원가입 (이메일, 비밀번호)
      - 이메일 중복 확인
      - 비밀번호 유효성 검사 (최소 8자, 문자/숫자 조합)
      - 회원가입 시 자동으로 USER 권한 부여
    - 로그인/로그아웃
      - 로그인 성공 시 JWT 토큰 발급
      - 로그아웃 시 토큰 무효화

- [ ] 내부 계좌 시스템
    - 계좌 생성
      - 계좌번호 자동 생성 (예: UUID 또는 고유한 일련번호)
      - 초기 0원  
    - 계좌 잔액 조회
      - 사용자 인증 후 본인 계좌 잔액 조회 가능 
    - 금액 충전 기능
      - 충전 금액 입력 후 충전
      - 충전 한도 설정 

- [ ] 펀딩 기능
    - 프로젝트 펀딩 (내부 계좌 간 송금)
      - 펀딩 금액 입력
      - 계좌 잔액 확인 및 송금 처리 
    - 펀딩 이력 조회
        - 최신순 정렬
        - 커서 기반 페이징 적용(기본 10개)

- [ ] 프로젝트 관리
    - 프로젝트 등록 (제목, 설명, 목표금액)
    - 프로젝트 목록 조회
      - 로그인하지 않은 사용자도 조회 가능     
      - 최신순 정렬 (생성 시간 기준 내림차순)
      - 커서 기반 페이징 적용(기본 20개)

## 기술 스택

- 백엔드: Spring Boot
- 데이터베이스: MySQL
- 프론트엔드: -

## ERD
![source-sprout](https://github.com/user-attachments/assets/2559891a-7596-4d64-8e65-9de721a187a9)


## 설치 및 실행 방법

(개발 진행 후 작성 예정)

## 향후 계획

- 보안 강화
- 실제 결제 시스템 연동
- 외부 은행 계좌 연결

## 라이선스

MIT License
