# 투자자로 성공하기

# [ 목차 ]
### 1. [게임명: 투자자로 성공하기]
### 2. [컨셉](#1)
### 3. [관련 이미지와 동영상](#2)
### 4. [대표 이미지](#3)
### 5. [컨셉과 대표이미지 기반 작품 묘사](#4)
### 6. [투자자로 성공하기의 구성 요소](#5)
### 7. [게임 시스템 디자인](#6)
#### a. [게임 오브젝트 분해](#a)
#### b. [파라미터](#b) 
#### c. [행동](#c) 
#### d. [상태](#d) 
#### e. [플레이어 캐릭터 속성(파라미터)](#e) 
#### f. [게임의 규칙](#f)
#### g. [게임에서 사용될 규칙](#g)
### 8. [요구사항 & 흐름도](#7)
#### a. [요구사항 (6주/1년)](#h)
#### b. [시간별 흐름도](#i)
#### c. [키보드 이벤트에 대한 흐름도](#j)
### 9. [개발작업 일정(6주)](#8)
### 10. [구현 목표& 작업결과(6주)](#9)
#### a. [1주차](#k)
#### b. [2주차](#l)
#### c. [3주차](#m)
#### d. [4주차](#n)
#### e. [5주차](#o)
#### f. [6주차](#p)


# 2. [컨셉] <a name='1'></a>

## 메인컨셉 : 투자 (Investment)

- 코로나 19이슈로 인해 암호화폐 시장(비트코인), 주식등의 금융투자를 하는 사람들이 늘어나며 이에 대한 정보나 지식등을 배울 수 있게 함.

- 솔로 플레이를 지향하여 개발

- 본인이 원하는 방향대로 투자를 하며 자금력을 키워나감

- 장르: 시뮬레이션


### 서브 컨셉 1 : 시뮬레이션(Simulation)

- 시뮬레이션은 ‘이런 식으로 진행하면 어떨까?’ 라는 if의 성격이 강함

- 자유도가 높기에 플레이어 취향대로 할 수 있는 특성이 존재

### 서브 컨셉 2 : 돈 (Money)

- 투자를 통해 돈을 벌 수 있으며 번 돈을 통해 다른 사업에 투자를 하며 안정적인 이익실현을 할 수 있음

### 서브 컨셉 3 : 자유(Liberty)

- 시뮬레이션 게임 특성 중 하나이며 최대 장점 중 하나

- 하나의 방법으로 진행 한 이후 다른 방법으로 게임을 진행하며 게임의 신선함을 추구

### 서브 컨셉 4 : 건설 (build)

- 투자한 돈을 통해 땅을 사고 구입한 땅에 건물을 올려 또 다른 이익을 취할 수 있다. 

<br><br>

# 3. [관련 이미지 & 동영상] <a name='2'></a>

- 이미지  
  <img src="./img/relation_img.PNG">
  <img src="./img/relation_img2.PNG">
