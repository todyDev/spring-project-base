# springPjrBase
> (*개인적인 파일입니다.)

 GitHub 사용법도 익힐 겸 스프링 프로젝트 기본 설정 부분까지만 올려본다.

## 개발 환경

현 프로젝트의 개발 환경입니다.

```sh
jdk1.8.0_181
Ecplise Oxygen
apache-tomcat-9.0.11
apache-maven-3.5.4
mysql-8.0.12-winx64
Spring FrameWork 3.2.3.RELEASE
```

## 업데이트 내역
* 문서
    * 추가: gitignore 적용
    * 수정: README 문서 업데이트
* 프로젝트 구조 변경 및 설정
    * 수정: context, servlet 폴더 및 파일들의 resources폴더로 경로 이동
    * 수정: web.xml의 context, servlet의 경로 수정
    * 추가: index.jsp 추가 및 utf8 설정
* Log4j 설정
    * 수정: log4j.xml 수정
* Interceptor 설정
    * 추가: CommonInterceptor 클래스 추가
    * 추가: interceptor-servlet xml 추가
    * 수정: actions-servlet xml 수정
    * 추가: TestController 클래스 추가
    * 추가: jsonView bean 등록
* Mybatis 연동
	* 수정: pom.xml에 필요한 라이브러리 추가
	* 추가: MySQL 연결(context-datasource.xml)
	* 추가: Spring 연결(context-mapper.xml)
	* 수정: log4j.xml 수정
	* 추가: AbstractDAO class 추가
    