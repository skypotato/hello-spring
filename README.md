# hello-spring
'스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술' 인프런 강의를 기반으로 코드를 작성해보고, 공부한 내용을 정리하는 공간이다.

## 프로젝트 환경설정
스프링을 시작하기에 앞서 스프링부트를 이용하여 관련 초기 설정 및 프로젝트를 손쉽게 생성하고 기본적인 동작을 작성하여 빌드하고 실행하는 수업니다.

### 프로젝트 생성
### 라이브러리 살펴보기
### View 환경설정
### 빌드하고 실행하기
빌드는 프로젝트 경로로 이동 후 Mac의 경우 아래와 같은 명령어를 실행하면 빌드되며 ./build 디렉토리가 생성된다.
~~~shell
./gradlew build
~~~
빌드가 정상적으로 안될 경우 아래와 같은 명렁어를 작성한다. 이 경우 기존의 ./build 디렉토리가 삭제된 후 새롭게 빌드하게된다.
~~~shell
./gradlew clean build
~~~
./hello-spring/build/libs 로 이동하여 아래 명령어를 작성하고 localhost:8080으로 접속하면 프로젝트가 실행되는 것을 볼 수 있다.
~~~shell
java -jar hello-spring-0.0.1-SNAPSHOT.jar
~~~