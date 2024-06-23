# familing-frontend

## Commit convention    

```
1. Type(File or function): Subject 
2. Type: Subject    // (파일이 여러 개인 경우)
```
ex) 로그인 기능 추가
```
feat(login.html): 로그인 기능 추가 // (login.html 파일만 추가)
feat: 로그인 기능 추가 // 파일이 여러 개인 경우 ()안에 다 넣을 수 없으므로 생략 
```

|    Type    | 설명                                             |
|:----------:|------------------------------------------------|
|    feat    | 새로운 기능 추가                                      |
|    fix     | 버그 수정                                          |
|   style    | 코드 수정 없음 (세미콜론 누락, 코드 포맷팅, 파일, 폴더명 수정 혹은 이동 등) |
|  refactor  | 코드 리팩토링                                        |
|  comment   | 주석 추가 및 변경                                     |
|    docs    | 문서 수정 (README.md 등)                            |
|    test    | 테스트 코드 추가                                      |
|   chore    | 빌드 업무 수정, 패키지 매니저 수정 (pom.xml 등)               |
|   remove   | 파일 삭제                                          |