- 동영상

  [![](./img/youtube_img.png)](https://youtu.be/jrcrMw55IO4)
  [![](./img/youtube_img2.png)](https://youtu.be/omoSCTVtjCM)
<br><br>

# 4. [대표 이미지] <a name='3'></a>

![그림](./img/rep_img2.PNG)

<br><br>

# 5. [컨셉 & 대표이미지 기반 작품묘사] <a name='4'></a>

> ### 대표이미지 기반 :
 <img src="./img/explain_img2.PNG">

> ### 컨셉 기반:
투자: 투자를 통해 돈을 모아가는 것이 목표
<br><br>
시뮬레이션: 여러가지 상황이 나올 수 있게 하여 상황마다 다른 플레이를 할 수 있도록지향한다.
<br><br>
돈: 모은 돈을 통해 주식 말고도 다른 곳에 돈을 쓸 수 있게함
<br><br>
자유: 플레이어가 원하는 과정의 플레이를 할 수 있게함.
<br><br>
건설: 모은 돈을 통해 건물을 짓고 도시를 건설할 수 있음.
<br><br>

<br><br>

# 6. [<투자자로 성공하기> 구성 요소] <a name='5'></a>

- 투자를 통해 부자가 되어보자

<br>

## 6-1. 메커니즘

[도전 과제]

1. 주식, 암호 화폐 거래 등을 통해 돈을 확보한다.

2. 확보한 자금을 통해 건물을 짓고 자본을 증가 시킨다.

[재미 요소]

1. 다른 게임들과 달리 자본이 올라갈 수도 있고 내려갈 수 도 있다.
2. 필요하다면 은행에서 대출을 하여 대출금을 통해 투자를 유치 할 수 있다.
   하지만 대출 상환기간까지 대출금을 갚지 못한다면 강제적으로 대출한 금액과 같은
   가치를 건물 등을 압수한다.
3. 소지한 금액, 건물 모두 0이고 대출금까지 갚지를 못한다면, 파산으로 이어지며 
파산시 게임이 종료가 된다. 
4. 투자를 하고 난 후 변동 되는 투자 금액은 다음 날 확인 할 수 있다.
5. 캐릭터에게 스테이터스를 주어 다른 요소에서도 돈이 빠져나갈 수 있게끔 유도한다.
6. 만일 특정 스테이터스가 일정 수치로 떨어지면 플레이어의 체력이 떨어지기 시작하며
체력이 모두 소모되면 그 즉시 게임을 종료 시킨다.


<br>

## 6-2. 이야기

[기획 의도]  
코로나 19이슈로 인해 주식, 암호화폐등에 대해 사람들이 많은 관심을 가지게 되고 이러한 경제 활동을 꺼려하고 다가가기 힘들어 하는 사람을 주위에서 쉽게 볼 수 있었다. 
이런 사람들에게 부담 되지 않게 활동 등을 알려주며 간단하게 즐길 수 있게 만들어 보고 싶어서 기획하게 되었다.

[세계관]  
일만 하면서 돈을 벌어 왔던 플레이어가 친구에게 일을 하지 않아도 돈을 벌 수 있다는 솔깃한 이야기를 듣게 되었다. 
플레이어는 ‘워렌 버핏’과 같은 최고의 투자자가 되기 위해 회사를 그만두고 투자에만 몰두하게 된다.

<br>

## 6-3. 미적요소

[디자인][컬러]  
방 배경, 도시 배경을 제작하고 방 배경화면에서는 주식, 암호화폐 거래등의 투자활동, 대출, 세금납부, 우편물 등의 UI를 제작하여 투자 활동을 할 수 있게 한다.
도시 배경에서는 빌딩, 주택, 백화점, 축구장, 야구장 등등 여러 다채로운 건물들을 디자인하여 본인의 마음대로 건물을 올릴 수 있는 재미를 줄 것이다.


[음향]  
평화로운 배경음악을 주로 틀어주고 각 상황에 맞는 효과음을 삽입하여 몰입감을 유도한다.
<br>

## 6-4. 기술

Unity엔진을 이용하여 제작합니다. 모바일, pc모두 구동이 가능하게 제작을 할 것입니다. 
다른 pc게임처럼 사양이 높게 나오진 않겠지만 간단하고 가볍게 재밌게 즐길 수 있는 게임을 개발 할 것입니다.


# 7.[ 게임 시스템 디자인 ] <a name='6'></a>
## a. 게임 오브젝트 분해 <b name = 'a'></b>


|연번|오브젝트 이름|오브젝트 이미지|
|---|---|---|
|1|건물|<img src="img/build.PNG">|
|2|음식|<img src="img/food.PNG">|
|3|방 내부|<img src="img/room.PNG">|
|4|활동|<img src="img/Active.PNG">|

## b. 파라미터 <b name = 'b'></b>

### b-1. 건물


|속성|영문명칭|설명|
|---|---|---|
|원룸 건물|Studio_apartment|대학생이나 공시생들이 살 수 있는 곳|
|아파트|Apartment|주민들이 살 수 있는 곳|
|축구장|Soccer_field|축구경기를 관람 할 수 있는 곳|
|야구장|Baseball_field|야구경기를 관람 할 수 있는 곳|
|스포츠센터|Sports_center|실내스포츠와 같은 다양한 스포츠를 즐길 수 있는 곳|
|상가|Strip_Mall|다양한 상정들이 있는 곳|
|호텔|Hotel|여행객들이 묵어가는 곳|



|속성|영문명칭|설명|
|---|---|---|
|건물 가치|b_price| 건물 생산에 필요한 가격이자 건물의 가치이다|
|건물 수입|b_import| 건물이 주기적으로 벌어들이는 수입|
|건설 시간|b_time| 건물을 건설하는데 걸리는 시간|



### b-2. 음식


|속성|영문명칭|설명|
|---|---|---|
|볶음밥|BokkeuBob|각종 야채와 밥을 볶은 음식|
|짜장면|JJaJangmyeon|중화요리 대표 음식중 하나. 춘장과 야채, 고기를 볶아 국수에 비벼먹는 음식|
|짬뽕|JJamBBong|중화요리 대표 음식중 하나. 야채와 김치 등을 넣고 끓인 음식 |
|삼겹살|Samkyubsal|돼지고기를 불에 구운 음식|
|김치찌개|Kimchi_JJigae|야채와 김치등을 넣고 끓인 음식|
|파스타|Pasta|이탈리아의 면을 이용한 음식|
|라멘|Ramen|육수를 오래 우려낸 일본식 라멘|

|속성|영문명칭|설명|
|---|---|---|
|음식의 가격|F_price|음식을 먹기위해 소비해야하는 돈이다.|
|포만감|F_starve| 음식을 먹으면 배고픔 수치가 올라간다.|


### b-3. 방 내부


|속성|영문명칭|설명|
|---|---|---|
|컴퓨터|Computer|투자활동이나 메일을 볼 수 있다.|
|침대|bed|침대에 누워 잠을 청할 수 있다.|
|식사 메뉴|Meal_Menu|원하는 음식을 시켜 밥을 먹을 수 있다.|
|활동 메뉴|Activate_Menu|원하는 활동을 할 수 있다.|


### b-4. 활동 아이콘

|속성|영문명칭|설명|
|---|---|---|
|운동|Exercise|간단한 운동을 한다.|
|산책|Walk|집 주변을 돌며 산책한다.|
|영화 감상| Movie|영화를 감상한다.|
|독서| Read| 책을 읽는다.|


## c. 행동 <b name = 'c'></b>


### c-1. 캐릭터(PC/NPC)


|행동|설명|
|---|---|
|대기|캐릭터가 아무것도 하지않는 상태를 뜻하며 정처없이 방안을 돌아다닌다.|
|투자활동|캐릭터가 의자에 앉아 컴퓨터를 사용한다.|
|식사|식탁에 앉아 음식을 먹는다.|
|자기|침대에 누워 잠을 청한다.|
|책읽기|식탁에 앉아 책을 읽는다.|
|영화 보기| 컴퓨터에 앉아 영화를 본다.|

## d. 상태 <b name = 'd'></b>


### d-1. 건물 

|현상태| 전이상태| 전이조건|
|---|---|---|
|건설 부지| 건설 중| 원하는 위치에 건물 형상을 놓고 건설시작을 버튼을 누른다.|
|건설 중| 건설 완료| 게임 내 시간 3~7일 지나면 건설이 완료된다.|
|건설 완료| 철거 중| 원하는 건물을 누르고 철거 버튼을 누른다.|
|철거 중 | 철거 완료| 게임 내 시간 4일이 지나면 철거가 완료된다.|

### d-2. 플레이어 

|현상태|전이상태|전이조건|
|---|---|---|
|대기|투자활동|컴퓨터 모양의 오브젝트를 누른다.|
|대기|수면|침대 모양의 오브젝트를 누른다.|
|대기|식사|식사메뉴 중 하나를 고른다.|
|대기|운동|활동 메뉴중 운동을 고른다.|
|대기|책 읽기|활동 메뉴 중 책을 고른다.|
|대기|산책|활동 메뉴 중 산책을 고른다.|
|대기|영화 감상|활동 메뉴 중 영화를 고른다.|

## e. 플레이어 캐릭터 속성 <b name = 'e'></b>


|속성|영문명칭|설명|
|---|---|---|
|스태미너|stamina|플레이어의 스테미너를 나타내고 0~100까지 수치를 준다.|
|배고픔|starve|플레이어의 배고픔 상태를 나타내며 100에서 0으로 수치가 점점 떨어진다.|
|스트레스|stress|플레이어의 스트레스 수치를 나타내고 0~100까지 수치를 준다.|
|이름| name| 플레이어의 이름|

## f. 게임의 규칙 <b name = 'f'></b>
1) 핵심 규칙
- 게임 내 1시간은 실제 시간 1분으로 한다. (실제 시간 24분)

- 캐릭터의 스테미너 수치가 0이되면 투자활동 외엔 아무런 활동을 하지 못한다.

- 캐릭터의 스트레스 수치가 100이 되면 캐릭터가 사망한다.

- 캐릭터의 배고픔 수치가 0인상태로 3일동안 유지되면 캐릭터가 사망한다.

- 첫 시작 금액은 500만원에서 시작을 한다.

2) 보조 규칙
- 수면 후 스테미너 수치는 70이 회복이 되고 스트레스 수치는 20, 배고픔 수치는 40 감소한다.

