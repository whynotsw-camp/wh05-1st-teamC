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

## 📖 Gantt :fire:

```mermaid
gantt
    title 프로젝트 일정
    dateFormat  YYYY-MM-DD
    section 주제 선정 및 기획
    주제 선정 및 기획 확정  :a1, 2024-04-01, 7d
    맞춤형 추천 시스템 리서치 :after a1, 7d

    section 데이터 설계 및 기획
    사용자 데이터 구조 설계 :a2, 2024-04-08, 7d
    시청 이력/장르 기반 개인화 로직 기획 :after a2, 7d

    section 데이터 수집 및 전처리
    데이터 수집 및 전처리 :a3, 2024-04-15, 7d
    콘텐츠 유사도 기반 추천 방식 실험 :after a3, 7d

    section 추천 알고리즘 개발
    실시간 트렌드 반영 방식 기획 :a4, 2024-04-22, 7d
    추천 알고리즘 개발 시작 :after a4, 7d

    section 추천 알고리즘 개발
    추천 알고리즘 개발 :a5, 2024-04-29, 7d
    사용자-콘텐츠 매칭 로직 설계 :after a5, 7d

    section 추천 알고리즘 개선
    추천 알고리즘 개발 :a6, 2024-05-06, 7d
    유저 피드백 기반 개선 방안 구상 :after a6, 7d

    section 추천 알고리즘 검증
    추천 알고리즘 개발 :a7, 2024-05-13, 7d
    모델 정확도 검증 테스트 :after a7, 7d

    section UI/UX 설계 및 개발
    UI/UX 설계 시작 :a8, 2024-05-20, 7d
    추천 알고리즘 개발 계속 진행 :after a8, 7d

    section 프론트엔드 개발
    프론트엔드 개발 시작 :a9, 2024-05-27, 7d
    추천 결과 시각화 카드 구성 :after a9, 7d

    section 백엔드 연동 및 테스트
    백엔드 연동 :a10, 2024-06-03, 7d
    추천 알고리즘 튜닝 :after a10, 7d
    시스템 통합 테스트 1차 :after a10, 7d

    section 추천 알고리즘 고도화
    필터링 고도화 :a11, 2024-06-10, 7d
    추천 알고리즘 개선 마무리 :after a11, 7d

    section UI 개선 및 사용자 테스트
    UI 개선 :a12, 2024-06-17, 7d
    사용자 테스트 :after a12, 7d
    추천 시스템 최종 보완 :after a12, 7d

    section 통합 테스트 및 기능 안정화
    2차 통합 테스트 :a13, 2024-06-24, 7d
    기능 안정화 :after a13, 7d

    section 기획서 및 발표 준비
    기획서/문서 정리 :a14, 2024-07-01, 7d
    최종 발표 구조 설계 시작 :after a14, 7d

    section 발표 자료 준비
    포스터, 시연 자료 준비 :a15, 2024-07-08, 7d
    사용자 시나리오 보강 :after a15, 7d

    section 발표 및 마무리
    발표 리허설 :a16, 2024-07-15, 7d
    시스템 정리 및 마무리 :after a16, 7d

    section 최종 테스트 및 배포
    최종 테스트 및 배포 :a17, 2024-07-22, 7d
    결과물 점검 및 리팩토링 :after a17, 7d

    section 최종 점검 및 제출
    최종 점검 및 제출 준비 :a18, 2024-07-29, 3d

    section 최종 발표
    최종 발표 및 데모 진행 :a19, 2024-08-01, 4d
```



### 데이터 베이스 설계(ERD):
![Image](https://github.com/user-attachments/assets/ad353fe3-68dc-4234-a4c1-5dcba012ab0b)






