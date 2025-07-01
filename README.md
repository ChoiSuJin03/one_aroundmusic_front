# Around Music

React Native를 활용한 AR 음악 공유 플랫폼의 앱입니다.

---

## 프로젝트 소개

AR 기술을 활용해 사용자가 음악을 공유하고, 다른 사람들과 감성을 나누는 소셜 네트워크 앱입니다.

---

## 주요 기능

- **AR 플레이어**: 공간에 떠 있는 AR 뮤직 플레이어로 감상  
- **인터랙션**: 댓글, 공유 기능  
- **팔로우 & 피드 기능**: 친구의 음악 업데이트와 이력 확인

---

## 시연 화면

### 1. 앱 실행 – AR 플레이어

<div style="display: flex; align-items: flex-start; gap: 20px;">
  <p>
    AR 화면 위에 음원 커버 이미지와 재생 버튼이 배치되어 있으며,  
    사용자가 실제 공간 위에서 음악을 감상할 수 있도록 구현되어 있습니다.  
    현실 공간과 디지털 콘텐츠가 융합된 사용자 경험을 제공합니다.
  </p>
  <img src="images/ar_player.png" width="40%">
</div>

---

### 2. 홈 피드 화면

<div style="display: flex; align-items: flex-start; gap: 20px;">
  <p>
    내가 등록한 음악과 최신 공유된 음악 리스트를 한눈에 확인할 수 있는 메인 피드 화면입니다.  
    각각의 카드에는 곡 제목과 등록 위치 정보가 포함되어 있으며, 간단한 검색도 가능합니다.
  </p>
  <img src="images/feed_screen.png" width="40%">
</div>

---

### 3. 음악 업로드 폼

<div style="display: flex; align-items: flex-start; gap: 20px;">
  <p>
    음악 파일과 커버 이미지, 곡 제목, 장르, 위치 등의 메타데이터를 입력하고 업로드할 수 있는 화면입니다.  
    사용자가 직접 콘텐츠를 생성할 수 있는 핵심 기능입니다.
  </p>
  <img src="images/upload_screen.png" width="40%">
</div>

---

### 4. 댓글 화면

<div style="display: flex; align-items: flex-start; gap: 20px;">
  <p>
    특정 곡에 대해 다른 사용자와 감정을 공유할 수 있는 댓글 창입니다.  
    사진과 함께 피드백을 남기며 공감과 소통을 유도합니다.
  </p>
  <img src="images/interactions.png" width="40%">
</div>

---

## 👥 팀 소개

총 프론트엔드 5명, 백엔드 2명이 협업한 프로젝트입니다.

---

## 🏁 실행 방법

```bash
git clone https://github.com/ChoiSuJin03/one_aroundmusic_front.git
cd one_aroundmusic_front

npm install
# 또는
yarn install

# iOS 시뮬레이터 실행
npx react-native run-ios

# Android 시뮬레이터 실행
npx react-native run-android
