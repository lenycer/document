## Elasticsearch 란?
- 텍스트, 숫자, 위치 기반 정보, 정형 및 비정형 데이터 등 모든 유형의 데이터를 위한 분산형 오픈 소스 검색 및 분석 엔진
- Apache Lucene을 기반(현재 Elastic이라고 알려져 있는) Elasticsearch N.V.가 2010년에 최초로 출시
- 간단한 REST API, 분산형 특징, 속도, 확장성 제공
- 데이터 수집, 보강, 저장, 분석, 시각화를 위한 오픈 소스 도구 모음인 Elastic Stack의 중심 구성 요소.
- Elasticsearch, Logstash, Kibana의 머리글자를 따서 ELK Stack이라고 하는 Elastic Stack + Elasticsearch로 전송하기 위한 경량의 데이터 수집 에이전트들이 풍부하게 제공되는 컬렉션인 Beats

## Elasticsearch 용도
- 검색
- 로깅 및 로그 분석
- 모니터링
- 데이터 분석
- 시각화

## Elasticsearch 작동 방법
- 원시 데이터 수집 (구문 분석, 정규화, 데이터 강화)
- Elasticsearch 색인
- kibana를 통해 데이터 시작화

## Elasticsearch Index
- RDB의 database및 table과 대응되는 개념
- 연관되어 있는 문서들의 모음
- Elasticsearch는 json 문서로 데이터를 저장
- inverted index 구조
- 하나의 값이 해당 값이 들어간 document_id를 지정하고 있음
- 빠른 검색을 위해 설계된 것

## Logstash
- 데이터 집계
- 데이터 처리 파이프라인
- 다양한 데이터 수집 및 변환, 데이터 강화
- Elasticsearch 전송

## Kibana
- Elasticsearch 시각화 및 관리 도구
- 다양한 그래프, 차트 제공

## filebeat
- 경량 데이터 수집 에이전시 
- 하나 이상의 로그 파일로 부터 집계하여 정의된 출력으로 전송




