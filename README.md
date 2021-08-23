# 2021_smarcle_makers_day
세종대 스마클 메이커스 데이(6조) 

smarcle makers day란?          
------------------------------------------------                        
smarcle makers day는 세종대 지능기전공학부 동아리인 [Smarcle](https://github.com/sejongsmarcle, "smarcle link")에서                  
2021 여름방학동안 진행한 메인 프로그램으로 아두이노, 인공지능 등 다양한 소프트웨어, 하드웨어를 융합하여             
하나의 큰 작품을 만드는 활동입니다. 

6조 프로젝트 시동
-----------------------------------------------
저는 smarcle makers day 6조로 포함되어 프로젝트를 진행했습니다. 저희 조는 지난 2017년 10월 20일 서울 신길역에서 휠체어 리프트를 이용하려던 故 한경덕 씨가 계단 밑으로 추락하는 사고를 뉴스로 보았습니다. 사고 영상을 보면 휠체어 리프트를 조작하는 한경덕 씨가 리프트를 조작하려 몸을 힘겹게 뻗다가 추락하는 모습을 볼 수 있습니다. 그래서 장애인들이 휠체어를 쉽게 사용할 수 있도록 리프트를 개선시켜야 할 필요가 있다고 생각했습니다. 
                                       
![캡처3](https://user-images.githubusercontent.com/81175672/130349801-cd29a05d-f4c4-4dfb-95fd-83d6f212c3fc.JPG)                            

블루투스 조작이 가능한 휠체어 리프트 모형, 앱 구현
--------------------------------------------
저희 조는 블루투스로 조작할 수 있는 휠체어 리프트로 기존의 리프트를 개선시키로 했습니다.                  
아두이노, HC-06, 기어드 모터를 이용해 회로를 만들고 앱 인벤터를 사용하여 리프트 조작 앱을 만들었습니다.                    
아두이노는 arduino IDE을 사용하여 코딩했습니다.

<img src = "https://user-images.githubusercontent.com/81175672/130350063-79ad78b3-b0bb-43f8-a260-92c57e709300.jpg" width="40%" height="40%">     <회로 프로토타입 모습>                
<img src ="https://user-images.githubusercontent.com/81175672/130350128-f1015db5-0223-44e0-8633-81e7aa73a8cb.png" width="40%" height="40%">
<리프트 조작 앱 모습>

[아두이노 소스 코드](https://github.com/RyuJungSoo/2021_smarcle_makers_day/blob/main/source_code/arduino.md, "project link") 
[자세한 앱 소스 코드는 여기를 참조1](https://blog.naver.com/goldfox10/222433130562, "project link")                        
[자세한 앱 소스 코드는 여기를 참조2](https://blog.naver.com/goldfox10/222450059705, "project link")                       


리프트 상승 시스템 구현
-------------------------------------
원래는 체인과 톱니를 이용하여 상승 시스템을 구현하려고 했으나 체인, 톱니, 축 무게를 고려했을 때 모터의 토크가 부족할 거 같아 다른 방식을 생각하기로 했습니다.                             
<img src="https://user-images.githubusercontent.com/81175672/130412164-d85d91c3-9d35-424b-86ba-f81a5dd4e4a8.jpg" width="40%" height="40%">                 
그래서 저희 조는 볼트와 너트를 이용하여 회전 직선 운동이 가능한 구조를 만들기로 했습니다. 너트를 볼트에 낀 상태로 너트를 돌리면 위 아래로 움직이는 것을 이용해          
너트가 회전하는 걸 막을 수 있는 지지대를 설치하면 볼트만 회전하면서 너트가 상승하는 시스템이 구현될 것이라고 저희 조는 생각했습니다.                 
<img src="https://user-images.githubusercontent.com/81175672/130414000-1798a397-24e4-4f81-b7d5-4659db8920f5.JPG" width="40%" height="40%">               
<완성한 볼트, 너트, 너트 회전 방지대, 지지대>             
[볼트+너트+지지대 3d 모델](https://github.com/RyuJungSoo/2021_smarcle_makers_day/tree/main/3d_model/bolt%2Bnut, "project link")

휠체어 3d 디자인
---------------------------------------
리프트 모형에 태울 소형 휠체어를 123d design을 사용하여 디자인 했습니다.                    
<img src="https://user-images.githubusercontent.com/81175672/130421272-74d4ed4f-88d2-4074-8ebb-d15bab9f052e.jpg" width="40%" height="40%">  
[휠체어 3d 모델](https://github.com/RyuJungSoo/2021_smarcle_makers_day/tree/main/3d_model/wheelchair, "project link")                     


 
작동 시연 영상
--------------------------------------
[![Video Label](https://www.youtube.com/watch?v=1j32gT3AuWs/0.jpg)](https://www.youtube.com/watch?v=1j32gT3AuWs)

마무리하면서...............
-------------------------------
저희 조는 약 2달 간의 활동을 하면서 사회적 약자를 위한 기술에 대해서 생각해보고 고민해보는 시간을 가졌습니다.                 
사회적 약자나 실생활의 불편을 없애주는 점이 기술의 장점 중에 장점이라고 저희 팀은 생각합니다. 앞으로 이런 기술들이 많이 개발되고 공유되는 것이 저희 팀의 바람입니다.


[프로젝트 소개 사이트](https://sites.google.com/view/smarclemakersdayteam6finalpres/%ED%99%88, "project link")
