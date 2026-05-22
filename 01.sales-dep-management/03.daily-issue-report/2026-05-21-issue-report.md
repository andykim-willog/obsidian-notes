_[__![:큰_주황색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e0.png)_ _SW 오류] 2건_  
  
▸ _이슈 #1_ | ![:큰_주황색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e0.png) 높음 | 담당: Rei, Philip (Andy CC)  
![:압정:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f4cc.png) **CoupangLS 계정/측정공간 매칭 오류**  
쿠팡로지스틱스([mailto:soyu4@coupangls.com](mailto:soyu4@coupangls.com))에서 "계정 통합 및 측정공간 매칭이 잘못되어 있음" 보고. 예시: 인천8 계정에 인천2 적재 관련 측정공간이 매칭됨. 빠른 수정 및 당일 잔여 162개 출고 확인 요청.  
![:망치와_렌치:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f6e0-fe0f.png) _권고 조치:_

1. [즉시] Philip/Rei — 계정별 측정공간 매칭 전수 확인 및 오류 수정
2. [즉시] CoupangLS 유수민에게 "확인 중" 중간 응답 발송

  
  
▸ _이슈 #3_ | ![:큰_노란색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e1.png) 중간 | 담당: Evan(CX), Charles_Backend, Min(Frontend)  
![:압정:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f4cc.png) **쿠팡 계정 엑셀 업로드 오류** ([mailto:yaj_2@coupang.com](mailto:yaj_2@coupang.com))  
동일 파일을 다른 계정에서는 정상 업로드되나 해당 계정에서만 실패. nickname 속성 없음으로 인한 분기 로직 버그. Charles_Backend 확인 완료, 프론트엔드 분기 로직 제거 예정.  
![:망치와_렌치:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f6e0-fe0f.png) _권고 조치:_

1. [당일] Min — 프론트엔드 분기 로직 제거 배포 일정 확인
2. [당일] Evan — 고객(쿠팡)에게 수정 예상 일정 안내

  
  
━━━━━━━━━━━━━━━━━━━━  
  
_[__![:큰_주황색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e0.png)_ _IoT 디바이스 장애] 2건_  
  
▸ _이슈 #2_ | ![:큰_주황색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e0.png) 높음 | 담당: Selly  
![:압정:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f4cc.png) **T1G 디바이스 배터리 충전 불량 (3대)**  
T1G26M160011(55%), T1G26M160013(50%), T1G26M040015(55%) — GNSS OFF 변경 이후에도 배터리 미완충. 2일째 충전 중이나 거의 올라가지 않음. Rei_운영기획에게 확인 요청됨.  
![:망치와_렌치:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f6e0-fe0f.png) _권고 조치:_

1. [즉시] Rei_운영기획 — 3개 기기 배터리/충전 이상 원인 확인
2. [당일] Selly — 고객사에 현재 확인 중임을 중간 안내
3. [단기] 동일 배치 T1G 기기 배터리 상태 전수 점검

  
  
▸ _이슈 #4_ | ![:큰_노란색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e1.png) 중간 | 담당: Rei, Jeymi  
![:압정:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f4cc.png) **오너스씨앤에어 IoT 디바이스 교체 진행 중** (대응 중)  
기존 디바이스 문제로 FedEx 통해 교체 기기 발송 완료 (운송장: 872019661177). 기존 기기는 현지 폐기 안내. "서비스 이용에 불편을 드려 죄송합니다" 고객에게 사과 완료.  
![:망치와_렌치:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f6e0-fe0f.png) _권고 조치:_

1. [단기] Rei — 교체 기기 수령 확인 후 고객 피드백 수집
2. [단기] Jeymi — Pipedrive 딜 노트에 교체 이력 기록

  
  
━━━━━━━━━━━━━━━━━━━━  
  
![:번쩍:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/26a1.png) _즉각 조치 필요 (__![:큰_주황색_원:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f7e0.png)_ _높음)_

- **Rei/Philip**: CoupangLS 측정공간 매칭 오류 전수 확인 및 수정
- **Selly/Rei_운영기획**: T1G 3대 배터리 충전 불량 원인 파악