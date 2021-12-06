# 2021-2-OSSProj-Lets_Kirin-8
![Github license](https://img.shields.io/github/license/CSID-DGU/2021-2-OSSProj-Lets_Kirin-8)
![badges](https://img.shields.io/badge/OS-ubuntu-red)
![badges](https://img.shields.io/badge/IDE-VSCode-informational)
![badges](https://img.shields.io/badge/python-3.8-blue)
![badges](https://img.shields.io/badge/pygame-2.0.2-yellow)

Shooting Game based on pygame   

#### **[8조 렛츠기린]** 
**Team Leader** : 동국대학교 전자전기공학부 [정태호](https://github.com/Taeho25)   
**Team Member** : 동국대학교 산업시스템공학과 [문지윤](https://github.com/MoonJiyoon)   
**Team Member** : 동국대학교 산업시스템공학과 [하지수](https://github.com/zisooh)    

![kirin](https://user-images.githubusercontent.com/84272893/144908804-c15fee78-2bba-498f-994a-776e28aa0e89.png)
![kirin_helper](https://user-images.githubusercontent.com/84272893/144908908-dd80ce02-4c48-4fec-a617-4f51d236bf6c.png)

## How To Run
1. python, pygame, pymysql 설치
```
sudo apt-get update
sudo apt install python3.8
pip3 install pygame==2.0.2
pip3 install pymysql
```
2. 저장소 클론 및 실행
```
git clone https://github.com/CSID-DGU/2021-2-OSSProj-Lets_Kirin-8.git
cd 2021-2-OSSProj-Lets_Kirin-8
python3 Lets-kirin.py
```

## Game Controls
![image](https://user-images.githubusercontent.com/84272893/144609693-fbf4915c-3b3a-431d-a413-4f08bfaeb560.png)   

## Menu 
### 1. 로그인 / 회원가입   
![init_page](https://user-images.githubusercontent.com/84272893/144904048-17c387f7-f323-46a0-8a96-3751c8e7ae85.jpg)
  - 게임 'Let's Kirin'의 첫화면입니다.
  - 메뉴 조작키는 UP/DOWN 방향키와 Enter입니다. 
  - RDS 데이터베이스 구축 후 유저 정보를 저장하였습니다. 
  - 패스워드는 해시/솔트를 통해 암호화 후 안전하게 저장됩니다. 

### 2. 메인 메뉴
![inMenu_page](https://user-images.githubusercontent.com/84272893/144905083-22149c3c-7eef-4536-9a09-e172f16be196.jpg)
  - 메뉴 조작키는 1번 메뉴와 동일합니다. 
  - 좌측은 로그인 또는 회원가입 후 만날 수 있는 메인 메뉴 화면입니다.
  - 중간은 Select Mode 화면입니다.
  - 우측은 single mode의 high score 화면입니다. 유저들의 점수 기록을 확인할 수 있습니다. 
<img width="370" alt="1" src="https://user-images.githubusercontent.com/84272893/144746500-9ff2267c-089e-4c40-bfbb-dd584697b709.png"> <img width="370" alt="2" src="https://user-images.githubusercontent.com/84272893/144746520-c7953954-ae90-474b-af5f-33f9652426bd.png">   
  - Help 화면입니다. 싱글/타임 모드 조작법과 게임의 간단한 설명을 제공합니다.
  
## In Game
### 불량 곰 (장애물)
![bear_panda](https://user-images.githubusercontent.com/84272893/144909059-1cc9036e-752a-4f41-8c74-f2afad46e88b.png)
![bear_sunglasses](https://user-images.githubusercontent.com/84272893/144909062-cc1c9a83-9d2a-45e8-91a5-002081dc7a05.png)
![bear_brown](https://user-images.githubusercontent.com/84272893/144909067-450251ed-997a-4cb9-9b9c-0c87e7756eea.png)
![bear_green](https://user-images.githubusercontent.com/84272893/144909069-06a01513-7402-4166-8f30-9cb8d99eb020.png)
![stone](https://user-images.githubusercontent.com/84272893/144909135-310e1594-222d-4eec-bb28-1fa94ddd7238.png)
### 아이템
![item_helper](https://user-images.githubusercontent.com/84272893/144909245-ced402bb-fa72-45cc-8aa8-e8d2e48fe7d9.png)
![kirin_helper](https://user-images.githubusercontent.com/84272893/144909249-bdd11a9a-9bed-4978-914b-b1707473f0c0.png)
![item_peep](https://user-images.githubusercontent.com/84272893/144909425-462c8002-57e9-4a07-bc9a-b66b3c7e4761.png)
![kirin_peep](https://user-images.githubusercontent.com/84272893/144909430-0a0dd934-2205-467c-bc46-cfae1e11434f.png) 
![item_shield](https://user-images.githubusercontent.com/84272893/144909479-7a96dd59-a88b-40f1-bf29-a02e1ef91850.png)
![kirin_shield](https://user-images.githubusercontent.com/84272893/144909480-4d7250ff-91db-45fb-9901-1a9b7d5b64c7.png)
![heart2](https://user-images.githubusercontent.com/84272893/144909525-562793f7-4cd9-4e40-8b37-473b83e9a0e1.png)
![heart3](https://user-images.githubusercontent.com/84272893/144909528-341d3277-2f29-4fad-abf9-1e005790c3e8.png)
![item_heart](https://user-images.githubusercontent.com/84272893/144909529-e6c02a64-b773-4a0d-9d16-d2b783772a7c.png)
![item_double](https://user-images.githubusercontent.com/84272893/144909701-9b24ab60-27bb-4b80-aad2-f8718a2f4465.png)




### 1. Single Mode  
  - 렛츠기린 게임의 베이스가 되는 게임입니다.   
  - ***이미지 추가예정***



### 2. Time Mode
  - 제한시간 30초 동안 획득한 점수로 순위를 매기는 타임리미티드 모드입니다.  
  - 기존 싱글모드에 비해 난이도를 상향 조정하여 시작하도록 설정하였습니다.   
  - 기존 싱글모드에 비해 아이템 출현 횟수를 높게 설정하였습니다.   
  - 제한시간내에 죽으면 점수 기록은 되지않습니다.   
  
### 3. PVP Mode
  - 오래 살아남는 플레이어가 승리하는 PVP 모드입니다.
  - 화면 분할에 따른 객체의 이동 범위 제한하였습니다.
  - 객체별 아이템, 목숨, 스코어 등을 분리하여 적용하였습니다.

## Credits
* Music: https://pixabay.com/ko/music/search/genre/%EB%B9%84%EB%94%94%EC%98%A4%20%EA%B2%8C%EC%9E%84/
* Sound FX: https://github.com/jpritcha3-14/shooting-game.git   

## Reference
* Origin Source : https://github.com/jpritcha3-14/shooting-game.git   
* login/Singup Source: https://github.com/CSID-DGU/2021-1-OSSPC-Tongsan1-2.git
