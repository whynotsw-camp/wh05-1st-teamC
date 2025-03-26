# 프로젝트 기획서

## 1. 프로젝트 개요
- 프로젝트 주제: **개인 취향을 반영한 맞춤형 OTT 콘텐츠 및 영화 추천 시스템 개발**
- 목표: **1. 사용자 선호 분석: 시청 이력, 장르 선호도 등을 반영한 개인 맞춤형 프로필 생성. 2. 실시간 트렌드 반영: 최신 인기 콘텐츠와 개인 취향을 조합하여 동적 추천 제공. 3. 사용자 인터페이스 구축: 직관적인 UI/UX 설계를 통해 개인화된 추천 목록 제공**
  
### 주요 소비층: 
- OTT 구독 후에 '볼 건 많은데 볼 건 없네' 라고 느낀 사람
- OTT 플랫폼 가운데 본인에게 딱 맞는 서비스를 찾지 못한 사람
### 기대 효과:
- 개인화된 콘텐츠 탐색 효율성 향상
- 사용자가 선호하는 콘텐츠를 빠르게 찾을 수 있어 검색 시간 절감
- 시청 경험 최적화 및 사용자 만족도 증가
- 사용자 참여도 및 OTT 플랫폼 이용률 증가
- 맞춤형 추천으로 시청 시간이 증가하고, 플랫폼 이탈률 감소
- 지속적인 관심 콘텐츠 제공으로 사용자 충성도 강화
- 다양한 콘텐츠 소비 촉진
- 기존에 몰랐던 콘텐츠를 추천받아 시청 폭 확대
- 비주류 영화, 독립 영화, 해외 작품 등의 노출 기회 증가

### 팀원 소개

<table align="center">
  <tr align="center">
    <td width="200px">
      <img src="https://github.com/user-attachments/assets/0512d74a-1598-40ab-8c5d-fe948cb112e5" width="160" height="160"/><br/><br/>
      <strong>김찬호</strong><br/><br/>
      <a href="https://github.com/kkch1012">
        <img src="https://img.shields.io/badge/GitHub-kkch1012-181717?style=for-the-badge&logo=github&logoColor=white"/>
      </a>
    </td>
    <td width="200px">
      <img src="https://github.com/user-attachments/assets/c7f913ad-1e35-4326-9b8e-44a9cb038c9a" width="160" height="160"/><br/><br/>
      <strong>최동연</strong><br/><br/>
      <a href="https://github.com/choidongyeon01">
        <img src="https://img.shields.io/badge/GitHub-jcbhama0528-181717?style=for-the-badge&logo=github&logoColor=white"/>
      </a>
    </td>
    <td width="200px">
      <img src="https://github.com/user-attachments/assets/a10bd66d-c019-4c88-8c72-a8ddd3b6cc40" width="160" height="160"/><br/><br/>
      <strong>이성재</strong><br/><br/>
      <a href="https://github.com/sungjae0309">
        <img src="https://img.shields.io/badge/GitHub-sungjae0309-181717?style=for-the-badge&logo=github&logoColor=white"/>
      </a>
    </td>
  </tr>
</table>


### 화면 구성:

<p align="center">
  <img src="https://github.com/user-attachments/assets/f543a2e2-1fb9-48ae-a3c4-20798983b6f6" height="450"/>
  <img src="https://github.com/user-attachments/assets/21d4c16f-6e57-4dbe-8b53-d703aac6985a" height="450"/>
  <img src="https://github.com/user-attachments/assets/c63fd17d-fb1c-49a7-9a8b-dc73391c91f7" height="450"/>
  <img src="https://github.com/user-attachments/assets/5aa7ff97-ec45-414c-af5b-b2eaf0104015" height="450"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/26bf0f1c-7ac8-4f9f-9429-3e2bd66f5a6b" height="450"/>
  <img src="https://github.com/user-attachments/assets/6b596558-d27e-4fef-ae49-7cd62db5a4d5" height="450"/>
  <img src="https://github.com/user-attachments/assets/2b476060-f0be-4602-b436-4e0a226805c8" height="450"/>
  <img src="https://github.com/user-attachments/assets/a65b3c7e-a6c4-4347-be09-4a3ad5e7e069" height="450"/>
</p>

## 📖 프로젝트 일정 Gantt :fire:

```mermaid
gantt
    title 프로젝트 일정
    dateFormat  YYYY-MM-DD
    section 주제 선정 및 기획
    주제 선정 및 기획 확정   : a1, 2025-04-01, 7d
    맞춤형 추천 시스템 리서치 : a2, 2025-04-08, 7d

    section 데이터 수집 및 전처리
    데이터 수집 및 전처리 : a3, 2025-04-15, 14d
    콘텐츠 유사도 기반 추천 방식 실험 : a4, 2025-04-29, 7d

    section 추천 알고리즘 개발
    실시간 트렌드 반영 방식 기획 : a5, 2025-04-22, 7d
    추천 알고리즘 개발 시작 : a6, 2025-04-29, 61d

    section 추천 알고리즘 개선
    추천 알고리즘 개발 : a7, 2025-06-03, 7d
    유저 피드백 기반 개선 방안 구상 : a8, 2025-06-10, 7d

    section 추천 알고리즘 검증
    추천 알고리즘 개발 : a9, 2025-06-10, 7d
    모델 정확도 검증 테스트 : a10, 2025-06-17, 7d

    section UI/UX 설계 및 개발
    UI/UX 설계 시작 : a11, 2025-06-17, 7d
    추천 알고리즘 개발 계속 진행 : a12, 2025-06-24, 7d

    section 프론트엔드 개발
    프론트엔드 개발 시작 : a13, 2025-06-24, 7d
    추천 결과 시각화 카드 구성 : a14, 2025-07-01, 7d

    section 백엔드 연동 및 테스트
    백엔드 연동 : a15, 2025-07-01, 7d
    추천 알고리즘 튜닝 : a16, 2025-07-08, 7d
    시스템 통합 테스트 1차 : a17, 2025-07-08, 7d

    section 추천 알고리즘 고도화
    필터링 고도화 : a18, 2025-07-08, 7d
    추천 알고리즘 개선 마무리 : a19, 2025-07-15, 7d

    section UI 개선 및 사용자 테스트
    UI 개선 : a20, 2025-07-15, 7d
    사용자 테스트 : a21, 2025-07-22, 7d
    추천 시스템 최종 보완 : a22, 2025-07-22, 7d

    section 통합 테스트 및 기능 안정화
    2차 통합 테스트 : a23, 2025-07-22, 7d
    기능 안정화 : a24, 2025-07-29, 7d

    section 최종 테스트 및 배포
    최종 테스트 및 배포 : a25, 2025-08-01, 7d
    결과물 점검 및 리팩토링 : a26, 2025-08-08, 7d
```



### 데이터 베이스 설계(ERD):
![Image](https://github.com/user-attachments/assets/ad353fe3-68dc-4234-a4c1-5dcba012ab0b)

# 작업 분할 구조 (WBS)

## 1. 기획 📋
### 1.1 문제 정의 🔍
- 사용자 취향을 반영한 맞춤형 OTT 추천 시스템의 필요성 분석
- 기존 OTT 추천 시스템의 한계점 및 개선 방안 정리
- 목표 설정: 개인화된 추천 서비스 제공

### 1.2 데이터 요구사항 정의 📊
- 필요한 데이터 항목: 사용자 시청 이력, 장르 선호도, 콘텐츠 평점 등
- 데이터 유형 정의: 정형 데이터, 비정형 데이터
- 데이터 수집 방법 및 출처 선정

## 2. 데이터 수집 및 준비 🗃️
### 2.1 데이터 소스 조사 🌐
- OTT 플랫폼에서 제공하는 공개 API 또는 데이터셋 조사
- 타겟 데이터를 제공하는 제3자 데이터 소스 확인
- 데이터 소스 선정 및 수집 전략 수립

### 2.2 데이터 수집 및 저장 💾
- 필요한 데이터 수집: 시청 이력, 장르별 선호도, 사용자 피드백 등
- 데이터 저장소 설계: 데이터베이스 또는 클라우드 저장소 선정
- 데이터 수집 자동화 및 관리 시스템 구축

### 2.3 데이터 전처리 🧹
- 결측값 처리 및 이상치 제거
- 텍스트 데이터 정제: 불용어 처리, 토큰화 등
- 데이터 정규화 및 표준화 작업
- 전처리된 데이터 저장

## 3. 데이터 분석 및 모델링 📈
### 3.1 데이터 탐색 및 시각화 📊
- 기본 통계 분석: 평균, 분산, 빈도 분석 등
- 데이터 분포 시각화: 히스토그램, 박스플롯, 산점도 등
- 장르별 선호도 및 사용자 특성 분석

### 3.2 모델 선택 및 학습 🤖
- 추천 알고리즘 선택: 콘텐츠 기반 필터링, 협업 필터링 등
- 모델 학습: 훈련 데이터와 검증 데이터 분리, 교차 검증 실시
- 모델 튜닝 및 최적화

### 3.3 성능 평가 📊
- 모델 성능 평가 지표 정의: 정확도, 정밀도, 재현율 등
- 테스트 데이터셋을 이용한 모델 성능 평가
- 평가 결과에 따른 모델 개선 사항 도출

## 4. 결과 도출 및 보고 📑
### 4.1 결과 요약 📋
- 추천 시스템 성능 요약 및 결과 분석
- 사용자 맞춤형 추천 시스템의 개선점 및 강점 정리
- 프로젝트 목표 달성 여부 평가

### 4.2 보고서 작성 📝
- 전체 프로젝트 흐름 및 주요 작업 내용 정리
- 데이터 분석 및 모델링 과정, 결과 분석 포함
- 시스템 구현 및 테스트 과정 보고

### 4.3 최종 발표 🎤
- 프로젝트 결과 발표 준비: 발표 자료 준비, 발표 연습
- 최종 발표 및 데모 진행
- 발표 후 질의응답 및 피드백 반영






