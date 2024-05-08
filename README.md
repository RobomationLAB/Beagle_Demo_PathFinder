# Path Finder

Path Finder는 Beagle 로봇의 체험형 데모 프로그램입니다.

![비글배경](https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/c43bef77-3f7d-4ea6-b028-5d082e06cfc6)

방향키 주행, 중심찾기, 방탈출, 미로찾기 모드가 있습니다.
<br>
아래 버튼을 눌러 실행 프로그램을 다운로드 받아 LiDar 센서를 직접 체험해보세요.

<br>

[PathFinder 설치하기](https://www.dropbox.com/scl/fo/aj5fmw9atbca62bo5fmyl/ALpFXy2laXgSvHFpTqhlGx8?rlkey=zh7ppr8qjcxn8riirmvxjzqsg&e=1&st=gdm2699v&dl=0)




*( ※ PATHFINDER.exe는* **windows** *전용 프로그램입니다. )*

<details>

<summary>설치방법</summary>

위 링크로 들어가, 다음과 같이 **로그인하지 않은 상태**로 다운로드를 진행할 수 있습니다.<br>
[ 다운로드 ] → [ 또는 다운로드만 하고 계속 진행하세요. ] 순으로 클릭합니다.

<img src='https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/bd19bcc5-2aaa-44e3-8cf2-65e22c0e432e' width=600>

<br><br>

브라우저 우측 상단에 다운로드 버튼을 눌러 설치된 zip파일을 선택하고, 설치된 zip파일을 원하는 위치에 압축을 해제합니다.

<img src='https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/d930da99-5aaa-497b-9e90-723a0ff01c1b' width=600>


---


</details>

<br><br>

---

**PATHFINDER 실행파일을 시작하기 전에 로봇과 [PC를 연결](#pc-연결)하고 실행파일을 시작해 주시기 바랍니다.**


<img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/d95c7017-3ce1-4d6d-b632-a69e0909af3d" alt="대체 텍스트" width=500>

---



*※해당 프로그램은 로보메이션의 제품을 활용해 대학생들이 개발하여 체험용으로 배포한 프로그램입니다.
<br>
따라서 <u>본 프로그램의 사용법이나 오류에 대한 문의는 받고 있지 않습니다.</u>*

---

<br><br><br><br>

 
# PC 연결

Beagle의 전원이 꺼져 있는 상태에서 **EXPRESS RECEIVER**를 PC의 USB단자에 꽂습니다.
<br>
**EXPRESS RECEIVER**의 연결 상태 표시등이 초록색으로 깜빡이면 연결 대기중인 상태로 정상입니다.



<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/e6f30006-f092-4e51-af49-13063e7f1f77" alt="대체 텍스트" width=500>

<br><br>

Beagle로봇을 EXPRESS RECEIVER에 가까이 가져가 Beagle의 **전원 버튼**을 눌러 전원을 켭니다.
<br>
Beagle에서 **삑** 소리가 나고 **Beagle의 통신 상태 표시등**과 **EXPRESS RECEIVER의 연결상태 표시등**이 계속 켜져있거나 빠르게 깜빡이면 정상입니다.

<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/d013081b-4ba2-492f-a9ba-0a2ff76b02b6" width=350>


---



<br><br>



# Path Finder 시작하기

- 우측 상단의 **CONNECT** 버튼을 클릭하여 연결을 시도합니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/c8dcead2-e0cf-43f3-a472-b14203a83295" width = 600>


<br><br>

- 연결에 **성공**했다면 왼쪽 사진과 같이 초록 불이 들어오고, 
  
- 연결에 **실패**했다면 초록 불이 들어오지 않습니다. 이때,  **Beagle의 전원**이 켜져 있는지 확인해봅니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/5b37fad9-b6ea-41bb-9034-8608699ce491" width = 1200> 



<br><br>

- 우측 상단의 **DISCONNECT** 버튼을 눌러서 Beagle과의 연결을 해제할 수 있습니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/1d46de72-bb80-43ec-813f-0878fa018f82" width = 600>

<br><br>




- Beagle이 연결된 상태에서 프로그램을 실행하면 아래와 같이 프로그램 창이 나타납니다.
    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/ab7a8827-3c13-4208-8598-8844ef112777" width = 700>

<br><br>



### 무한반복 모드란?
- 중심 찾기와 미로찾기에 있는 모드입니다.
- **무한 반복 모드**를 클릭하여 활성화하고, **PLAY** 버튼을 누르면, 비글이 **무작위 위치**로 이동한 뒤 중심을 찾아갑니다. 이 과정을 무한히 반복합니다.
- **미로찾기**의 경우, 끝과 끝을 무한히 왕복합니다.
- **무한 반복 모드**는 계속해서 동작이 반복되므로 중지하기 위해서는 **＇STOP＇** 버튼을 클릭합니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/c377f660-394e-4bef-99ab-5c4e2ac2f2ae" width = 600>

<br><br>

### LiDar 뷰어 모드란?

**LiDar 뷰어 모드**에는 **두가지 모드**가 있습니다.


| 모드 | 설명 |
| --- | --- |
| Auto Scaling | [ 자동모드 ] LiDAR 센서가 수집한 데이터 중에서 가장 먼 거리의 정보를 기준으로 뷰어의 스케일을 자동으로 조정하여 시각적으로 나타내는 모드입니다. (뷰어의 수동조작 불가)|
| Mouse WheelScroll | [ 수동모드 ] 좌클릭 상태로 마우스를 움직여 화면상 Beagle의 위치를 자유롭게 이동시킬 수 있습니다. 휠 스크롤을 사용하여 화면 비율을 확대 또는 축소할 수 있습니다. |


<br><br>






# 방향키 주행

- PC와 Beagle이 연결되어 있는 상태에서 방향키 주행을 선택합니다.
    <img src='https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/dfd614c2-8881-4487-bdc3-e7cac3356a71' width=600>


<br><br>

- 하단 **PLAY** 버튼을 누르면 다음과 같이 LiDar센서가 활성화되고, 키보드로 Beagle을 제어할 수 있는 상태가 됩니다. 


    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/47620aa0-58f8-4e5e-9a9e-97eb9392c47f" width = 1200>




<br><br>

| 입력 | 설명 |
| --- | --- |
| `↑` | 전진 |
| `↓` | 후진 |
| `←` | 제자리에서 왼쪽으로 회전 |
| `→` | 제자리에서 오른쪽으로 회전 |
| `↑` + `←` | 좌회전 |
| `↑` + `→` | 우회전 |
| `↓` + `←` | 왼쪽으로 후진 ( `↓`, `←` 순으로 입력 권장) |
| `↓` + `→` | 오른쪽으로 후진 ( `↓`, `→` 순으로 입력 권장) |


<br><br>

- **STOP** 버튼을 누르면 키보드와 LiDar센서가 비활성화 됩니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/3e52bcb9-ba8f-458c-9d2b-693da11f32a6" width = 600>




<br><br>




# 중심 찾기

### 준비

- Beagle을 미로판 안 원하는 위치에 내려놓으면 중앙을 찾아가는 프로그램입니다.

- Beagle과 [PC연결](#pc-연결)이 되어있는 상태에서 진행하도록 합니다.

- 중심 찾기를 위해 <u>Beagle용 미로판</u>인 **AI DRIVING TRACK**을 사용하여 3×3이나 3×4 크기의 방을 만들어 줍니다.<br>*벽의 높이는 3층으로 쌓기를 권장합니다.*



    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/1b17c2e2-6d32-4eb4-b9a0-df2486e645c2" height="200">



<br><br>


### 중심찾기 준비


- 프로그램에서 다른 모드가 실행중이라면, 종료하고 중심찾기 모드를 선택합니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/d2796560-b44a-4a91-93ad-7f6f68acef68" width = 600>


<br><br>


### 중심찾기 시작




- **PLAY** 버튼을 누르면 Beagle의 LiDar가 활성화 되고 Beagle이 자동으로 중심을 찾아 이동하는 프로그램이 실행됩니다.

- 중심을 찾는 데 성공했다면 중심 찾기가 자동으로 종료됩니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/d858c8db-beda-4098-9a53-97bce1249642" width = 600>








<br><br><br><br>











# 방탈출

### 준비

- Beagle을 미로벽 안 원하는 위치에 내려놓으면 출구를 찾는 프로그램입니다.

- Beagle과 [PC연결](#pc-연결)이 되어 있는 상태에서 진행하도록 합니다.

- 방탈출을 위해 <u>Beagle용 미로판</u>인 **AI DRIVING TRACK**을 사용하여 3×4 크기의 맵을 만들어 줍니다.<br>*벽의 높이는 3층으로 쌓기를 권장합니다.*



    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/c1f39eaa-27e7-4e67-9bad-38914771a1be" height="200">


<br><br>


### 방탈출 준비



- 프로그램에서 다른 모드가 실행중이라면, 종료하고 방탈출 모드를 선택합니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/3c063ddd-d56d-4498-8b70-1d865faa7b62" width = 600>


<br><br>


### 방탈출 시작




- **PLAY** 버튼을 누르면 Beagle의 LiDar가 활성화 되고 Beagle이 방탈출하는 프로그램이 실행됩니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/4a588d4b-74ab-42a8-94ca-23dbbfbfe06d" width = 600>


<br><br>

- Beagle이 어떤 방식으로 탈출구를 찾아가는지 생각해 봅니다. 
- 출구를 찾는 데 성공했다면 방탈출이 자동으로 종료됩니다.


    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/da4355b7-7023-429a-a525-2bba78396e3f" width = 1200>






<br><br><br><br>



# 미로찾기

### 준비

- Beagle을 미로판 한 쪽 끝에 내려놓으면 미로를 따라 이동하는 프로그램입니다.

- Beagle과 [PC연결](#pc-연결)이 되어있는 상태에서 진행하도록 합니다.

- 미로찾기를 위해 <u>Beagle용 미로판</u>인 **AI DRIVING TRACK**을 사용하여 아래와 같은 맵을 만들어 줍니다.<br>*벽의 높이는 3층으로 쌓기를 권장합니다.*



    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/f4cc02cb-a92b-437f-8982-26ace86a7f42" alt="대체 텍스트" height="200">


<br><br>


### 미로찾기 준비


- 프로그램에서 다른 모드가 실행중이라면, **종료**하고 미로찾기 모드를 선택합니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/96ce04db-aa7c-42ad-8540-743334ee08b1" width = 600>


<br><br>

### 미로찾기 시작

- **PLAY** 버튼을 누르면 Beagle의 LiDar가 활성화 되고 미로찾기 프로그램이 실행됩니다.


    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/bc642a70-6e24-4eb1-971f-a9c664b6b9e0" width = 600>


<br><br>

- Beagle이 어떤 방식으로 미로를 해결해 나아가는지 생각해 봅니다.
- 성공하면 미로찾기가 자동으로 종료됩니다.

    <img src="https://github.com/tjdtnxx/Personal_tjdtn/assets/160319639/d681d4e4-df65-4850-9201-942b5e15ad55" width = 600>








<br><br><br><br>
