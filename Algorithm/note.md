Week 1, Mon
========
첫수업, 교수님께서 대형강의를 좋아해서 온라인강의에 불만이 많다고 하신다.

알고리즘의 사전적 정의: 입력으로부터 출력을 만드는 과정을 애매하지 않게 기술한 것. 문제해결 = Data structure + Algorithm. 이 강의에선 알고리즘 자체를 공부하기도 하지만, 그만큼 중요하게 생각하는 방법을 익히게 될 것이다. 알고리즘을 공부하는건 현재의 문제를 해결하는법을 배우는것이지만, 생각하는 방법을 배우는 것은 미래의 문제를 미리 해결해두는것이나 마찬가지입니다.

이번 강의에서 다룰 중요한 주제들

1.  알고리즘 설계와 분석의 기초. 알고리즘에 대한 개략적인 이야기를 할것이다. 알고리즘 복잡도에 대해 다루게된다.
2.  Recurrences, 점화식. 재귀와 밀접한 관련이 있다. 재귀적 구조를 가진 알고리즘의 복잡도는 어떻게 계산하는가 이런것도 다룸.
3.  Sorting, 정렬. 자구에서도 했지만 더 깊게 배움. 알고리즘 각각의 설명, 복잡도 계산 및 증명, 각각의 아이디어를 깊게 다룸.
4.  Selection, 선택. "n개의 수 중에서 n/3번째로 작은 원소 찾기" 이런걸 다룸. 이런 알고리즘들을 소개함. O(n^2) 복잡도의 원시적인 알고리즘부터 O(nlogn), O(n) 등 다양한 알고리즘을 배움.
5.  Search Trees. 자구에서 배운것보다 더 깊게 다룸. 자료구조의 이론적 퍼포먼스 증명 등
6.  Hash Tables. 얘도 증명 포함됨
7.  Handling Exclusive Sets. 배타적인 집합을 다루는 방법.
8.  Dynamic Programming. 아무리 강조해도 지나치지 않음. "동적 프로그래밍"이라는 단어는 DP가 실제로 어떤것인지랑은 무관해서 부적합한 표현임. 재귀적인 구조를 가진 문제를 푸는 방법. 아주 중요함
9.  Graph Algorithms. DFS, BFS, 미니멈 스패닝 트리, 최단경로문제, Strongly connected component, 토폴로지 소팅 등 다양한 문제를 다루고, 알고리즘이 왜 맞는지 증명도 함.
10. Greedy Algorithms. 드물게 그리디한 접근을 해도 글로벌 옵티멈을 보장함. 프림 알고리즘, 크루스칼 알고리즘, 다익스트라 알고리즘. 이런 예가 많지 않은데 이런 그리디들을 배움. [매트로이드]라는 수학적인 구조를 가지면 어떤 성질로 도움을 받을 수 있는지, 이런걸 배움. 매트로이드는 그래프의 더 abstract한 mathematical object
11. String Matching. Exact matching을 배우면 Approximate matching 알고리즘도 만들 수 있음.
12. NP-Complete/Hard. 이 앞 챕터까지는 어떤 문제를 잘 풀수있을까에 대한 이야기인데, 이 챕터는 어떤 문제가 풀기 힘드냐를 배우게됨. "현실시간에 풀 수 없다"는 가정을 다들 믿고 살긴 하는데 그것도 증명이 안되어있어서 세계 7대 난제로 등록되어있음.
13. Problem Space Search. 문제를 푸는 Rugged한 공간에서 어떻게 이동할것인가, 어떻게 탐색을 할것인가에 대해 배움. 문제공간의 특성, 문제공간을 어떤 관점으로 보느냐.

[매트로이드]: https://en.wikipedia.org/wiki/Matroid

추천교재

1. 쉽게 배우는 알고리즘, 문병로, 한빛미디어
2. Introduction to Algorithms, Cormen et al, MIT Press.

숙제는 총 4회. 2회는 Handwriting, 2회는 프로그래밍.

