# Object

#### MakeObject 노드 (MakeObject Node)

**목적:** 지정된 키와 값으로 구성된 객체를 생성합니다.

**기능:** 이 노드는 입력으로 받은 키와 값 쌍을 사용하여 새로운 객체를 만듭니다. 이 과정을 통해 데이터를 구조화하여 다른 노드로 전달할 수 있는 형태의 객체로 변환할 수 있습니다. 다음 단계로의 데이터 전달을 위한 'result' 연결점을 제공합니다.

#### ObjectDestructor 노드 (Object Destructor Node)

**목적:** 객체를 구성하는 키와 값을 분해하여 개별적으로 사용할 수 있게 합니다.

**기능:** `ObjectDestructor` 노드는 복잡한 객체를 단순한 구성 요소로 분해합니다. 이를 통해 객체 내 특정 값에 접근하거나 필요한 데이터만을 추출하는데 사용됩니다. 'result' 연결점은 분해된 값들을 다음 노드로 전달하는 데 사용됩니다.

#### ObjectConstructor 노드 (Object Constructor Node)

**목적:** 주어진 데이터나 파라미터들로부터 객체를 생성합니다.

**기능:** `ObjectConstructor` 노드는 다양한 입력 값을 받아 이를 하나의 객체로 조립합니다. 객체를 새로 구성하거나 기존의 데이터 구조를 변경할 때 사용되며, 'result' 연결점을 통해 생성된 객체를 다음 노드로 전달할 수 있습니다.
