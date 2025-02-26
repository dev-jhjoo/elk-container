# elk-container 🚀

ELK 스택을 Docker Compose를 사용하여 손쉽게 설정하고 실행할 수 있는 프로젝트입니다. 이 프로젝트는 Elasticsearch, Logstash, Kibana를 포함하며, 로그 데이터를 수집, 분석 및 시각화하는 데 도움을 줍니다.

## 구성 요소 🛠️

- **Elasticsearch**: 분산형 검색 및 분석 엔진
- **Logstash**: 로그 수집 및 처리 파이프라인
- **Kibana**: 데이터 시각화 도구

## 시작하기 🏁

1. Docker 및 Docker Compose가 설치되어 있는지 확인하세요.
2. 프로젝트를 클론합니다:
   ```sh
   git clone https://github.com/yourusername/elk-container.git
   cd elk-container
   ```
3. Docker Compose를 사용하여 컨테이너를 시작합니다:
   ```sh
   docker-compose up -d
   ```

## 로그 파일 경로 📂

> 💡만약 로그 파일이 아닌 다른 유형의 Datasource를 원한다면 logstash.conf 의 input 설정을 자신에게 맞게 수정해야 합니다.

- 로컬 로그 파일 경로: [logs](http://_vscodecontentref_/1)
- Logstash 설정 파일 경로: [logstash.conf](http://_vscodecontentref_/2)
- sincedb 정보 저장 경로: `./sincedb`

## 라이선스 📄

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

---

이 프로젝트는 ELK 스택을 쉽게 설정하고 관리할 수 있도록 도와줍니다. 기여나 피드백은 언제나 환영합니다! 😊
