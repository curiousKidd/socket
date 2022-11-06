# socket
socket_test

``` java

소켓 통신?
    소켓 프로토콜을 준수한 통신방법
    포트에서 통신을 할때 사용되는 소켓을 직접적으로 사용하는 방식이다
    
    PORT(포트)?
        - 네트워크를 통해 데이터를 주고받는 프로세스를 식별하기 위해 할당받아야 하는 고유한 숫자
    
    SOCKET(소켓)?
        프로세스가 네트워크를 통해서 데이터를 주고받으려면 반드시 열어야 하는 창구 같은 것이다.
    
   - 포트, 소켓
    - 프로세스가 고유하게 받는 것이 포트
    - 그 포트내에서 통신을 위해서 사용되는 것이 소켓
    - 소켓의 경우 포트가 여러개를 만들 수 있다.
        - 같은 protocol, 같은 ip, 같은 port를 가진 데이터가 소켓을 찾아가는 방법?
            - Descriptor(디스크립터) - 소켓 고유 번호 (pid)
    
         
특징?
    1. 실시간 반영
    2. 양방향 통신
    3. stateful 
    4. 통신 유지
    등이 있다

소켓통신을 사용하면 보다 적은 데이터를 사용해서 통신이 가능하다 (stateful이기 떄문)
채팅과 같은 경우 인터넷을 통하지 않고도 통신을 해도 되기 떄문에 웹 통신이 아닌 소켓통신이 유리하다
항시 통신을 유지하기 때문에 데이터 소모측면에서 유리하고, 작은 헤더로도 통신이 가능하다
단 서버측에서 해당 통신을 위한 규약이 정해져 있어야한다

소켓통신의 경우 서버측 소켓과, 클라이언트 소켓이 나뉘어져 있다.
통신 라이브러리를 맞춰줘야 통신이 가능하다



``` 

