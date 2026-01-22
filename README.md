# Sensor Data Monitoring Project

## 프로젝트 개요
Python을 활용해 가상 센서 데이터를 생성하고,  
IPC · MySQL · MQTT를 연계한 **실시간 데이터 수집·저장·시각화 파이프라인**을 구축한 프로젝트입니다.

---

##  프로젝트 설명
Python으로 온도·습도·조도 센서 데이터를 주기적으로 생성하고,  
IPC(FIFO)를 통해 프로세스 간 데이터를 전달한 뒤 MySQL(MariaDB)에 저장했습니다.  
또한 MQTT 기반 실시간 스트리밍과 시각화를 구현하여  
**엔드투엔드 데이터 흐름을 설계·구현**했습니다.

---

##  구현 내용
- Python 기반 가상 센서 데이터 생성 로직 구현 (1초 주기)
- FIFO 파이프를 이용한 IPC(프로세스 간 통신) 설계
- MySQL(MariaDB) 테이블 설계 및 센서 데이터 저장
- MQTT 브로커를 활용한 실시간 데이터 Publish / Subscribe 구조 구현
- Matplotlib을 활용한 실시간 센서 데이터 시각화

---

##  사용 기술
- Python
- IPC (FIFO)
- MySQL (MariaDB)
- MQTT
- Matplotlib

---

##  프로젝트 성과
Python, IPC(FIFO), MySQL, MQTT를 활용하여  
실시간 센서 데이터의 **생성·전송·저장·시각화 전 과정을 직접 구현**하며  
IoT 데이터 처리 구조에 대한 이해도를 확보했습니다.
