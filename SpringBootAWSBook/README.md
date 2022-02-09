# 스프링 부트와 AWS로 혼자 구현하는 웹 서비스

## Issue
### compile 못씀
gradle 7 버전 이상부터 compile이 삭제가 되었다. [참고](https://tomgregory.com/gradle-implementation-vs-compile-dependencies/)

### Lombok과 jdk 버전 이슈
Lombok의 버전을 명시해주지 않았을 때 1.18.8 버전이 설치되었다. 이는 jdk 17과 호환되지 않기 때문에 강제로 버전업을 시켜줄 필요가 있다.
현재 1.18.22(최신 버전)으로 명시해주어 이슈를 해결했다.