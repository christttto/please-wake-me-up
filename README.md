# please-wake-me-up
app that will finally make sure I woke up

4가지 개인 채널에 올리기 (To-be 시나리오, 5W1H, 요소연결, 그래서 뭐가 좋아졌는가?)
# As-is

> 또 늦잠을 자버렸다. 
알람을 몇개나 해뒀는데...
아니 7시에 분명히 일어났는데, 20분 미리 일어나려고 알람을 4개씩 해놨었는데...
괜히 스누즈 안하고 꺼버렸다.
망했다...
다시 알람을 하나만 쓸까...? 그러다 못들으면 어쩌지
> 

# 객관적인 요소정리

## WHO

- 나, 아침에 잘 일어나지 못하는 사람

## WHEN

- 아침

## WHERE

- 집

## WHY

- 제시간에 일어나기 위해서

## HOW

- 알람을 여러개 해둔다, 일찍 잔다, 알렉사, 스마트 커튼, 전화해달라하기

## WHAT

- 제시간에 일어나서 하루를 시작한다

# 주관적인 요소정리

## 문제/ 불편한 점

- 제대로 일어날거라는 확신이 없어서 알람이 많아진다
    - 어느 날은 여러 알람이 필요하지 않은데 울린다
- 다른 알람 시스템들은 침대에서 할수있거나 비생산적이다
    - 침대에서 쓸수있어서 잠들 위험이 있음
    - 의미없는 행동을 해야함

- //문제의 파편화

## 우선순위

- 확실히 일어나게하는 시스템이 필요하다
- 다음 행동 시작에 도움을 준다

# To-Be

> 내일은 7시 20분에 일어나야한다. 알람을 맞춰두고 유투브를 보다가 잠이 들었다.
아침 7시 20분, 알람이 울리는걸 들었다. 너무나도 고통스럽다. 일단 폰을 들고 화장실을 간다.
칫솔을 물고 양치를 하는 나를 폰으로 찍었고, 그제서야 내 알람의 off 버튼이 활성화 되었다.
알람소리가 너무 짜증나지만 어째뜬 내 아침은 7시 20분에 시작되었다.
> 

## 개선점

- 확실히 일어날거기 때문에 알람을 여러개 해둘필요가 없음
- 양치질 이라는 일어난 뒤에 해야할 행동으로 유도해준다

## 요소 연결
- 제대로 일어날거라는 확신이 없어서 알람이 많아진다
    - 확실히 일어날거기 때문에 알람을 여러개 해둘필요가 없음
- 다른 알람 시스템들은 침대에서 할수있거나 비생산적이다
    - 양치질 이라는 일어난 뒤에 해야할 행동으로 유도해준다


## 이후 할수있는 부분, 유의점

- 확산 가능부분
    - 개인이 원하는 액션
        - 인기패턴들을 공유할수있다면?
        - 다른 공기계를 이용한 오프 버튼의 분리 (화장실의 세컨폰으로만 알람을 끌수있다)
- image recognition (양치하는 사람, 혹은 그냥 화장실에 서있는 나를 인식해줌)
    - 이미지 인식 정확도
        - 기본사진을 여러장을 미리 업로드해둬서 이미지들을 비교해서 특정 퍼센트 이상의 매칭률을 가지면 알람이 활성화됨
- ios 알람 라이브러리
    - 시간값을 가져올수있어야함
    - 소리  엑세스
    - 앱이 꺼져도 계속 켜져있을수있어야함
        - 조금 어려울지도?