### TIL
#Java, Spring
#AWS S3에 여러 파일 업로드 및 삭제구현하기
![image](https://user-images.githubusercontent.com/116361833/210064159-b8a1dc8f-d1a6-4cdd-8731-dc2c10e87faa.png)

https://earth-95.tistory.com/117

✍VM옵션에 ```-Dcom.amazonaws.sdk.disableEc2Metadata=true``` 추가하기

✍swagger 연동 오류날 경우 : Spring boot 2.6버전 이후에spring.mvc.pathmatch.matching-strategy 값이 ant_apth_matcher에서 path_pattern_parser로 변경되면서 몇몇 라이브러리(swagger포함)에 오류가 발생할 수 있다고 합니다.

❗❗# Swagger (application.properties에 추가)
```spring.mvc.pathmatch.matching-strategy = ANT_PATH_MATCHER``` 를 추가

❗❗build.gradle에 추가
```implementation 'io.springfox:springfox-boot-starter:3.0.0' ```
