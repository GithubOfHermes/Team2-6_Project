# 보고서 제출:

## 2-6조_오픈소스SW의 이해 _깃헙프로젝트.pdf
### 내용:  
20205139 스마트IOT 김성열  

### 1) Project Introduction 👋🏻
간편하게 사용할 수 있는 타이머,스톱워치 구현  
사용자가 프로그램 실행 시 스톱워치와 타이머 두 가지 모드 중 하나를 선택할 수 있으며, 또한 이 프로그램은 CLI (Command Line Interface) 환경에서 작동하며, 각 모드에 따라 적절한 기능을 수행하는 프로그램입니다.

### Feature Responsible 👤
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/DriedSlime">
        <img src="https://avatars.githubusercontent.com/DriedSlime" width="50px;" alt="DriedSlime"/>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Hermes765">
        <img src="https://avatars.githubusercontent.com/Hermes765" width="50px;" alt="Hermes765"/>
      </a>
    </td>
	  <td align="center">
      <a href="https://github.com/sanchaehwa">
        <img src="https://avatars.githubusercontent.com/sanchaehwa" width="50px;" alt="sanchaehwa"/>
      </a>
    </td>
  </tr>
  <t>
    <td align="center">
      <b>심건우(Timer Feature)</b>
    </td>
	 <td align="center">
      <b>김성열(Stopwatch Feature)</b>
    </td>
    <td align="center">
      <b>양화영(Main Function)</b>
    </td>
   
  </tr>
</table>

### Project System Architecture 🧾
```
                             +---------------------------+
                             |   사용자 (User Interface)  |
                             +---------------------------+
                                          |
                                          v
                             +---------------------------+
                             |     모드 선택 (Main Menu) |
                             +---------------------------+
		                    |                |
		                    v                v
		        +------------------+   +-----------------+
		        |  스톱워치 모드   |   |   타이머 모드    |
		        | (Stopwatch Mode) |   | (Timer Mode)    |
		        +------------------+   +-----------------+
		                    |                   |
		                    v                   v
		        +------------------+   +-----------------+
		        |    시간 측정 및   |  |    시간 설정 및  |
		        |     표시 기능     |  |     카운트다운   |
		        +------------------+   +-----------------+
		                    |                   |
		                    v                   v
                                 +---------------------------+
                                 |    종료 및 초기화 기능     |
                                 +---------------------------+
```

### 2) Milestone  
![milestones](https://github.com/user-attachments/assets/2c3bec9e-6a62-47e2-b85a-f93e42f2a208)  

### 3) Open 상태인 Issue  
![open issue](https://github.com/user-attachments/assets/cc61fed7-6921-48e8-86f1-6458a9f4d700)  


### 4) Closed 상태인 Issue  
![close issue](https://github.com/user-attachments/assets/8a94d313-2fd6-43ca-9505-805cca01f183)  

### 5) 최종적 Project 보드  
![project board](https://github.com/user-attachments/assets/45c216d7-1bf7-4b3e-8c54-53944d98f4bd)  

### 6) Requirements.txt

### 7) PR 탭 화면 (open/closed 둘다 스크린샷)  
open  
![open PR](https://github.com/user-attachments/assets/acaa1184-e261-4aa4-a08f-b7a4601cd0d8)  
closed  
![close PR](https://github.com/user-attachments/assets/1ebbebba-4ad6-4f11-bc1b-e534f64b23ba)  

### 8) 실행 화면
![terminal](https://github.com/user-attachments/assets/6eb02bd4-072f-4b78-9d38-1ced9b9ceca5)