- 주식은 종목마다 하루당 변동률이 최대 +30% -30%이다.

- 비트코인은 종목마다 하루당 변동률의 최대치가 없다.

- 플레이어는 게임 내 시간 오전 0시가 되기 전까지 얼마든지 구매한 종목의 수를 변경이 가능하다.

- 오전 0시가 되면 메일로 변동된 투자금액을 받을 수 있다.

- 각 식사 메뉴를 통해 배고픔 수치를 올릴 수 있다,

- 각 활동 메뉴를 통해 스테미너를 소모하여 스트레스 수치를 감소 시킬 수 있다.

- 보유 자금 2억으로 땅을 구입 할 수 있다. 구입한 이후 건물 건설기능이 활성화 된다.

- 구입한 건물들은 일주일마다 정기 수입을 낸다.

- 일정 금액을 주고 건물을 업그레이드 하면 건물의 수입이 늘어난다.

- 매달 말일 마다 세금을 납부해야한다.

- 보유자금에 따라 납부해야하는 세금이 달라지며 최대 수입의 50%의 세금을 납부해야한다.

- 구입한 건물을 철거해야 한다면 건물의 가치의 40%만큼을 돌려받을 수 있다. 철거는 게임내 시간 4일이 소요된다.

- 자신의 건물 인수를 승인한다면 철거를 하지 않고 바로 자신의 땅에서 해당건물이 사라진다.

