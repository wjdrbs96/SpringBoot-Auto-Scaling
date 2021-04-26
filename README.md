# `Spring Boot & Auto-Scaling`

- [Blue/Green 배포 방식이란?](https://devlog-wjdrbs96.tistory.com/300)
- [Blue/Green 자동화 배포하는 법 정리](https://devlog-wjdrbs96.tistory.com/305)

<br>

## `서버 아키텍쳐`

![스크린샷 2021-04-26 오전 10 42 55](https://user-images.githubusercontent.com/45676906/116018071-30370600-a67c-11eb-8702-c71d6c76f461.png)

- 위의 아키텍쳐는 `Blue/Green 배포 방식으로 이루어지기 때문에 배포 중에 Green 그룹이 생기고 배포가 끝나면 Blue 그룹이 삭제됨`

<br>

## `사용된 기술`

- `Java 11`
- `Spring Boot`
- `AWS EC2, S3`
- `Travis CI`
- `AWS CodeDeploy(Blue/Green)`
- `AWS Load-Balancer`
- `AWS Auto-Scaling`