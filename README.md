# TodayIlearned 
 


06/20 
서버란 무엇인가 :  클라이언트에게 네트워크를 통해 정보나 서비스를 제공하는 컴퓨터 프로그램 또는 장치를 의미 


도메인 : 도메인의 같은된 시스템 ,www 는 호스트 네임이다 . 서버의 아이피 주소를 현실적으로 외우기 어렵기때문에 식별하는 호스트명 저장하는 것이 도메인이다 / 

 A recored L: 도메인을 서버 ip 로 연결한다 직통연결. Cname : 도메인을 별명을 넣는거다. 주기적으로 변하는 ip 에 일정하게 연결된 다른 도메인 
 
 
 6/21: 
 공인 ip : 전세계에 유일한 ip ., 사설 ip : 내부망에서 사용하는 고유한 ip 
git: 버전관리하는 툴 , github : 원격저장소


6/22
정적 : 움직이지 않는,. 언제 접속하여도 움직이지 않는 웹(시간, 랜덥), 접속할때마다 내용이 편하지 않는 사이트(프론트)
동적 : 접속할때마다, 서버와 디비를 통해 페이지 출력



07/03
아파치, NginX, 톰캣이 뭔가요? (+ 웹서버, WAS, 로드밸런싱, 프록시)

어떤 컴퓨터로 하여금 서버 역할을 하도록 해주는 소프트웨어를 (아파치, nginx, iis) 웹서버!

정적웹 : 페이지 내에서 바뀔수 없는 웹페이지를 정적웹이라고 한다. 
동적웹 : 새로운 데이터가 변경 생성해주때마다 새로운 페이지 정보를 제공해주는 웹을 동적웹 

톰캣이란 무엇인가? : 요즘엔 스프링에 톰캣이 기본적으로 내장이 되어있어서 잘안쓰지만
java jsp으로 만든 웹 또는 api 어플리케이션을 실행할때 톰캣같은 was 서버로 가동된다. 

was : 웹이랑 서버 사이에 어플리케이션이 들어있는다. 
동적사이트를 전문적으로 처리한다. 
결과적으로 아파치, 엔진엑스는 웹서버 , 톰캣은 와스 라고 기억

 아파치, 엔진엑스 리버스 프록시  제공
 프록시는 중간에서 처리 서버의 정보를 감춘다. 
 
 
성능과 가벼움을 중요한 서비스는 nginx, 안정성은 아파치



웹서비스에 필수! CDN이 뭔가요?

CDN : 이미지나 동영상 같은 컨텐츠를 사용자에게 배달한다. 
사용을하는 이유는, 서버 컴퓨터에서 컨텐츠를 처리하면 
1. 거리때문에 전세계에서 전송하는데 느리면 큰일나고 
2. 트래픅을 감당한다. 


톰캣을 쓰는가 
1. 오픈소스 


톰캣 구성
Catalina 컴포넌트는 서블릿을 처리하는 역할을 수행합니다.
Coyote는 HTTP 요청을 처리하는 역할을 수행하는 컴포넌트로서 톰캣에 TCP를 통한 프로토콜을 생성하고 관리합니다.
Jasper는 jsp 페이지를 처리하는 컴포넌트로서 jsp 로 만들어진 페이지를 처리하는 서블릿 입니다.

5.5.4

