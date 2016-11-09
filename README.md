# java87
비트캠프 자바87기

# gradle 사용
## 실행
- 그래들을 이용하여 수행할 수 있는 작업 정보를 출력한다.
- 명령어를 실행하는 디렉토리에서 build.gradle 파일을 찾아 읽는다.
- build.gradle 파일은 그래들 설정 파일이다. 여기에 설정한 대로 동작한다.
~~~~
> gradle
:tasks

--------------------------------------------
All tasks runnable from root project
--------------------------------------------

Build Setup tasks
-----------------
init - Initializes a new Gradle build. [incu
wrapper - Generates Gradle wrapper files. [i

Help tasks
----------
buildEnvironment - Displays all buildscript
components - Displays the components produce
dependencies - Displays all dependencies dec
dependencyInsight - Displays the insight int
help - Displays a help message.
...
~~~~

## 그래들 설정 파일 생성
- build.gradle 
~~~~
apply plugin: "java"
apply plugin: "eclipse"
~~~~

## 그래들 프로젝트 폴더 생성
- 그래들 프로젝트 표준 디렉토리 구조 생성
~~~~
project01
  src
    main
      java
      resources
      webapp
    test
      java
      resources
~~~~