## g. 게임에서 사용될 공식 <b name = 'g'></b>
-시간당 소모 되는 배고픔 수치
<br><br>
(현재 배고픔 수치)-(5 * (게임 내 흐른 시간))

- 주식 투자금액 변동
<br><br>
투자금액 + (투자금액 * 랜덤변동률) = 최종 변동액
변동률범위: -30%~+30%

- 암호화폐 투자금액 변동
<br><br>
투자금액 + (투자금액 * 랜덤 변동률) = 최종 변동액
변동률 범위: -200%~+200%

# 8. [ 요구사항 &  흐름도] <a name='7'></a>

## a. 요구사항 (6주/1년) <b name = 'h'></b>
### 1. 요구사항 (6주)
#### 1. 게임화면
- ~~쿼터뷰의 형태로 방의 모습을 비춰준다.~~
- ~~캐릭터가 정처없이 돌아다닌다.~~
- ~~우측상단에는 현재 소지하고 있는 금액을 알 수 있는 UI를 배치한다.~~
- ~~처음 게임 시작시에는 500만원으로 시작을 한다.~~
- ~~방 내부에는 침대, 컴퓨터, 식탁이 있다.~~
- ~~우측하단에는 캐릭터의 현재 상태를 알 수 있는 스테이터스 표시기를 만든다.~~
- ~~스테이터스 표시기에는 스테미너, 배고픔, 스트레스수치가 표시된다.~~
- ~~우측상단에는 게임 내 시간을 알 수 있는 시간을 표시한다.~~
- ~~침대 오브젝트를 누르면 캐릭터가 잠을 청한다.~~
- ~~침대 오브젝트는 게임 내 시간 오후 10시 이후 활성화 된다.~~
- ~~컴퓨터 오브젝트를 누르면 캐릭터가 컴퓨터 앞에 앉고 컴퓨터화면으로 전환된다.~~

