# WADP_PUBLIC_DEPLOY

whatap_auto_deploy_collector (Java / Spring Boot jar) 배포 압축 파일을 받는 곳입니다.
압축 파일은 이 저장소의 파일이 아니라 [Releases](../../releases) 에 있습니다.

## 최신 버전: GIT_20261028_1341

뺀 것: 탭 cserver · 자동화 작업 whatap-collector, collector-patch, kind-3, kind-4, kind-5

| 서버의 Java | 압축 파일 | 크기 |
|---|---|---|
| Java 8 이상 | [WADP_20261028_1341_GIT_jdk8.tar.gz](https://github.com/simtg-cre/WADP_PUBLIC_DEPLOY/releases/download/GIT_20261028_1341/WADP_20261028_1341_GIT_jdk8.tar.gz) | 32.2 MB |
| Java 17 ~ 25 | [WADP_20261028_1341_GIT_jdk17.tar.gz](https://github.com/simtg-cre/WADP_PUBLIC_DEPLOY/releases/download/GIT_20261028_1341/WADP_20261028_1341_GIT_jdk17.tar.gz) | 27.7 MB |

전체 버전: [Releases](../../releases)

## 설치와 실행

압축 파일 하나에 jar 와 실행 스크립트(whatap_auto_deploy_collector.sh)가 들어 있습니다.

```sh
# Java 8 이상
curl -LO https://github.com/simtg-cre/WADP_PUBLIC_DEPLOY/releases/download/GIT_20261028_1341/WADP_20261028_1341_GIT_jdk8.tar.gz
# Java 17 ~ 25
curl -LO https://github.com/simtg-cre/WADP_PUBLIC_DEPLOY/releases/download/GIT_20261028_1341/WADP_20261028_1341_GIT_jdk17.tar.gz

tar xzf WADP_20261028_1341_GIT_jdk17.tar.gz
cd WADP_20261028_1341_GIT_jdk17
./whatap_auto_deploy_collector.sh
```
