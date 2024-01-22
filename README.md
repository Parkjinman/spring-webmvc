spring-webmvc
=============

## 개발환경
| 순번 | 이름     | 버전            |
|----|--------|---------------|
| 1  | webmvc | 4.3.2.RELEASE |
| 2  | gradle | 8.1.1         |
| 3  | tomcat | 8             |
| 4  | java   | 1.8           |

## 개요
webmvc + maven + tomcat으로 구축된 솔루션을 gradle로 migration하는 과정에서 webmvc를 분석하기 위해 초기세팅 버전입니다.

## Intellij 환경세팅 방법
### 목차
1. Java 세팅
2. Gradle load
3. tomcat 설정

#### 1. Java 세팅
- 설정화면 열기
>ctrl + alt + shift + s
- Project Settings > SDK
- Java 1.8 선택

#### 2. Gradle load
```bash
$ ./gradlew --refresh-dependencies
```

#### 3. tomcat 설정
![tomcat_1.png](image%2Ftomcat_1.png)
![tomcat_2.png](image%2Ftomcat_2.png)

- 설정 이후 tomcat start
- getHelloWorld.http 파일 실행

![tomcatTest.png](image%2FtomcatTest.png)