#### 2. 컴퓨터 화면
- ~~컴퓨터화면에는 활동 버튼, 주식시장 및 암호화폐시장 버튼, 건설, 메일, 은행버튼이 있다.~~
- ~~우측 하단에는 게임 내 시간을 알려주는 시계가 있다. ~~
- ~~왼쪽 하단에는 전원 버튼이 있으며 누르면 다시 게임화면으로 돌아간다.~~
- ~~주식시장 및 암호화폐시장 버튼을 제외한 버튼은 비활성화 되어있다.~~
- ~~주식및 암호화폐시장 버튼을 누르면 주식, 암호화폐 두가지 버튼으로 나뉘어 진다.~~
- ~~주식 버튼을 누르면 주식시장 화면으로 넘어간다.~~
- ~~암호화폐 시장 버튼을 누르면 암호화폐시장 화면으로 넘어간다.~~


#### 3. 거래시장 화면
- ~~우측 하단에는 게임 내 시간을 알려주는 시계가 있다. ~~
- ~~주식시장화면에서는 총 3개의 회사가 상장되어있으며 각 회사마다 1주의 가격이 다르다.~~
- ~~주식 시장은 하루 최대 변동률이 +-30%이다.~~
- ~~주식 시장과 동일하게 3개의 암호화폐가 상장 되어있다.~~
- ~~암호화폐 시장은 하루 가격 변동의 제한이 없다.~~
- ~~주식은 오전 9시부터 오후 3시까지 마음대로 투자를 변동 할 수 있으나 오후 3시 이후에는 주식 거래시장에서 거래를 할 수 없다.~~
- ~~암호화폐 시장은 시간 제한 없이 거래 할 수 있다.~~

### 2. 요구사항 (1년)

#### 1. 메인화면
- 화면중앙부분에 게임 타이틀인 '투자자로 성공하기'로 된 텍스트가 있다.
- 텍스트 아래에는 게임시작 버튼, 설정버튼, 게임종료 버튼 순으로 위에서 아래로 나열되어 있다.
- 게임시작버튼을 누르면 게임화면으로 넘어간다.
- 설정버튼을 누르면 설정화면이 팝업이 된다.
- 게임종료 버튼을 누르면 게임을 종료한다.

#### 2. 설정화면
- 좌측에는 위에서 순서대로 BGM, 효과음 텍스트가 있다.
- 각 텍스트의 우측에 0~100의 Bar가 있다.
- 각 Bar의 스크롤을 이용하여 BGM, 효과음의 크기를 조절할 수 있다.
- 하단 왼쪽에는 취소버튼, 오른쪽에는 확인 버튼이 있다.
- 취소버튼을 누르면 설정하기 이전의 상태로 돌아가며 메인화면으로 돌아간다.
- 확인버튼을 누르면 설정상태가 저장이 되며 메인화면으로 돌아간다.

#### 3. 게임화면1(방)
- 캐릭터의 스테미너가 0이된다면 주식 및 암호화폐시장 버튼, 수면을 제외한 행동이 모두 제한된다.
- 식탁을 누르면 캐릭터가 식탁으로 이동하여 의자에 앉는다.
- 캐릭터가 식탁에 있는 의자에 앉으면 식사메뉴가 팝업된다.
- 식사메뉴에는 7개가 있다.
- 각 식사메뉴에는 감소되는 자금 스트레스 수치, 증가하는 배고픔 수치가 다르다.
- 하나의 식사메뉴를 선택 후 금액을 지불하면 캐릭터가 밥을 먹는다. 
- 배고픔 수치의 0이 3일동안 유지가 된다면 캐릭터가 죽게되고 게임오버 화면으로 이동한다.

