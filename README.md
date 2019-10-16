# Create-Android-Application
## 어플리케이션 만들기
<img width="500" height="300" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/1.PNG"/>
●First press Create.
<br>
먼저 새로 생성하기를 눌러줍니다.
<hr><br>
<img width="500" height="300" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/2.PNG"/>
●Then we will create an empty activity to make it for practice.
<br>
그다음 연습용으로 만들기 위해서 빈 엑티비티를 만들겟습니다
<hr><br>
<img width="500" height="300" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/3.PNG"/>
●Then enter the name of the application and the Internet domain name,<br> specify the location of the folder where the project will be created and click Done.
<br>
그다음 어플리케이션의 이름과 인터넷 도메인 이름을 입력하고 <br> 프로젝트가 생성되는 폴더의 위치를 지정하고 완료를 눌러줍니다
<hr><br>
<img width="500" height="300" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/9.PNG"/>
●After a certain time, the following screen appears,<br>
installing the uninstalled build tool, compilation will proceed.
<br>
일정 시간이 지나면 다음과 같은 화면이 뜨는데, 미설치된 빌드 도구를 설치하고나면 컴파일이 진행됩니다.
<hr><br>
<img width="200" height="350" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/9.jpg"/>
●Run the application on your phone and it will look like this
<br>
어플리케이션을 휴대폰에 실행시키면 다음과 같이 나옵니다.
<hr><br>
<img width="200" height="350" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/12.jpg"/>
●The application is created in the phone menu.
<br>
그리고 휴대폰 메뉴에 어플리케이션이 생성됩니다.
<hr><br>
<img width="200" height="100" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/4.PNG"/>
●If you want to change the icon image,<br>Paste the image file you want to change into the drawable folder of the registry.
<br>
만약 아이콘 이미지를 바꾸고 싶을땐 , <br>레지스트리의 drawable 폴더에 바꾸고싶은 이미지 파일을 붙여넣기로 옮겨준다음에
<hr><br>
<img width="500" height="300" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/7.PNG"/>
●Open the AndroidManifest.xml file in your app's manifests folder,( android: icon = "@ drawable / ) will change the image file name.
<br>
앱의 manifests 폴더안 AndroidManifest.xml 파일을 열어( android:icon="@drawable/ ) 부분에 이미지 파일명을 적어주면 바뀝니다.
<img width="200" height="350" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/10.jpg"/>
<hr><br>
<img width="500" height="300" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/5.PNG"/>

●If you want to change the name of the application, you can change the name in the label part.And if you want to remove the title part of the app launch screen,<br>
Ctrl + click on (style / AppTheme) in (android: theme = "@ style / AppTheme") and you'll see (styles.xml).
 &lt;item name = "windowNoTitle"> true &lt;/ item>  will remove the title.
<br>
또한 어플리케이션의 이름을 바꾸고 싶을땐 label 부분에 이름을 바꿔주시면 됩니다. 그리고 앱 실행 화면의 타이틀 부분을 없애고 싶을땐,( android:theme="@style/AppTheme" )에 ( style/AppTheme ) 부분을 Ctrl 버튼을 누른채로 클릭을 해주면( styles.xml )이 뜨는데, &lt; item name="windowNoTitle">true &lt;/item> 를 넣어주시면 타이틀이 제거 됩니다.

<img width="210" height="100" src="https://github.com/Bono-kim/Create-Android-Application/blob/master/11.jpg"/>
●The title has been removed.
<br>타이틀이 제거되었습니다.
