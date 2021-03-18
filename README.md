# CS 스터디 질문모음
###
스터디 구성원  
(https://github.com/LEEJ0NGWAN)  
(https://github.com/dss1111)  
(https://github.com/yeong-a)  
## 자료구조 (2021-01-27)
* 우선순위 큐의 구현방법을 설명해보세요
* 힙의 삽입과 삭제는 어떻게 이루어지는지 설명해보세요
* 배열과 비교한 링크드리스트의 장점과 단점
* 스택으로 큐를 구현해보세요
* 해싱 충돌해결 방법에는 어떤것이 있는지 설명해보세요
* 해싱에서 군집화란 무엇이고 이를 해결하려면 어떻게 해야하는지 설명해보세요
* 최소신장트리(minimal spanning tree)란?
* 덱(데큐)란 무엇인지 설명해보세요
* 배열로 큐를만들면 어떤문제가 발생하는가? (원형큐를 왜사용하는가?)
## 알고리즘 (2021-02-03)  
* 불안정정렬과 안정정렬에 대해서 설명해보세요
* 크루스칼, 프림알고리즘에 대해서 설명해보세요
* 다익스트라 알고리즘에 대해서 설명해보세요
* A* 알고리즘에 대해 설명해보세요 -> 추정치를 추가하여 추론적으로 짧은거리를 찾을 수 있음.
* 다익스트라 알고리즘과 비교한 벨만포드 알고리즘의 장점 -> 가중치가 음수에서도 사용가능하다
* DFS를 사용하면 그래프에서 어떤것을 알 수 있는가? -> 노드가 엣지를 타고 방문할 수 있는 인접노드를 모두 탐색할 수 있음
* BFS를 사용하면 그래프에서 어떤것을 알 수 있는가? -> 모든 엣지의 가중치가 같을때 최단경로를 알 수 있음.
* DFS와 BFS중 항상 Optimal한 결과를 얻을 수 있는 것 ->BFS
* 바텀업 방식에서 메모이제이션을 왜 사용하는가?
* 백트래킹은 DP에서 탑다운방식인가? 바텀업방식인가?
## 네트워크 (2021-02-17),(2021-03-05)
* tcp와 udp의 차이점에 대해 설명해보세요
* 순서가 뒤바뀔 수 있는데 왜 UDP를 사용하는지 설명해보세요
* AIMD
* 오류제어방법 Go back N, Selective repeat
* 혼잡제어 AIMD, Slow start, Fast recovery
* 쿠키와 세션에 대해 설명하고 사용하는 이유를 설명해보세요
* DNS란 무엇인지 설명해보세요
* 대칭키와 공개키에 대해서 설명해보세요
* http와 https의 차이점을 설명해보세요
* https는 몇번포트를 사용하나요?
* https 를 사용하기 위한 handshaking과정을 설명해보세요
* https는 비대칭키를 한 번 사용하고 이후 대칭키를 사용합니다. 비대칭키를 한 번만 사용하는 이유를 설명해보세요 
## 운영체제 (2021-02-10)
* 뮤텍스와 세마포어에 대해 설명해보세요
* 데드락이 일어나기 위한 조건에는 어떤 것이 있지 설명해보세요
* 데드락을 어떻게 탐지할 수 있는지 설명해보세요
* 멀티스레드와 멀티프로세스는 언제 사용하는지 설명해보세요
* cpu 스케줄링의 방법에 대해서 설명해보세요
* 우선순위 스케줄링의 문제점에 대해서 설명해보세요
* 페이징이란 무엇이고 왜 필요한지 설명해보세요
* 세그먼테이션에 대해서 설명해보세요
* 내부단편화와 외부단편화에 대해서 설명해보세요
## 디자인패턴
* 리팩토링을 하는이유에대해 설명해보세요
* 상속보다 컴포지션을 사용하면 유리한 점에대해 설명해보세요
## 데이터베이스 (2021-03-15) 
* 정규화를 하는 이유, 반정규화를 하는 이유에 대해서 설명해보세요
* 저장방식에 따른 NoSQL분류를 말해보세요
* db 수직적확장 , 수평적확장이란?
* 트랜잭션의 병행처리란? 병행처리시 발생할 수 있는 문제점을 설명하세요