#### 4. 컴퓨터 화면
- 건설버튼을 제외한 비활성화된 버튼들을 활성화 시킨다.
- 건설버튼을 제외한 각 버튼들을 누르면 기존 버튼들이 사라지며 새로운 팝업화면을 띄운다.
- 팝업화면의 오른쪽 상단에 x버튼을 누르면 이전으로 돌아간다.
- 활동 버튼을 누르면 팝업화면에 운동, 산책, 영화보기, 책읽기 버튼이 새로 생긴다.
- 각 버튼에는 소모되는 스테미너 값, 감소되는 스트레스 수치등이 표시 되어있다.
- 건설버튼은 대출금액을 제외한 소유금액 2억이되면 버튼이 활성화 된다.
- 건설버튼을 누르면 게임화면2(건설부지)로 이동한다.
- 메일 버튼을 누르면 받은 메일 목록함이 열리고 주식 및 암호화폐시장에서의 좋은 정보들을 확인 할 수 있다.
- 낮은 확률로 인수요청 메일을 받을 수 있으며 수락을 하면 제시한 가치 만큼의 돈을 구할 수 있다.
- 은행 버튼을 누르면 팝업화면에 대출, 입금, 출금, 대출 상환, 세금납부 버튼이 나오며 중앙 상단에는 저축한 돈을 확인 할 수 있다.
- 대출버튼을 누르면 또다른 팝업화면이 나온다.
- 팝업화면에는 각 대출 상품들을 나열해 놓은 목록이다.
- 각 대출상품은 상환기간, 대출금액, 이자율이 다르다.
- 기간안에 대출금을 상환 하지 못한다면 대출금의 1.5배만큼의 돈을 강제로 회수해 간다.
- 한달에 한번 세금 납부메일을 받게되는데 기한내에 세금을 납부하지 못한다면 납세해야하는 금액의 10배를 강제로 회수해간다.
- 세금은 각 구간별로 나뉜다. 소지금 1억이하는 소지금의5%, 1억이상 10억 이하는 소지금의 10%, 10억이상 50억이하 소지금의 20%, 50억 이상은 소지금의 35%를 세금으로 책정한다. 

#### 5. 게임화면2(건설부지)
- 쿼터뷰형식이며 오른쪽 하단에 건물 목록버튼이 있다.
- 우측 상단에 집모양 버튼이 있으며 버튼을 누르면 게임화면1로 돌아간다.
- 집모양 버튼의 좌측에 소지한 금액을 나타내는 UI가 있다.
- 화면의 좌측상단에는 게임 내 시간을 나타내는 시계가 있다.
- 버튼을 누르면 팝업화면이 나오며 각 건물들의 버튼들이 나온다.
- 팝업화면 우측상단에 X버튼을 누르면 팝업화면이 닫힌다.
- 각 건물들은 건설비용, 건물 수입, 건설시간이 다르다.
- 건물목록중 하나를 선택하면 팝업화면이 닫히고 초록색으로 된 건물 잔상이 화면중앙에 생성된다. 
- 생성된 건물 잔상은 드래그를 통해 마음대로 움직일 수 있다.
- 건물을 지을 수 없는 칸이 있을경우 해당부분의 잔상을 빨간색으로 전환한다.
- 잔상의 색이 초록색이면 오브젝트 중앙에 체크버튼, X버튼을 생성한다.
- 체크 버튼을 누르면 건설이 시작되고 X버튼을 누르면 잔상이 사라진다.

## b. 시간별 흐름도 <b name='i'></b>
### 1. 캐릭터 상태 관련 흐름도
<img src="./img/Time_flowchart.PNG">

### 2. 투자활동 관련 흐름도
<img src="./img/flowchart2.PNG">

## c. 키보드 이벤트에 대한 흐름도 <b name = 'j'></b>

<img src="./img/Key_flowchart3.PNG">

# 9. [개발작업 일정] <a name='8'></a>
<img src="./img/Schedule.PNG">

변경 개발 작업


<img src="./img/Change_schedule.PNG">

# 10. [개발작업 일정] <a name='9'></a>
## a. 1주차
### 구현 목표
작업명 :  게임화면 Scene 작업

해당 요구사항 : 

1) 게임화면1에서는 쿼터뷰의 형태로 방의 모습을 비춰주고 캐릭터가 돌아다닌다.

2) 방 내부에는 침대, 컴퓨터, 식탁이 있다.

3) 우측하단에는 캐릭터의 현재 상태를 알 수 있는 스테이터스 표시기를 만든다.

4) 스테이터스 표시기에는 스테미너, 배고픔, 스트레스수치가 표시된다.

작업 내용 : 

1) 쿼터뷰 형태로 방의 모습을 제작하고
2) 캐릭터를 내부에 배치하고
3) 스테이터스 표시기 UI 제작 3개

### 작업 결과
1) 쿼터뷰 형태로 방의 모습을 제작(100%)
2) 캐릭터를 내부에 배치 (100%)
3) 스테이터스 표시기 UI 제작 3개(100%)

### 결과동영상
<video width="100%" height="100%" controls="controls">
  <source src="./img/1Week.mp4" type="video/mp4"></video>


## b. 2주차
### 구현 목표
작업명 : 캐릭터 움직임 및 오브젝트 상호작용, UI추가작업

해당 요구사항 : 

