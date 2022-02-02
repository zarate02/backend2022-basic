- 백앤드 기초

-- 환경

--- 준비물
1. 자바 1.8 : https://github.com/ojdkbuild/ojdkbuild/releases/download/java-1.8.0-openjdk-1.8.0.322-1.b06/java-1.8.0-openjdk-1.8.0.322-1.b06.ojdkbuild.windows.x86_64.zip
2. 롬복 : https://projectlombok.org/downloads/lombok.jar
3. sts 3 : https://download.springsource.com/release/STS/3.9.11.RELEASE/dist/e4.12/spring-tool-suite-3.9.11.RELEASE-e4.12.0-win32-x86_64.zip

--- 자바1.8 설치
1. c:\dev\ 에 압축해제 (c:\dev\java-1.8.0-openjdk-1.8.0.322-1.b06.ojdkbuild.windows.x86_64\)
2. 자바PATH 설정 : https://hyoje420.tistory.com/7
3. cmd > java -version > 1.8.0.322 성공

--- sts3 설치
1. c:\dev\ 에 압축해제 (c:\dev\sts-bundle\)
2. c:\dev\sts-bundle\sts-3.9.11.RELEASE\STS.exe 실행

--- 롬복 설치
1. 기동중인 이클립스 종료
2. lombok.jar 실행 (더블클릭 or java -jar lombok.jar)
3. Specify location 클릭
4. C:\dev\sts-bundle\sts-3.9.11.RELEASE 선택
5. install/update 클릭
6. Quit Installer

--- 예제 스프링 만들어보기
1. STS 실행
2. 상단 File > New > Spring Legacy Project 클릭
3. Project name 입력 > Spring MVC Project 선택 > Next
4. top-level-package : com.winitech.cs 입력 > Finish
5. 신규 프로젝트 생성될때까지 대기 (초기 세팅 시간걸림)

