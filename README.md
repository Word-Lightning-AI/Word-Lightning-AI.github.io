#Word-Lightning-AI.github.io

Word Lightning AI의 문서화를 위한 저장소입니다.


## 개발 환경 설정
```shell
$ pnpm install # 패키지 설치

$ pnpm run start # 개발 서버 실행

$ pnpm run build # 빌드

# package.json의 deploy 스크립트를 수정해야 합니다
$ pnpm run deploy # 배포
```

```json
{
  "scripts": {
      "deploy": "GIT_USER=<Your Github username> docusaurus deploy"
  }
}
```