1-2)  캐릭터가 방을 정처없이 떠돈다.

1-11)  컴퓨터 오브젝트를 누르면 캐릭터가 컴퓨터 앞에 앉고 컴퓨터화면으로 전환된다

1-3)  우측상단에는 현재 소지하고 있는 금액을 알 수 있는 UI를 배치한다.

1-4)  처음 게임 시작시에는 500만원으로 시작을 한다.

작업 내용 : 

1)캐릭터가 방 안에서만 돌아다니게 한다.

2)컴퓨터 오브젝트를 누르면 캐릭터가 컴퓨터 오브젝트 쪽으로 이동

3)이동 후에 새로운 Scene으로 전환

4)소지하고 있는 금액을 알 수 있는 UI 배치

### 작업 결과

1)캐릭터가 방 안에서만 돌아다니게 한다. (90%) -> 이유: 버그가 발생하여 한번씩 방밖으로 나가는 경우가 생김
                                                    추후 버그 수정 
                                                    
2)컴퓨터 오브젝트를 누르면 캐릭터가 컴퓨터 오브젝트 쪽으로 이동.(50%) -> 이유: 동작을 하지 않음 추후 수정 할 것임

3)이동 후에 새로운 Scene으로 전환(100%)

4)소지하고 있는 금액을 알 수 있는 UI 배치(100%)

### 결과동영상
<video width="100%" height="100%" controls="controls">
  <source src="./img/2Week.mp4" type="video/mp4"></video>



## c. 3주차
### 구현 목표

작업명 : 컴퓨터 화면 제작

해당 요구사항 : 

2-1)컴퓨터화면에는 활동 버튼, 주식시장 및 암호화폐시장 버튼, 건설, 메일, 은행버튼이 있다.

2-3)우측 상단에는 X버튼이 있으며 누르면 다시 게임화면으로 돌아간다.

2-4)주식시장 및 암호화폐시장 버튼을 제외한 버튼은 비활성화 되어있다.

2-5)주식및 암호화폐시장 버튼을 누르면 주식, 암호화폐 두가지 버튼으로 나뉘어 진다.

2-6)주식 버튼을 누르면 주식시장 화면으로 넘어간다.

2-7)암호화폐 시장 버튼을 누르면 암호화폐시장 화면으로 넘어간다.

3-2)주식시장화면에서는 총 3개의 회사가 상장되어있으며 각 회사마다 1주의 가격이 다르다.

작업 내용 : 

1. 실제 컴퓨터 바탕화면처럼 꾸미고 버튼을 아이콘처럼 표현

2. 왼쪽하단에 전원 아이콘을 만들어 해당 아이콘을 누르면 게임화면으로 이동

3. 주식시장 및 암호화폐시장을 제외한 아이콘을 누르면

   개발중이라는 팝업메시지를 띄움.

4. 주식시장 및 암호화폐시장 아이콘을 누르면 팝업 화면이 나오고

   주식, 암호화폐 두개의 아이콘이 새로 나옴.

5. 각 해당 버튼을 누르면 Scene이 넘어감 

6. 실제 거래시장화면을 참고하여 UI를 만든다.

7. 각 종목에 랜덤값을 주어 사고 파는 상황을 알 수 있게 한다.

8. 각 상황에 맞게 실제 시간 10초마다 그래프가 변동이 된다.


### 작업 결과
1. 실제 컴퓨터 바탕화면처럼 꾸미고 버튼을 아이콘처럼 표현 (100%)

2. 왼쪽하단에 전원 아이콘을 만들어 해당 아이콘을 누르면 게임화면으로 이동(100%)

3. 주식시장 및 암호화폐시장을 제외한 아이콘을 누르면

   개발중이라는 팝업메시지를 띄움.(100%)

4. 주식시장 및 암호화폐시장 아이콘을 누르면 팝업 화면이 나오고

   주식, 암호화폐 두개의 아이콘이 새로 나옴.(100%)

5. 각 해당 버튼을 누르면 Scene이 넘어감 (100%)

6. 실제 거래시장화면을 참고하여 UI를 만든다. (100%)

7. 각 종목에 랜덤값을 주어 사고 파는 상황을 알 수 있게 한다.(20%)

-> 랜덤값을 주는 것 까지 성공하였으나 각 상황을 알 수 있는 UI를 구현하지 못함