보통 알고리즘 강의는 30명정도가 하는데, 지금 알고리즘 수업이 120명이 하는 대형강의가 되었다. 조교들이 본인 연구를 하면서 동시에 숙제 채점을 하기때문에 굉장히 일이 힘들다. 조교들이 대답이 늦더라도 양해를 부탁한다.

시험은 반드시 교실에서 봄. Open Book. 시험시간 들고올 수 있는것은 책 두 권, 강의 노트 프린트+메모, 기출 문제 및 자신이 풀어본 내용. 두 교실로 나눠서 시험을 보게됨. 디지털 미디어는 가져오면 안됨

&nbsp;

Week 1, Wed
========

### 알고리즘을 공부하는 목적

1.  특정 문제를 해결하는 방법을 배우기도 있지만
2.  체계적으로 생각하는 훈련을 하고
3.  지적 추상화 레벨의 상승(Intellectual abstraction)을 이룩할수있다. 연구나 개발에 있어 정신적 여유를 유지하기 위해 매우 중요한 요소다!

문교수님 왈 워낙 다양한 문제를 다루고 시행착오를 겪고 나니까, 새로운 문제 새로운 프로젝트를 다룰때에 "이걸 해결할 수 없으면 어쩌나"하는 느낌을 겪지 **못할까봐** 두렵다. 너무 쉬우면 제대로된 논문으로 나오지도 않고, 남에게 내세우지도 못하고, 자신에게 만족감도 줄수없고.

챌린징한 문제를 푸는 경험을 누적해나가는게 중요하다. 지금 님들한테 주는 과제가 처음 보면 꽤 어려울 수 있는데, 계속 머리에 넣어두고 계속 생각해보면 듀데이트가 될 즈음이 되면 어떻게든 풀게될겁니다. 머리속에 일단 넣어두고있으면 밥먹을때 버스탈때 잘때 잠재의식이 계속 풀고있을거다!

문제 자체를 해결하는 알고리즘을 배우는것도 중요하지만, 생각하는 방법을 배우는게 더 중요하다! 미래에 맞딱드릴 문제를 해결할 빌딩블록을 얻게될거다.

알고리즘은 자료구조의 확장이다. 자료구조는 건축이나 자동차 제작의 건축자재, 부품, 모듈같은것임. 이거를 조립해서 더 복잡하고 어려운 문제를 푸는거다.

### 알고리즘 수행시간
바람직한 알고리즘은 명확해야하고, 가능하면 간명해야한다. 지나친 기호적인 표현들은 오히려 명확성을 떨어트린다. 명확하게 기술할 수 있다면 그냥 말로 풀어써도 됨.

바람직한 알고리즘은 효율적이어야한다. 수행시간 효율적이어야 하고 알고리즘이 차지하는 메모리 공간이 효율적이어야함. 이 알고리즘 클래스에선 수행시간에 주로 집중한다.

알고리즘의 수행시간에는 여러가지 클래스가 있다. log N, N, NlogN, N^2, N^3, 2^N, 등.

알고리즘 수행시간이 n^2/5, 5*n 이런식으로 주어진다면 상수때문에 입력이 작을때에는 n^2/5 알고리즘이 더 빠를수도있지만, 입력이 충분히 커지면 차수가 큰 알고리즘이 이기게된다. asymptotic(점근의) notation에서는 계수가 중요하지 않고 차수가 중요하다.

알고리즘의 수행시간은 for 문 반복회수, 특정 행이 실행되는 회수, 함수 호출회수 등 다양한 기준으로 결정할 수 있다.

(예제로 수행시간 계산하는 문제 여럿 풀어봄)

### 재귀와 귀납적 사고
Optimal Substructure: 큰 문제의 최적해가 자신보다 작은 문제의 최적해를 포함하는 구조

예제: 머지소트 `T(n) = 2*T(n/2) + cn`

```
T(n) = 2*T(n/2) + cn
     = 2^2*T(n/2^2) + 2cn
     = 2^3*T(n/2^3) + 3cn
     ...
     = 2^k*T(1) + kcn   (k = log_2 n)
     = a*n + b*nlogn
```