#🌳Memory Tree🌳
-
# ☀️기억의 나무는요!

- **고령화 사회로 접어들며 치매는 할머니, 할아버지들의 가장 큰 걱정거리로 접어들고 있습니다. 기억의 나무(Memory-Tree)를 통해 “나무가 열매를 맺듯, 노인분들의 기억과 경험이 축적되어 추억이라는 소중한 열매를 맺도록 하자!” 는 취지로 만들게 되었습니다!**

# 💭아이데이션

## 🔥문제 상황

**변화에 대한 거부감**

할머니, 할아버지께서는 익숙하지 않은 훈련 방식과, 활동에 대해 어렵고 피곤하다고 느끼시는 경우가 많고, 훈련이 효과가 없을 것이라는 생각으로 훈련을 하는 것을 꺼려하십니다.

**일상 기억의 퇴색**

일상이 반복적이고 단조로워서 기억할 만한 특별한 사건이 없으므로 뇌를 자극할 기회가 줄어듭니다. 실제로 저희 할머니께 어제 뭐 했어? 라고 물어보면 기억이 안난다거나 몇 일 전의 한 일을 말씀하시곤 하는 것을 목격하였습니다. 

(카카오 메시지 API 구현시) **가족과의 소통 단절**

자손들과 공감대가 부족하고, 거리가 멀다는  등의 이유로 가족 구성원 간의 소통이 점차 줄어드는 문제가 있습니다.

## ✨해결방안

**거부감이 없는 친화적인 방식**

'기억의 나무'는 익숙하지 않은 애플리케이션에 대한 부담을 줄이기 위해 간단하고 직관적인 인터페이스를 제공하며, 쉬운 난이도의 게임으로 거부감을 줄일 수 있도록 설계하였습니다!

또한 하루 일과를 간단한 단어 형식으로 기록하여, 해당 내용을 기반으로 다음 날 퀴즈를 제공하여 기억을 되새기고 뇌를 자극할 수 있도록 설계하였습니다.

**성취도 부여**

저희 할머니는 박스와 술병을 모아 고물상에서 동전을 모으시는 모습을 보며, 리워드를 제공한다면 할머니들께서도 게임에 참여하며 기억력 증진에 도움을 받을 것이라 생각했습니다. 이 리워드는 추후 카페, 식당, 편의점 등에서 교환 가능하며, 동시에 경험치를 통해 초기 화면의 캐릭터가 3의 N승만큼 성장하여 성취감을 극대화할 수 있도록 설계하였습니다.

(카카오 메시지 API 구현시)**소통**

가족들에게 일일 미션 완료 문자를 카카오톡으로 전달해, 세대 간 대화의 주제를 만들고 공감대를 형성하며, 거리가 멀어도 소통의 기회를 마련할 수 있습니다.

## 🔔기대효과

- 게임을 통해 두뇌를 활성화할 수 있습니다.
- 일기를 쓰며 하루를 되돌아보고, 다음 날 퀴즈를 통해 한 번 더 기억을 되새기며 두뇌를 자극합니다.
- 리워드 지급으로 사용자가 미션에 적극 참여하도록 유도할 수 있습니다.

# 🌸기능정리

### 두뇌 회전 게임

1. 1부터 12까지 랜덤으로 배치되어있는 숫자들을 순서대로 찾는 게임
2. 뒤집힌 카드들의 짝을 찾는 게임
3. 틀린 글자 찾기 게임 ( 3x3 배열에 가위가 8개, 가위에서 변형된 글자 1개 (까위)면 까위를 찾는 게임 )

### **일과 작성 및 퀴즈**

하루에 있었던 일과를 단어와 같은 형식으로 작성하고, 오늘 있었던 일과의 내용을 다음날 QUIZ를 통해 기억을 되새기는 기능

### **리워드**

게임 클리어시 경험치와, 리워드를 제공하여 캐시워크와 같이 리워드를 모으고 바우처 형식으로 카페, 편의점등 다양한 곳에서 교환이 가능합니다. 또한 경험치를 통해 시작화면의 캐릭터를 성장시킬 수 있습니다.

### 통계

각 게임의 최고기록을 타이틀에 위치시켜, 사용자가 최고기록을 갱신하기 위해 더 많은 집중을 유도합니다.
