# 프로젝트명
당근 스트리밍 마켓
# 프로젝트기간
2021.09.27. ~ 2021.10.08
# 개발인원
고대연, 김진호, 김영대, 최진경
# 개발환경
- Visual Studio 2019 / C# Winform
- Linux Ubuntu 20.04 / C++ 9.3.0 / Visual Studio Code 1.57.1 / MySQL
# 프로그램 소개
- 실시간 스트리밍을 활용한 중고거래 플랫폼 프로그래밍
# 주요기능
- 판매시 물건을 설명할수 있는 실시간 1:다 스트리밍 기능 
- 채팅 기능
- 일반판매, 경매판매 기능
- 사용자 정보 설정 가능
- 사용자마다 신뢰도가 있고 거래후기에 따라 변함 
# 느낀점
통신프로토콜, UI에 공부가 많이 되었던 프로젝트 였다.
스트리밍을 하기위해 ffmpeg와 vlc를 이용한 RTSP방식을 사용했는데 ffmpeg와 vlc를사용하는 방법과 C#에서 연결하는 방법을 몰라서 많이 해맸었다.   
특히 ffmpeg는 사용시 여러가지 옵션으로 스트리밍 뿐만아니라 동영상 편집도 할수있다는걸 알 게 되었고 나중에 시간이 되면 동영상 편집기도 만들어보고 싶다는 생각을 했다.   
프로젝트가 진행되면서 실제로 상용되고 있는 스트리밍은 RTMP방식을 이용하고 있다는걸 알게 되었고 시도하려 했지만 웹을 통해서 한다는점, 서버가 따로 필요하다는 점, 시간부족으로 인해 결국 RTSP로 하게되었지만 나중에 비슷한 프로그램을 만들일이 생기면 RTMP방식으로 만들어 보고 싶다는 생각이 들었다.
 그동안 UI에 공부를 소홀히 했었는데 이번기회에 공부할겸 프로젝트에서 UI를담당하여 진행했다.
여러가지 찾아보니 그동안 UI는 단순히 꾸미는 것만 있는줄 알았는데 깔끔한 코드와 코드로 UI 를 만들기 까다로운 부분을 위해 UI쪽도 공부할 필요성을 느꼈다.
각진 기본 컨트롤을 오버라이딩을 통해 둥글게 만들거나 Graphics클래스를 활용하여 원하는 도형을 만들어 놓을수 있다는점,
사용자정의 컨트롤로 내가 원하는 컨트롤들을 조합하여 새로운 컨트롤을 만들수 있다는점에서 놀라웠다
UI쪽을 공부하니 코드를 만들때 컨트롤과 프로퍼티를 통해 코드를 만들기에 한결 수월해졌고 앞 으로도 많이 활용해야 겠다는 생각이 들었다.
