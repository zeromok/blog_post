# ***명명 규칙(Naming Convention)***

- ## 공통
    대소문자가 구분되며 길이에 제한이 없다.  
    예약어를 사용해서는 안 된다.   
    숫자로 시작해서는 안 된다.  
    특수문자는 '_' 와 '$'만을 허용한다.  
    파스칼 표기법 (PascalCase)과 카멜 표기법(camelCase)를 사용한다.  
        PascalCase : 모든 단어에서 첫 번째 문자는 대문자이며 나머지는 소문자이다.  
        camelCase : 최초에 사용된 단어를 제외한 첫 번째 문자가 대문자이며 나머지는 소문자이다.  
    반의어는 반드시 대응하는 개념으로 사용해야 한다.  

- ## 클래스 이름
    클래스 이름은 각 단어의 첫 글자를 대문자로 하여 제목의 경우 명사여야 합니다.  
    Ex) MyClass또는 EmployeeDetails.

- ## 인터페이스 이름
    인터페이스 이름도 각 단어의 첫 글자를 대문자로 하여 제목의 경우 명사여야 합니다.  
    Ex) MyInterface또는 Runnable.

- ## 메서드 이름
    메서드 이름은 카멜 표기법의 동사여야 하며 첫 번째 단어의 첫 글자는 소문자이고 각 후속 단어의 첫 글자는 대문자여야 합니다.  
    Ex) calculateArea()또는 displayEmployeeDetails().

- ## 변수 이름
    변수 이름은 설명적이고 의미가 있어야 하며 각 단어의 첫 글자는 소문자여야 합니다. `카멜표기법` or `스네이크표기법`   
    변수에 약어를 사용하지 않고 모든 의미를 충분히 담는다.  
    선언된 지점에서 초기화하며, 가능한 사용범위를 최소화 한다. 숫자 0 레퍼런스 null  
    단, 첫 단어의 첫 글자는 지역 변수 및 필드 변수의 경우 소문자여야 하고 상수의 경우 대문자여야 합니다.
    예: firstName, lastName또는 MAX_VALUE.

    반복문에서 인덱스로 사용할 변수는 i,j,k 등으로 사용한다.  
    Ex) for(int i = 0; i < 10; i++){}

    지역변수와 멤버변수(전역변수)는 변수명 앞에 밑줄(_)을 사용하여 구별한다.  
    boolean타입의 변수는 접두사로 is를 사용한다 Ex) isCheck


- ## 상수 이름
    상수 이름은 모두 대문자여야 하며 단어는 밑줄로 구분됩니다.  
    Ex) MIN_VALUE또는 PI.

- ## 패키지 이름
    패키지 이름은 모두 소문자여야 하며 단어는 점으로 구분되어야 하고, 가급적 `한단어의 명사`일 것  
    Ex) com.mycompany.project.

- ## 열거형 이름
    열거형 이름은 클래스 이름과 동일한 규칙을 따라야 합니다.

- ## 주석 이름
    주석 이름은 인터페이스 이름과 동일한 규칙을 따라야 합니다.

- ## Note
    - 2023년 02월 26일 첫 발행  
        > 괜찮은 레퍼런스가 있으면, 좀 더 추가하며 완성시켜나가기