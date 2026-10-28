# WADP_PUBLIC_DEPLOY

| 서버의 Java | 압축 파일 | 크기 |
|---|---|---|
| Java 8 이상 | [WADP_20261028_1347_GIT_jdk8.tar.gz](https://github.com/simtg-cre/WADP_PUBLIC_DEPLOY/releases/download/GIT_20261028_1347/WADP_20261028_1347_GIT_jdk8.tar.gz) | 32.2 MB |

전체 버전: [Releases](../../releases)

## 설치와 실행

압축 파일 하나에 jar 와 실행 스크립트(whatap_auto_deploy_collector.sh)가 들어 있습니다.

```sh
# Java 8 이상
curl -LO https://github.com/simtg-cre/WADP_PUBLIC_DEPLOY/releases/download/GIT_20261028_1347/WADP_20261028_1347_GIT_jdk8.tar.gz

tar xzf WADP_20261028_1347_GIT_jdk8.tar.gz
cd WADP_20261028_1347_GIT_jdk8
./whatap_auto_deploy_collector.sh
```
