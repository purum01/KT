수업 자료 다운로드
---------------
* Windows OS를 사용하시는 분은 여기서 다운로드 받아 설치하세요
* [KT DATA](http://naver.me/Gq8OpQZJ)

프로그램 다운로드 사이트
------------
* Mac OS를 사용하시는 분은 각 사이트에 접속해서 다운로드 받아 설치하세요(버젼 확인)
* [JDK 17](https://www.oracle.com/java/technologies/downloads/#jdk17-windows)
* [Spring Tools 4 for Eclipse 4.15.3](https://spring.io/tools)
* [Tomcat 9](https://tomcat.apache.org/)
* [H2 DB](https://www.h2database.com/html/main.html)


Java 설치
------------
1. jdk-17_windows-x64_bin.exe 실행  
2. [Next] 클릭  
![image](https://github.com/user-attachments/assets/7309c860-f45a-443a-9df1-6c04115f1b11)  
3.[Next] 클릭   
![image](https://github.com/user-attachments/assets/560ee0db-3b24-40d2-896a-65e650386585)   
4. 설치 진행  
![image](https://github.com/user-attachments/assets/6cf343d8-cc7b-4a80-9c00-e7dc5adc0ccc)  
5. [Close] 클릭  
![image](https://github.com/user-attachments/assets/9e919011-83e8-45b8-bfac-fe16fdcf04b7)
6. PATH 확인 --> [ windows + R ] 키를 누른 후 "cmd" 입력하고 Enter 키를 누릅니다. <b>java -version</b> 명령을 실행하면 다음과 같이 java 17 버젼이 나와야 합니다.
![image](https://github.com/user-attachments/assets/d3748c0c-286c-4957-9cb0-485da8060f2e)
7. Java 17 버젼이 아닌 경우 환경 변수를 설정합니다. 
    1. [windows]키를 누르고 "환경 변수" 입력
    2. "시스템 환경 변수 편집"을 선택
    3. [환경 변수] 버튼 선택
    4. 시스템 변수 영역에 [새로 만들기] 버튼 선택
        1. 변수 이름에 JAVA_HOME  입력
        2. 변수 값에 JDK가 설치된 경로 입력 (예:C:\Program Files\Java\jdk-17)
        3. ![image](https://github.com/user-attachments/assets/69c314b1-2033-453d-a4fd-8ed4288a2bea)
        4. 환경 변수를 새로 설정한 경우 커맨드창을 새로 여신후 <b>java -version</b> 명령을 실합니다.

Spring Tools 4 for Eclipse 4.15.3 설치
------------
1. C:\STS 폴더를 생성하고 spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-win32.win32.x86_64.self-extracting.jar 파일을  복사
2. 파일을 포인팅한 후 마우스 오른쪽 버튼을 눌러 [연결 프로그램]-[Java(TM) Platform SE binary]을 선택
3. 또는 터미널창에서 "java -jar  spring-tool-suite-4-4.15.3.RELEASE-e4.24.0-win32.win32.x86_64.self-extracting.jar 실행"  
![image](https://github.com/user-attachments/assets/b8781953-e242-40fb-ba52-66926d49342a)
4. 압축후 폴더 모습   
![image](https://github.com/user-attachments/assets/99e3c24f-6d4a-4400-9162-da378f849037)
5. <b>SpringToolSuite4.ini</b> 파일을 열어 javaw.exe 지정(설치 경로가 다를수 있습니다)
![image](https://github.com/user-attachments/assets/1a271a9c-6095-4536-a162-0bb79e6bc427)
6. <b>SpringToolSuite4.exe</b> 더블클릭해서 실행
7. [Launch]버튼 클릭 (이클립스가 실행됩니다.)
8. 상단의 메뉴에서 [Help] -> [Eclipse Marketplac...] 선택
![image](https://github.com/user-attachments/assets/89d61dd6-0dab-4c54-a901-ada5ad959ead)
9. Find 창에 "Enterprise Java"를 입력후 검색
10. Eclipse Enterprise Java and Web Developer Tools 3.26 의 [Install] 클릭
11. 이후 설치는 기본값으로 진행합니다.
![image](https://github.com/user-attachments/assets/efa52e82-1413-4f47-8687-becccacfd9c0)
12. Eclipse가 재 실행된 후 [Ctrl + N]을 눌렀을 때 다음 항목들이 나오면 설치 완료입니다.
![image](https://github.com/user-attachments/assets/0aba7289-e7e4-4dd2-8b6e-5c13e17e2a4f)

H2 설치
------------
1. h2-setup-2024-07-15.exe 더블클릭
2. 설치 폴더 확인 후 [다음] 선택  
![image](https://github.com/user-attachments/assets/4eca4c36-008a-401a-a0f9-ce7ac1840c51)
3. [설치] 선택  
![image](https://github.com/user-attachments/assets/74f9bfe4-8cb6-4e83-909f-5da847b1f3d6)
4. windows 버튼 누르고 "h2" 입력한 후 [H2 Console] 선택 
![image](https://github.com/user-attachments/assets/304b248d-817a-4bf8-8cd5-a1674198e9ec)
5. 저장한 설정을 Generic H2(Server) 선택
![image](https://github.com/user-attachments/assets/f22c695a-0ddf-4bce-a2e3-00e038deb5e4)
6. [연결] 선택
![image](https://github.com/user-attachments/assets/89a55e12-cc93-4138-9d62-7a2696ad826e)
7. H2 DB가 실행된 화면
![image](https://github.com/user-attachments/assets/06edd3f9-9f17-48e0-adad-ff142240518e)
8. [연결]부분에서 오류가 나는 경우 해결 방법
    1. mem.testdb  오류인 경우 - C:\사용자\[계정이름] 폴더에 test.mv.db 파일을 생성함 
    2. 포트번호 오류인 경우 - 터미널창에서 다음 명령문 실행
        1. netstat -ano | findstr 포트번호
        2. taskkill /PID  포트번호  /F








   
   



 



