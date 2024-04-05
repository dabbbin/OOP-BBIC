
# 📈 주식거래 시스템

## 📉프로젝트 소개
* 사용자가 정보를 입력하고 본인 계정을 이용해 주식을 거래하는 시스템입니다.
* 사용자는 1명으로 고정되어 있으며 주식또한 10개로 고정되어있습니다.

## 🧑‍💻팀원 구성

1. ⭐️ 연주현 (DISNOTACAT)
2. 고경호 (yoaruku)
3. 김다빈 ()
4. 서윤정 ()
5. 최승인 ()

## 🛠️개발 환경
* Develop : JAVA
* Version Constrol : Git
* Communicate : Slack, Figjam, Notion

## 프로젝트 구조
```
├── README.md
└── trading
     ├── src/main/java/com/bbic
           ├── controller
           |    └── CashDispenser.java
           |    └── StockManager.java
           ├── model
           |    ├── dto
           |    |      ├── StockDTO.java
           |    |      ├── User.java
           |    |      └── UserStockDTO.java
           |    ├── BuyStock.java
           |    └── SellStock.java
           ├── run
           |    └── App.java
           └──view
                ├── MainMenu.java
                └── MenuView.java
```
<br>

## 📋역할 분담

#### ⭐️ 연주현
* 주식 매수
  1. 주식 리스트에서 원하는 주식을 선택하여 매수
  2. 보유 주식에 중복된 주식 체크 후 저장
  3. 잔고에서 금액 출금

#### 고경호
* 입출금
  1. 입력받은 금액을 입금하거나 출금
 
* 주식 리스트 조회
  1. 미리 정해둔 주식 리스트를 출력
 
#### 김다빈
* 주식 매도
  1. 보유 주식 리스트에서 원하는 주식을 선택하여 매도
  2. 보유 주식 리스트에서 해당 주식 수량 차감
  3. 잔고에 금액 입금
 
#### 서윤정
* 사용자 데이터셋 생성
  1. 이름, 보유금액, 보유주식을 가진 데이터셋 생성
     
* 사용자 데이터 정보 조회
  1. 사용자 데이터를 조회
  2. 보유주식을 리스트화 하여 출력

#### 최승인
* 메인화면 개발
  1. 프로그램의 시작 입력화면 및 메뉴화면 출력
  2. 메뉴화면에서 선택한 각 메뉴들 연결
 
## 📕 프로젝트 후기

#### ⭐️ 연주현
* 맡은 파트의 상세한 기능에 대해 스스로 잘 이해하지 못했음을 여러번 느꼈습니다. 팀에게 적극적으로 질문하며 해결하려 했지만, 간혹 배우려는 자세보다는 쉽게 해결하려는 태도를 가지기도 하였습니다.
  팀원분들의 도움으로 배운 내용을 적극적으로 활용하고 이해할 수 있는 기회를 가질 수 있었습니다. 협업을 하며 함께 성장 할 수 있도록 서로 존중해야함을 다시 한번 느낄 수 있었습니다.
* 깃, 슬랙과 피그잼 등 다양한 소통 툴을 활용하여 협업하는 환경을 연습할 수 있었습니다. 앞으로는 커밋 메세지와 이슈 관리를 더 중요시 할 필요성을 느꼈습니다.
* 객체기반 언어를 활용하는 장점을 조금 느낄 수 있었습니다. 생성자와 컬렉션을 이해하고 적극 활용하려 하였습니다. 개발을 진행하며 언어를 활용하는 능력이 많이 부족하다고 느꼈고, 많은 예제를 접하여 연습할 수 있도록 하려 합니다.



#### 고경호
* 프로젝트를 시작할 때는 작은 규모의 프로젝트여서 쉽게 해결할 수 있을 것이라고 생각했습니다. 그러나 코드를 작성하는 단계에 들어가니 생각보다 많은 고민과 어려움이 있었고 협업하는데 있어 주의 해야 할 점을 알아가게 되었습니다.
* 프로젝트를 진행하면서 점점 자바코드를 이해하고, 더 나은 방법으로 개선하는 법을 배울 수 있었습니다.
* 팀원들과 소통하는데 있어 너무 나의 주장을 강하게 어필한거같아 조금 후회가 되어 앞으로 비슷한 프로젝트에 참여할 때는 더욱 원활한 소통을 할 수 있도록 노력해야겠다고 생각했습니다.

#### 김다빈
* 예외처리, 입출력을 구현한 이후에 테스트를 해봤을 때 생각하지 못한 오류들이 많이 있었습니다. 이러한 부분을 처음에 제대로 신경쓰지 못한 점이 아쉬웠습니다.   
* 사용자가 예기치 못한 입력을 했을 때, 사용자 입장에서 더 알기 쉽도록 입력 오류 처리를 개선할 필요가 있다고 생각합니다. 
* 각 기능의 메소드를 제대로 나눠 구현하는 방법에 대해서 팀원들에게 많이 배웠습니다. 또한 데이터를 전달하고 전달받는 방법, 테스트 방법 등을 직접 구현하고 활용할 수 있어서 좋았습니다.  

#### 서윤정
* 프로젝트 진행 주제가 정해 졌을 때 과연 내가 할 수 있을까 라는 생각이 들었던 것 같다.
* 일단, 주식이라는걸 해본 적이 없어서 주식 메커니즘을 이해하는게 힘들었다. 하지만, Figma앱을 이용한 도식화를 통해 주식 메커니즘을 잘 이해한 것 같다.
* 이번 프로젝트 부분에서 DTO 생성 부분을 맡아서 다른 팀원분들보다 많이 수월 했던 것 같다.
* 개인적으로 아쉬웠던 점은 주식 값이 계속 변동 할 수 있는 코드를 만들어서 더 develope 해보고 싶다!

#### 최승인
* 프로젝트를 시작할 때, 구현 목표가 단순하다고 생각하여 순조롭게 진행될 것으로 생각했다.하지만 프로젝트를 진행하면서 다른 팀원이 작성한 코드를 이해하고 활용하는 과정에서 어려움을 겪었다. 이 과정에서 팀원들과 코드에 대해 충분히 상의하지 않은 것이 아쉬움으로 남았다.
* 같은 파일에서 동시에 작업하며 발생한 충돌 문제로 인해 상당한 어려움을 겪었지만, 이를 통해 깃을 더 효과적으로 관리하는 방법을 배울 수 있었다,
* 이번 프로젝트를 통해 강사님께서 알려주신 내용을 프로젝트에 적극적으로 적용하며, 배운 지식을 실제 상황에서 활용해보려 노력하였고, 팀원간의 소통의 중요성과 함께, 코드 관리와 협업 도구의 활용에 대한 이해도를 높일 수 있었다.



