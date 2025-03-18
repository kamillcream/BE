# IoT 센서 데이터 대시보드

- 개발 기간: 2024.10 - 2024.12
- 프로젝트 : 2024-2 ‘사물인터넷프로그래밍’ 과목 프로젝트

⸻

## 프로젝트 개요

- 본 프로젝트는 IoT 센서 데이터를 1초 단위로 서버에 전송 및 실시간 처리하는 시스템을 구현하는 것을 목표로 하였습니다.
- WebSocket + Kafka를 활용하여 클라이언트 요청 없이 자동으로 센서 데이터를 송신하는 구조를 설계했습니다.

⸻

## 핵심 기능 및 차별점

- 1초 단위 실시간 센서 데이터 수신 및 처리
- 클라이언트 부담 제거: 요청 없이 자동으로 최신 데이터 전송
- 웹소켓(WebSocket) 기반 단방향 송신: 서버에서 클라이언트로 실시간 데이터 푸시
- Kafka 적용: 센서 수 증가로 인한 데이터 확장성 고려

⸻

## 도전 과제 & 해결 방법
- 1초 단위로 서버에 도착하는 센서 데이터 처리 : 실시간 데이터 스트림에 용이한 Kafka 적용
- 클라이언트 요청 없이 실시간으로 최신 데이터 전달 : WebSocket 기반 단방향 송신으로 클라이언트 요청없이 데이터 전송

⸻

## 사용 기술 및 인프라
### 백엔드
- Spring Boot
- MySQL
### DevOps
- Github Actions
- Google Cloud Platform

  

