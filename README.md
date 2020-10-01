# Clean Architecture
## 핵심
### 프레임워크로 부터 독립하세요
아키텍쳐는 프레임워크에 의존하면 안됩니다. 최소한의 노력으로 새로운 프레임워크를 적용할 수 있어야 합니다.
### 세부 구현으로부터 독립하세요
SW 시스템의 핵심 모듈은 UI, DB, Framework, Library의 변경에 영향을 받으면 안 됩니다.
### 하위 레이어는 상위 레이어를 의존하면 안 됩니다.
항상 모든 의존성은 하위 레이어를 향해야 합니다.
### Entity, UseCase
Entity, UseCase는 Implementation의 영향을 받으면 안 됩니다
### Adapter, Converter
Adapter, Converter은 레이어 내부의 세부사항이 다른 레이어로 전파되지 않도록 도와줍니다.<br/>
DDD의 Bounded Context를 좋은 형태로 구현할 수 있도록 해줍니다.
### DIP
고 수준의 모듈이 저 수준 모듈에 의존하면 안됩니다. 상호가 추상화에 의존하도록 하십시요.
