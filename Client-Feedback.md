클라이언트 업데이트 피드백 (v1.4)

알려진 문제

로그인 화면

- 로그인이 정상적으로 진행되지 않음 (클라이언트-서버간 코드구현 미완)
- 클라이언트 알림 팝업을 여닫을 때 소리가 출력되지 않음 (단순 경로 인식 문제)
- 계정 정보를 기억할 수 없음 (로컬드라이브에 계정 저장관련 코드 미완)
- 옵션 버튼을 클릭하면 옵션이 클라이언트 전체를 덮는 현상 (팝업 관련 코드를 수정하면서 스타일시트 파일이 망가지면서 생긴 문제 - 완전히 재수정해야함)

로비 화면

- 반응형으로 제작했지만 공간 활용이 적절하지 않음(resizer 관련 모듈을 써야하는것으로 보임)
- 인사이드 탭이 비활성화 되었음에도 클릭이 됨
- 프로필 탭은 장식임 (로그인 콜백이 없으니 이미지만 있음)
- 옵션 버튼을 클릭하면 옵션이 클라이언트 전체를 덮는 현상 (팝업 관련 코드를 수정하면서 스타일시트 파일이 망가지면서 생긴 문제 - 완전히 재수정해야함)
- 간혹 클라이언트를 처음 설치하고 게임 클라이언트 업데이트를 끝마치려하면 100%에서 더 이상 진행이 되지 않는 문제

개선 예정 사항

- 렌더러 코드의 최적화
( 현재 노바 클라이언트는 필요 없는 상황에서의 렌더러를 전부 페이지에 끌어모아 효율이없음, 자바스크립트 모듈화 등으로 최적화가 절실한 상황)
- 채팅 모듈 구현
( 가장 기본적인 커뮤니케이션 기능이 없음 )
- 친구 모듈 구현
( 채팅이 구현되고나면, 친구 추가 및 요청 수락 등을 구현해야함 )
- 프로필 구현
( 프로필 아이콘 설정, 레벨 확인, 닉네임 확인등이 필요함 )