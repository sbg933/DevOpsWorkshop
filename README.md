# Oracle APAC 클라우드 테스트 드라이브


최종 업데이트 : 2017 년 9 월 07 일 

## 마이크로 서비스 랩


이 랩에서는 Microserivces 환경을 준비하고 Oracle Application Container Cloud Service를 사용하여 Mircoserivces를 개발하는 방법을 보여줍니다. 

### 소개


마이크로 서비스 아키텍처에 대한 표준은 없지만 업계에서는 주로 아래에 언급된 마이크로 서비스 아키텍처가 따라야 할 몇 가지 디자인 요소와 특성에 부합해야 합니다. 

- 여러개 이며, 작고, 미니멀하고 독립적인 서비스
- 장애가 날 수도 있음
- 확장성을 위한 디자인
- 메시지를 통해 호출되는 기능적인 분리성
- 상태를 저장하지 않는 것을 기본으로 함
- DevOps/NoOps를 위한 완전 자동화된 배포

마이크로 서비스를 채택하는 일반적인 사용 사례가 몇 가지 있습니다. 

- 주변에 마이크로 서비스를 추가하여 기존의 단일 응용 프로그램을 확장할 때
- 기존 모듈 식 앱을 마이크로 서비스 스타일로 생성할 때
- 완전히 새로운 마이크로 서비스 스타일 앱을 처음부터 만들 때

따라서, 마이크로 서비스에 대한 예시 요구 사항은 다음과 같습니다. 

- scalable, elastic, polyglot 
- 자동 개발 작업 
- 애플리케이션 성능 모니터링 및 진단 장비 
- 단순성과 확장성 을위한 컨테이너
- 서비스 소비를 위한 API 
- mobile first / modern Web UX 

**마이크로 서비스를 통해 기업은 신속하고 민첩한 방식으로 애플리케이션의 일부를 개발, 배포 및 업데이트 할 수 있으므로 보다 신속하고 유연한 방식으로 새로운 시장 요구 사항 및 경쟁에 대응할 수 있습니다.**

마이크로 서비스 아키텍처 (**MSA**)는 민첩한 개발 및 서비스 배포를 보장합니다. 그러나 조직이 MSA를 채택 할 때 여러 가지 과제가 있습니다. 다음 다이어그램은 그러한 과제 / 요구 사항 중 일부를 나열합니다. 

![](images/000.challenges.png)


## Oracle Application Container 클라우드 서비스


[Oracle Application Container Cloud Service](https://cloud.oracle.com/en_US/application-container-cloud)는 Oracle AppDev Portfolio의 클라우드 서비스 중 하나로 Java SE, Node.js, PHP, Python 및 Ruby 응용 프로그램을 Oracle Cloud에 배포 할 수 있습니다. 

![](images/000.architecture.png)


Oracle Application Container Cloud Service에는 다음과 같은 주요 기능이 있습니다. 

- Java SE, Node.js, PHP, Python 및 Ruby 응용 프로그램에 대해 사전 구성된 환경. 
- Java Flight Recorder, Java Mission Control, 고급 메모리 관리 및 지속적이고 적절한 보안 업데이트의 알림 같은 Java SE 고급 기능. 
- Spring, Play, Tomcat 및 Jersey와 같은 모든 Java 프레임 워크 및 컨테이너를 지원하는 개방형 플랫폼. 
- JRuby와 같은 Java Virtual Machine (JVM) 기반 언어 지원. 이 서비스에서 Java Virtual Machine을 사용하는 언어를 실행할 수 있습니다. 
- 오라클의 엔터프라이즈 급 지원. 
- 웹 기반 사용자 인터페이스 및 REST API 

![](images/000.accs.png)


또한 다른 Oracle Cloud 서비스와의 통합을 선택할 수도 있습니다. 로컬 시스템에서 애플리케이션을 개발하거나 Oracle Developer Cloud Service를 사용할 수 있습니다. 

## Oracle Developer Cloud Service

[Oracle Developer Cloud Service](https://cloud.oracle.com/en_US/application-container-cloud)은 민첩한 개발 방법론 및 DevOps 자동화를 가능하게하는 클라우드 기반 개발 플랫폼입니다. 이 호스팅 팀 개발 및 전달 플랫폼에는 문제 추적, 코드 버전 관리, 위키, 애자일 개발 도구, 지속적인 통합 및 배포 자동화(CI/CD)가 포함됩니다. 

![](images/000.devcs.png)


## 오늘 Practice에 관해서


개발자 클라우드 서비스를 사용하여 다음 1 시간 동안 Application Container Cloud에 2 개의 마이크로 서비스를 만들고 배포합니다 :smile:. 
- 기존 3rd party Git Repository 활용 
- 개발자 클라우드 서비스에서 빌드 및 배포 작업 만들기 
- 개발자 클라우드 서비스와 IDE 사용 
- 응용 프로그램에서 데이터베이스 클라우드 서비스 활용 
- 응용 프로그램 컨테이너 클라우드 서비스에 배포 

![](images/000.todaylab.png)   


## [Start The Lab](MicroservicesLab.md)
