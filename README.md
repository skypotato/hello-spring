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
### 회원 관리 예제 - 백엔드 개발
- 비즈니스 요구사항 정리
- 회원 도메인과 리포지토리 만들기
- 회원 리포지토리 테스트 케이스 작성
- 회원 서비스 개발
- 회원 서비스 
### 스프링 빈과 의존관계
- 컴포넌트 스캔과 자동 의존관계 설정
    - 컴포넌트 스캔
    - 자동 의존관계
        - 생성자 주입
        - 필드 주입
            - 단점 : 중간에 변경할 방법이 없다.
        - setter 주입
            - 단점 : set 메서드가 public 하게 노출된다.
- 자바 코드로 직접 스프링 빈 등록하기

Junit으로 테스트 코드 작성해보기
Boot 시작
프로젝트 imports 공부
강의목록
