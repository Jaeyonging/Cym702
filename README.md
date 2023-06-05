
# <b> Cym702 (출시)</b>
https://play.google.com/store/apps/details?id=com.yellosis.app&hl=en-KR

해당 코드는 회사소유로 올리지 못합니다. 
따라서 구조를 올리겠습니다. 

<h2 id="0">
    <b>💁 Team  introduce </b>
    
</h2>

| Part                 | Name                                                |
| -------------------- | --------------------------------------------------- |
| **Android Developer** | <a href="https://github.com/Jaeyonging">최재용 </a>   |
| **Back-end**         | <b>1명<b>     |
| **Font-end**         | <b>1명<b>     |



<hr>

<h2 id="0.5">
    <b>💡 Topic</b>
</h2>

#### 건강을 간단하게 체크 하고 싶을때, 병원을 예약하고 시간을 내어 방문하기가 쉽지 않을 때, Cym702(심702)는 소변을 이용한 간단한 검사를 통해, 일상 속에서 누구나 건강을 쉽게 관리할 수 있도록 도와주는 AI 건강관리 솔루션 이다. 

- AI 건강관리 솔루션

<hr>
<h2 id="0.5">
    <b>⭐️  My Task</b>
</h2>

- 알람 서비스
    - 사용자가 설정한 시간에 맞게 알람이 울리게끔 구현함 (반복주기 1~2분 차이 있음)
- 블루투스 기능
    - 블루투스 기기와 통신하여 연결하고 명령어를 보내 데이터를 가져옴
- 검사지 촬영
    - 사용자가 카메라 (camerX)를 이용하여 검사지를 촬영할 수 있도록 구현함
- 뒤로가기 기능
    - 사용자가 뒤로가기 버튼을 두 번 누를시 앱이 종료되게 구현함
- 프로그레스 바 기능
    - 검사 촬영 후 사진 전송시, 사용자에게 프로그레스 바를 통해 얼마나 남았는지 보여줌
<hr>


<h2 id="2">🛠 Tech Stack</h2>

`Kotlin`, `JetPack`, `DataBinding`, `ViewModel`, `SharedPreference`, `BridgeFunction`,

`SplashImage`, `CameraX`, `Retrofit2`, `LiveData`, `GoogleLogin`, `AlarmService`

`BluetoothService`, `SharedPreference`, `ProgressBar`

 ### ⚙️ Architecture

`MVVM`
<hr>
  
<h2 id="0.5">
    <b>🤔 Learned</b>
</h2>

- `BluetoothService` 을 처음 구현해봤으며 블루투스 기기와 통신하는 방법을 알게 됐음.
- `AlarmService` 을 이용하여 반복주기 함수(setRepeating)을 쓰면 정확한 시간에 오지 않아 setExactAndAllowWhileIdle를 사용하여 이를 고민하고 해결함.
- 핸드폰 재부팅시 `SharedPreference` 을 이용하여 알람 데이터를 보존함.
- `BridgeFunction` 을 이용하여 웹뷰와의 통신을 구현함.
- 사용자 입장을 생각해보며 블루투스 기기가 중간에 끊겼을 때`LiveData` 을 사용하여 이를 해결함.
- WIT Show 2023에 참가하였을 때 인터넷이 느려 서버로 보내는 시간이 오래 걸렸을 때를 생각해 사용자 입장을 생각해 `ProgressBar`를 사용하여 얼마나 남았는지 보여주는 기능을 구현함.
- 한국에서는 카메라 찍을 때 소리가 나야하지만 CameraX를 통해 사진을 촬영시 소리가 안나기 때문에 MediaSound로 사진 촬영 시 소리나게 구현함
- `GoogleLogin` 을 통해 사용자가 구글 로그인으로 로그인할 수 있도록 구현함.

<hr>

<h2 id="3">🏙 ScreenShot</h2>

<p float="left">  
<img width="40%" src="/image/Splash.jpg">
<img width="40%" src="/image/googleLogin.jpg">
</p>
  
<p float="left">  
<img width="40%" src="/image/main.jpg">
<img width="40%" src="/image/Screenshot_20230501-155300_Cym702.jpg">
</p>
  
<p float="left">  
<img width="40%" src="/image/Screenshot_20230501-192828_Cym702_developer.jpg">
<img width="40%" src="/image/Screenshot_20230501-192839_Cym702_developer.jpg">
</p>
  
<p float="left">  
<img width="40%" src="/image/Screenshot_20230501-163136_Cym702.jpg">
<img width="40%" src="/image/Screenshot_20230215-141943_Cym702 Developer.jpg">
</p>

  
<p float="left">  
<img width="40%" src="/image/1-9.jpg">
<img width="40%" src="/image/1-10.jpg">
</p>
  
 <p float="left">  
<img width="40%" src="/image/1-4.jpg">
<img width="40%" src="/image/1-5.jpg">
</p>
  
 <p float="left">  
<img width="40%" src="/image/1-6.jpg">
<img width="40%" src="/image/1-7.jpg">
</p>
  
 <p float="left">  
<img width="40%" src="/image/Screenshot_20230501-192844_Cym702_developer.jpg">
<img width="40%" src="/image/Screenshot_20230501-155352_Cym702.jpg">
</p>

