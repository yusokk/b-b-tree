C 언어를 이용한 B 트리, B+ 트리 구현

- 참여자 : 김승현, 김유석, 조정훈
- 프로젝트 기간 : 2021.01.08 ~ 2021.01.14
- B 트리 : 
  - 루트를 제외한 노드에서 1개 이상의 키를 갖고, 트리의 균형이 유지되는 2 이상의 자식을 갖는 트리 자료구조
  - 완전 이진 트리, 이진 검색 트리의 확장
  -  각 노드와 노드의 키들이 정렬이 되어 있으며, 동시에 완전히 균형잡힌 트리를 유지하는 성질도 갖고있다.
  - **logtn**의 시간을 보장하기 때문에 이진 트리보다 더 효율적인 검색 시간을 제공
  - 생성, 삽입, 검색, 삭제 기능
  - Visual : 테스트 및 디버깅을 위한 트리 시각화

* B+ 트리 :
  * b트리에서 효율적으로 연속적인 데이터를 읽어올 수 있도록 개선한 자료구조
  * 오직 리프 노드에서만 데이터에 접근할 수 있다.
  * 내부 노드의 키들은 이정표의 역할만 수행
  *  각 리프 노드들은 **연결리스트**로 연결, 연속적인 선형 검색이 가능
  * 생성, 삽입, 검색, 삭제 기능
  * Visual : 테스트 및 디버깅을 위한 트리 시각화
  * Visual_head : 테스트 및 디버깅을 위한 리프 노드의 키 연결리스트 시각화

