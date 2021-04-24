# qcode

[Java Error] Tomcat: java.lang.IllegalArgumentException:Invalid character found in method name. HTTP method names must be tokens

: 위 Exception은 HTTPS의 사용이 어려운 클라이언트의 엔드포인트로부터 HTTPS 실행 요청이 들어왔을 경우 발생하는 예외.

-> https://를 http://로 고치면 해결이 된다.


reference.
stackoverflow.com
