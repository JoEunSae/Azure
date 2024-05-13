# VM Log수집 및 Alert

## Azure에서 Log를 수집하는 방법

1. Azure Monitor 에이전트 사용
- Windows 및 Linux VM에서 사용할 수 있다.
- 에이전트를 VM에 설치하고 로그 수집을 위한 데이터 수집 규칙을 구성해야 한다.
- 에이전트는 시스템, 애플리케이션 및 사용자 지정 로그를 포함하여 다양한 유형의 로그를 수집할 수 있다.
- 수집된 로그는 Log Analytics 작업 영역에 저장된다.

2. VM 인사이트 사용
- Windows 및 Linux VM에서 사용할 수 있다.
- VM에 Azure Monitor 에이전트가 설치되어 있어야 한다.
- VM 인사이트는 성능 및 연결 메트릭, 컴퓨터 및 프로세스 인벤토리 데이터, 상태 정보를 수집하여 Azure Monitor의 Log Analytics 작업 영역에 전달한다.

**Azure Monitor 에이전트와 VM 인사이트 차이**
- Azure Monitor 에이전트 : 시스템, 애플리케이션, 사용자 지정 로그를 포함하여 다양한 유형의 로그를 수집할 수 있습니다. 또한 성능 카운터 및 이벤트도 수집할 수 있다.
- VM 인사이트 : 주로 성능 및 연결 메트릭, 컴퓨터 및 프로세스 인벤토리 데이터, 상태 정보와 같은 성능 중심 데이터에 중점을 둔다.

![image](https://github.com/JoEunSae/Azure/assets/83803199/0026d7b0-bf41-4ebe-b0bf-1a8f53dcc666)


