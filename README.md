---
description: How your application will be built.
---

# Architecture

ServerKit는 일반 개발자와 동일한 방식으로 애플리케이션을 구축합니다. 따라서 응용 프로그램의 구성 요소는 모든 전문 소프트웨어와 동일합니다.



(아키텍처.png)



## SchemeKit and DBKit

SchemeKit는 기본 데이터 타입을 넘어서, 고차원적으로 추상화된 데이터 타입을 지원하여, 텍스트나 파일과 같은 데이터를 특화된 타입(예: 이메일, 전화번호, 엑셀 파일)으로 처리함으로써 추가 기능과 제약사항의 적용을 가능하게 합니다.

<figure><img src=".gitbook/assets/스크린샷 2024-02-13 오후 4.03.17.png" alt=""><figcaption></figcaption></figure>

이를 통해, 특정 데이터 타입에 대한 내장된 유효성 검사와 제약 속성을 자동으로 적용하여 데이터의 정확성과 일관성을 보장합니다. 또한, 각 추상화된 데이터 타입은 AI 및 자연어 처리 프로그래밍의 발전을 지원하는 정규화된 데이터 형태로의 확장성을 제공합니다.



## LogicKit

LogicKit는 노드 기반 프로그래밍 툴로써 복잡한 프로그래밍 작업을 간단한 노드와 연결을 통해 시각화합니다. 사용자는 프로세스의 흐름을 쉽게 이해하고 조작할 수 있습니다.&#x20;

<figure><img src=".gitbook/assets/스크린샷 2024-02-13 오후 4.14.28.png" alt=""><figcaption></figcaption></figure>

드래그 앤 드롭 기능을 통해 노드를 손쉽게 추가하고 연결할 수 있으며, 복잡한 코드 작성 없이도 서버를 구성할 수 있습니다. 노드의 기능과 속성은 사용자의 특정 요구에 맞게 맞춤 설정 가능하여, 다양한 프로그래밍 요구와 환경에 유연하게 대응할 수 있습니다. 오류 감지 기능은 잘못된 상태의 저장을 방지하여 더 안정적이고 신뢰할 수 있는 프로그래밍 환경을 제공합니다.



## RouterKit

RouterKit는 Restful API 기반의 손쉬운 엔드포인트 설정이 가능합니다. 사용자가 복잡한 코딩 과정 없이도 API를 손쉽게 구성할 수 있습니다.

<figure><img src=".gitbook/assets/스크린샷 2024-02-13 오후 4.19.53.png" alt=""><figcaption></figcaption></figure>

이를 통해, 사용자는 URL 경로, HTTP 메소드 및 요청 파라미터를 유연하게 매핑하고 관리할 수 있어, 다양한 API 요구 사항에 적응할 수 있습니다. 보안 프로토콜과 인증 메커니즘을 통합할 수 있는 옵션을 포함하여 데이터 보안과 접근 제어를 강화합니다. 또한, API 엔드포인트의 설정을 기반으로 한 자동 문서화를 제공하며, 사용자는 이를 통해 API를 쉽게 테스트하고 디버깅할 수 있습니다.



## UserKit

UserKit는 강력한 보안 수단을 제공하는 권한 정의 기능입니다. 세밀한 권한 설정을 제공하여 사용자 및 그룹별로 접근 가능한 리소스와 스행 가능한 작업을 정확히 정의할 수 있어 데이터와 시스템 보안을 강화합니다. 권한 부여에 시간 제한을 설정할 수 있게 하여 특정 기간 후 자동으로 권한이 만료되거나 필요에 따라 갱신되어 불필요하거나 오래된 권한이 계속 유지되는 것을 방지하고 시스템의 보안을 지속적으로 강화합니다.

<figure><img src=".gitbook/assets/스크린샷 2024-02-13 오후 4.24.41.png" alt=""><figcaption></figcaption></figure>

또한 OpenID 기반 인증으로 손쉽게 연동 가능합니다. 기본 이메일 로그인 외에도 여러 소셜 미디어 계정을 통한 로그인 옵션이 포함되어 사용자에게 다양한 로그인 방법을 제공합니다. OpenID 기반 인증은 복잡한 인증 흐름을 손쉽게 설정할 수 있도록 하여 개발자는 사용자 경험에 더 집중할 수 있습니다.



## Deploy

ServerKit에서 배포는 원클릭으로 가능합니다. 사용자는 복잡한 설정 없이도 전체 Backend 시스템을 쉽고 빠르게 배포할 수 있어 시간을 절약하고 에러 가능성을 줄입니다.  필요한 경우 이전 버전으로 쉽게 롤백 할 수 있는 기능을 제공하여 신속한 오류 수정과 안정적인 서비스 유지가 가능합니다.

<figure><img src=".gitbook/assets/스크린샷 2024-02-13 오후 4.36.08.png" alt=""><figcaption></figcaption></figure>

멀티 스테이지 배포도 원클릭으로 가능합니다. 여러 단계에 걸친 복잡한 배포 단계를 쉽게 진행 할 수 있습니다. 또한 개발, 테스트, 운영으로 나뉘어진 배포 단계에 명확한 설정과 상태 추적 기능을 제공하여 배포의 안정성과 품질을 보장합니다.

