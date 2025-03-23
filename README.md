# User-Agent
What is User-Agent

ipv4 패킷 헤더의 구조중 UA에 대한 분석 보고서

User Agent, UA


사용자를 대신하여 일을 수행하는 소프트웨어의 식별 정보이다.
여기서 사용자 에이전트가 쓰이는 곳은 대개 웹 분야이기 때문에 '사용자를 대신하여 일을 수행하는 소프트웨어'는 대개 웹 브라우저를 뜻한다.

Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/108.0.0.0 Safari/537.36 Edg/108.0.1462.46
Microsoft Edge 버전 108.0.1462.46에서 출력하는 내용
Windows NT 커널 버전 10을 사용하는 64비트 운영체제[1]상의 Gecko 같은 브라우저 레이아웃 엔진인 KHTML을 사용하는[2] 엣지 버전 108.0.1462.46이고, 크롬 버전 108.0.0.0, AppleWebKit 및 Safari 버전 537.36과 호환되는 브라우저라는 내용이며 맨 앞의 Mozilla/5.0 부분은 최신 브라우저를 알지 못하는 유물급의 사이트들을 위한 하위호환용 문구다.

그런데 웹 브라우저와 운영체제의 수는 수없이 많다. 웹 브라우저만 해도 엣지, 사파리, 크롬, 파이어폭스 등이 있고, 최근에는 운영체제의 다변화도 이루어져 Windows 말고도 안드로이드, iOS 등 모바일 플랫폼용 운영체제도 많이 출시되었다.
여기서 웹 페이지에 접속할 때 각 플랫폼에 맞는 페이지, 즉 모바일 페이지나 데스크탑용 페이지로 연결하려면 거기에 맞는 정보가 필요한데, 그 정보가 바로 사용자 에이전트이다. 이름만 보면 거창하지만 사실상 평범한 웹 헤더다. What is my user agent? 등에서 확인할 수 있다.

YOUIP.NET 에서는 Fake-user-agent 와 Real-user-agent를 감지하여 표시해주는 기능을 제공한다.

사실 이는 사용자 에이전트 자체라기 보다는, 사용자 에이전트가 뭔지 표시하는 문자열이고, 영어로 정확히 표현하면 User-Agent string in HTTP라고 해야 옳겠지만, 줄임말 비슷하게 앞뒤 자르고 User Agent라고만 하는 경향이 있다보니 용어가 혼용되는 것이다. 영문 위키백과에서도 설명 자체는 구분해 뒀지만, User agent identification과 Use in HTTP라는 하위 문서를 통해 적당히 구분해 둔 정도이다. 아래 설명들도 바로 이 웹 헤더로써의 사용자 에이전트를 설명하는 것이다.

파이어폭스 계열 브라우저에서는 about:config에서 사용자 에이전트 문자열을 바꿀 수 있으며 타브라우저는 확장기능으로 변경할수 있다.

IETab에서도 특정 버전의 사용자에이전트로 바꿀수 있는 기능이 있다. 과거 IE7 미지원 웹페이지가 많았을때 구세주였다.