8. 각 상황에 맞게 실제 시간 10초마다 그래프가 변동이 된다.(70%)

-> 10초 주기로 가격이 오르내리는 것, 그래프를 그렸으나 두개의 스크립트를 연동 및 UI구현하지 못함

### 결과동영상
<video width="100%" height="100%" controls="controls">
  <source src="./img/3Week.mp4" type="video/mp4"></video>



## d. 4주차
### 구현 목표
작업명 : 그래프, 가격변동 알고리즘 연동

해당 요구사항 : 

3-2)주식시장화면에서는 총 3개의 회사가 상장되어있으며 각 회사마다 1주의 가격이 다르다.
3-1)우측 하단에는 게임 내 시간을 알려주는 시계가 있다.
작업 내용 : 

1.이전 주차에 하지 못한 그래프, 가격변동 알고리즘 연동
2.프로토타입에 맞는 3개 주식 상장
3.게임 내 시간 구현, 게임에서 거래되는 돈 모든 씬에서 연동시키기
### 작업 결과

1.이전 주차에 하지 못한 그래프, 가격변동 알고리즘 연동(100%)

~~2.프로토타입에 맞는 3개 주식 상장~~
      ->6주차로 계획 변경
      
3.게임 내 시간 구현, 게임에서 거래되는 돈 모든 씬에서 연동시키기(100%)

### 결과동영상
<video width="100%" height="100%" controls="controls">
  <source src="./img/4Week.mp4" type="video/mp4"></video>



## e. 5주차
### 구현 목표

작업명: 거래시장에서 거래하기

해당 요구사항 : 

3-3)주식 시장은 하루 최대 변동률이 +-30%이다.

3-6)주식은 오전 9시부터 오후 3시까지 마음대로 투자를 변동 할 수 있으나 오후 3시 이후에는 주식 거래시장에서 거래를 할 수 없다.

3-7) 암호화폐 시장은 시간 제한 없이 거래 할 수 있다.

3-5) 암호화폐 시장은 하루 가격 변동의 제한이 없다.

3-8) 주식 거래시장 종료 이후에는 가격 변동이 없으며 매수와 매도를 하지 못한다.

작업 내용 : 

1.플레이어가 소지한 돈을 이용하여 투자를 할 수 있게 구현

2.하루 최대 변동률 구현

3.주식 거래시장이 열려있을 때만 주식을 매수와 매도가 가능하도록 구현

4.주식 거래시장이 닫히면 그래프가 정지하도록 구현

### 작업 결과

1.플레이어가 소지한 돈을 이용하여 투자를 할 수 있게 구현(100%)

2.하루 최대 변동률 구현(100%)

3.주식 거래시장이 열려있을 때만 주식을 매수와 매도가 가능하도록 구현(100%)

4.주식 거래시장이 닫히면 그래프가 정지하도록 구현(100%)

### 결과동영상
<video width="100%" height="100%" controls="controls">
  <source src="./img/5Week.mp4" type="video/mp4"></video>



## f. 6주차
### 구현 목표

작업명: 마무리 작업
요구사항:

3-2) 주식시장화면에서는 총 3개의 회사가 상장되어있으며 각 회사마다 1주의 가격이 다르다.

3-4) 주식 시장과 동일하게 3개의 암호화폐가 상장 되어있다.

작업내용:

1.3개의 주식회사 상장

2.3개의 암호화폐 상장

3.게임 내 요소들을 알려 줄 수 있는 기능 만들기

4.디버깅 후 버그 찾아서 고치기

### 작업 결과

1.3개의 주식회사 상장(100%)

2.3개의 암호화폐 상장(100%)

3.게임 내 요소들을 알려 줄 수 있는 기능 만들기 (0%)
-> 튜토리얼을 추후 추가 예정 프로토타입 게임 설명은 PPT로 서술

4.디버깅 후 버그 찾아서 고치기(50%)
-> 찾긴했으나 시간부족및 기술부족으로 인해 고치진 못함

추가 작업

5.22시이후 에만 침대오브젝트가 활성화

6.22시이후 침대 오브젝트를 누르면 화면이 페이드아웃 되었다 페이드 인되며 시간이 8시로 이동

### 결과동영상
<video width="100%" height="100%" controls="controls">
  <source src="./img/6Week.mp4" type="video/mp4"></video>


