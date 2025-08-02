![미리보기](https://github.com/jvisualschool/sound_meter_web/blob/main/screenshot.png)

# 🎯 소음 측정기 Sound Meter

실시간 소음 측정과 팀별 기록 관리를 제공하는 웹 애플리케이션입니다. 발표나 이벤트에서 팀별 함성 크기를 재미있게 겨룰 수 있습니다.

## ✨ 주요 기능

### 📊 실시간 소음 측정
- 마이크를 통한 실시간 데시벨(dB) 측정
- 원형 미터와 레벨 바로 시각적 표시
- 현재/최대/평균 소음 레벨 추적

### 📈 실시간 데이터 시각화
- Chart.js를 활용한 실시간 그래프
- 지난 20개 측정값의 변화 추이 표시
- 부드러운 애니메이션과 반응형 차트

### 🏆 팀 기록 관리
- 팀별 최고 기록 저장
- 리더보드 순위 표시 (🥇🥈🥉)
- localStorage를 통한 로컬 데이터 저장

### 🎨 모던 UI/UX
- 그라디언트 배경과 글래스모피즘 디자인
- 반응형 레이아웃 (모바일/데스크톱 지원)
- 부드러운 애니메이션과 시각적 피드백

## 🚀 시작하기

### 사전 요구사항
- 모던 웹 브라우저 (Chrome, Firefox, Safari, Edge)
- 마이크 접근 권한

### 설치 및 실행
1. 저장소 클론
```bash
git clone https://github.com/yourusername/sound-meter-web.git
cd sound-meter-web
```

2. 웹 서버로 실행 (로컬 파일 열기로는 마이크 권한 제한)

3. 브라우저에서 접속
```
http://localhost:8000
```

## 📱 사용법

### 1. 소음 측정
1. **"측정 시작"** 버튼 클릭
2. 마이크 권한 허용
3. 실시간으로 소음 레벨 확인
4. **"측정 중지"** 버튼으로 종료

### 2. 팀 기록 저장
1. 소음 측정 후 팀 이름 입력
2. **"최고 기록 저장"** 버튼 클릭
3. 리더보드에서 순위 확인

### 3. 기록 관리
- 동일 팀명으로 재등록 시 더 높은 점수만 업데이트
- **"전체 기록 삭제"**로 리더보드 초기화

## 🛠 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS, Font Awesome, Google Fonts
- **Charts**: Chart.js
- **Audio**: Web Audio API
- **Storage**: localStorage

## 🎯 데시벨 참고 기준

| 데시벨 | 소음 수준 | 예시 |
|--------|-----------|------|
| 0-30 dB | 매우 조용 | 도서관, 속삭임 |
| 30-60 dB | 조용 | 일반 대화, 사무실 |
| 60-90 dB | 보통 | 텔레비전, 카페 |
| 90-120 dB | 시끄러움 | 지하철, 콘서트 |
| 120+ dB | 위험 수준 | 제트기 이륙 |

## ⚠️ 안전 가이드

- **120dB 이상**은 청력에 해로울 수 있습니다
- 측정 시간은 **10초 이내**로 제한하세요
- 마이크와 **적절한 거리**를 유지하세요
- 과도한 소음 노출을 피하세요

## 🔧 브라우저 호환성

| 브라우저 | 지원 버전 |
|----------|-----------|
| Chrome | 66+ |
| Firefox | 60+ |
| Safari | 11.1+ |
| Edge | 79+ |

## 📄 라이선스

MIT License - 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 문의

프로젝트에 대한 질문이나 제안이 있으시면 이슈를 생성해 주세요.

---

**🎉 즐거운 소음 측정하세요!**
