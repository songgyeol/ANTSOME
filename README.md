# ANTSOME
22.07.20
KioskApp

2022.07.20(수) 업무 예정 사항

1. Kiosk 과제
- 상품 구매 및 완료 목록 구현

-ListView, Image URL, JSONObject

2.  로직 과제

- 로직 문제 풀기

[https://kumgo1d.tistory.com/6](https://kumgo1d.tistory.com/6)

[https://deumdroid.tistory.com/entry/안드로이드-스튜디오-리스트-뷰-ListView-사용하기](https://deumdroid.tistory.com/entry/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%8A%A4%ED%8A%9C%EB%94%94%EC%98%A4-%EB%A6%AC%EC%8A%A4%ED%8A%B8-%EB%B7%B0-ListView-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)

**ListView** = [https://itstudy-mary.tistory.com/207](https://itstudy-mary.tistory.com/207)

[https://blog.naver.com/hke3255/222313680264](https://blog.naver.com/hke3255/222313680264)

[https://webnautes.tistory.com/1190](https://webnautes.tistory.com/1190)

[https://bbaktaeho-95.tistory.com/66](https://bbaktaeho-95.tistory.com/66)

[https://lktprogrammer.tistory.com/163](https://lktprogrammer.tistory.com/163)

![스크린샷 2022-07-20 오후 11.32.19.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/07c2e96c-2f2f-4bb2-8b25-b6afeac0ab97/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-07-20_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.32.19.png)

XML파일 만들기 = [https://myyamyam001.tistory.com/11](https://myyamyam001.tistory.com/11)

Json = [https://itstudy-mary.tistory.com/88?category=902777](https://itstudy-mary.tistory.com/88?category=902777)

tools:context = [https://dreamaz.tistory.com/229](https://dreamaz.tistory.com/229)

```java

xml
<LinearLayout
        android:id="@+id/linearLayout3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent">

        <TextView
            android:id="@+id/poster"
            android:text="과자"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:layout_weight="1"
            android:scaleType="fitXY"
            tools:srcCompat="@tools:sample/backgrounds/scenic[2]" />

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical"
            >

            <TextView
                android:id="@+id/movieName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="가격" />

            <TextView
                android:id="@+id/grade"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="20dp"
                android:text="수량" />
        </LinearLayout>
    </LinearLayout>
```

로직 = [https://semicolon-dev.tistory.com/46](https://semicolon-dev.tistory.com/46)

swift로직 = [https://greendreamtrre.tistory.com/46](https://greendreamtrre.tistory.com/46)

**리스트** = **contentVIew 개념**

객체지향프로그래밍 = [https://www.youtube.com/watch?v=vrhIxBWSJ04](https://www.youtube.com/watch?v=vrhIxBWSJ04)

**JSONObject{}다루기, JSONString, JSONArray{[]}** = [https://blog.naver.com/PostView.naver?blogId=jang0_0yw&logNo=222448275383&categoryNo=25&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView](https://blog.naver.com/PostView.naver?blogId=jang0_0yw&logNo=222448275383&categoryNo=25&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView),

[https://stickode.tistory.com/75](https://stickode.tistory.com/75), [https://codechacha.com/ko/java-convert-object-to-json-and-write-to-file/](https://codechacha.com/ko/java-convert-object-to-json-and-write-to-file/)
**MAP이랑 같은 개념**
**JSON 확장자 파일** = .json

22.07.18
**KioskApp(화면전환,타이머구현,버튼이벤트→network check,list,뒤로가기 수정) = 0시간(목요일까지지만 집중해서 시간 줄이기)**

AndroidStudio **Print** 찍기 = `System.*out*.println("123");`

**Network** = [https://developer.android.com/training/basics/network-ops/managing?hl=ko](https://developer.android.com/training/basics/network-ops/managing?hl=ko)

[https://daldalhanstory.tistory.com/184](https://daldalhanstory.tistory.com/184)

[https://gist.github.com/PasanBhanu/730a32a9eeb180ec2950c172d54bb06a](https://gist.github.com/PasanBhanu/730a32a9eeb180ec2950c172d54bb06a)

**Network Check** = [https://soo0100.tistory.com/1305](https://soo0100.tistory.com/1305)

**App에서 설정으로 이동하기** = [https://kanais2.tistory.com/291](https://kanais2.tistory.com/291)

**Manifest** = [https://developer.android.com/guide/topics/manifest/service-element?hl=ko](https://developer.android.com/guide/topics/manifest/service-element?hl=ko)

**Alert,Button** = [https://lktprogrammer.tistory.com/155](https://lktprogrammer.tistory.com/155), 

### **단일 선택 목록 (List) 추가하기**

먼저 다이얼로그 창에 Setting 할 문자열 배열 리소스를 /res/values/strings.xml 경로 밑에 추가합니다.

```jsx
예시)
<resources>
    <string name="app_name">My Application</string>
    <string name="title_activity_sub">SubActivity</string>

    <string-array name = "LAN">
        <item>"Android"</item>
        <item>"Java"</item>
        <item>"C/C++"</item>
    </string-array>
</resources>
```

**ListView만들기 =** [https://ddaengddaeng.tistory.com/27](https://ddaengddaeng.tistory.com/27)

**네트워크 연결 안됐을 때 → alert → setting(network setting)**

![스크린샷, 2022-07-18 18-54-16.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2c93b3de-8bfe-474d-83f1-ea9caa6d5208/스크린샷_2022-07-18_18-54-16.png)

**list만들기**

**통신받기**

```


22.07.15 KioskApp 추가
**KioskApp(화면전환,타이머구현,버튼이벤트→network check,list,뒤로가기 수정) = 0시간**

[https://verad.tistory.com/entry/안드로이드-CountDownTimer-카운트다운타이머](https://verad.tistory.com/entry/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-CountDownTimer-%EC%B9%B4%EC%9A%B4%ED%8A%B8%EB%8B%A4%EC%9A%B4%ED%83%80%EC%9D%B4%EB%A8%B8)

[https://aries574.tistory.com/73](https://aries574.tistory.com/73)

**Timer Countdown(Text)** = [**https://learntutorials.net/ko/android/topic/6063/카운트-다운-타이머**](https://learntutorials.net/ko/android/topic/6063/%EC%B9%B4%EC%9A%B4%ED%8A%B8-%EB%8B%A4%EC%9A%B4-%ED%83%80%EC%9D%B4%EB%A8%B8)

**Button Click Event** = [https://recipes4dev.tistory.com/55](https://recipes4dev.tistory.com/55) ,[https://lcw126.tistory.com/35](https://lcw126.tistory.com/35)

**등본,졸업증명서,통장사본**

**과제 + 코딩테스트 1레벨**

**IT** = information technology는 전기 통신, 방송, 컴퓨팅(정보처리, 컴퓨터 네트워크, 컴퓨터 하드웨어, 컴퓨터 소프트웨어, 멀티미디어), 통신망 등 사회 기반을 형성하는 유형 및 무형의 기술 분야이다.

**Database** = [https://www.oracle.com/kr/database/what-is-database/](https://www.oracle.com/kr/database/what-is-database/)

데이터베이스는 일반적으로 컴퓨터 시스템에 전자적으로 저장되는 구조화된 정보 또는 데이터의 조직화된 모음입니다. 데이터베이스는 일반적으로 [데이터베이스 관리 시스템(DBMS)](https://www.oracle.com/kr/database/what-is-database/#WhatIsDBMS)
에 의해 제어됩니다. 연결된 애플리케이션과 함께 데이터와 DBMS를 하나로 묶어 데이터베이스 시스템이라고 하며 단축하여 데이터베이스라고도 합니다.

**Intro - 네트워크 체크 =** [https://developer.android.com/training/basics/network-ops/managing?hl=ko](https://developer.android.com/training/basics/network-ops/managing?hl=ko)

[https://developer.android.com/training/basics/network-ops/connecting?hl=ko](https://developer.android.com/training/basics/network-ops/connecting?hl=ko)

**Alert 사용**

1. Wifi = Wifi - 설정으로 넘기기?
2. LTE - 확인(데이터 이용~멘트), (버튼 = 확인 취소)

**MAIN** = 상품등록(구매하기 밑에 버튼)_리스트만들기, 이미지는 파일로X

App안에 데이터 저장_이름,가격,수량,url(image)-제품 상세이미지

*오감자,죠리퐁,새우깡,홈런볼

**구매완료(Complete)** = 리스트만들기

App안에 데이터 저장_이름,가격,url(image)

- **구매완료에서 뒤로 가기 눌렀을 때, PaymentAC로 가지면 안 됨**

22.07.14 KioskApp
**mac jdk환경변수 설정** - [https://velog.io/@newfff/JDK-환경변수PATH-설정-for-Mac](https://velog.io/@newfff/JDK-%ED%99%98%EA%B2%BD%EB%B3%80%EC%88%98PATH-%EC%84%A4%EC%A0%95-for-Mac)

**android studio import 자동설정 =** [https://shyunku.tistory.com/15](https://shyunku.tistory.com/15)

**android studio Button Click Event =**

[https://developer.android.com/guide/topics/ui/controls/button?hl=ko](https://developer.android.com/guide/topics/ui/controls/button?hl=ko)

[https://lktprogrammer.tistory.com/140](https://lktprogrammer.tistory.com/140)

[https://developer.android.com/guide/topics/ui/controls/button?hl=ko](https://developer.android.com/guide/topics/ui/controls/button?hl=ko)

**android stuio TextView, Layout 정렬 =**

[https://atomic0x90.github.io/android-studio/2020/03/04/android-studio-center-gravity.html](https://atomic0x90.github.io/android-studio/2020/03/04/android-studio-center-gravity.html)

**Activity LifeCycle** = [https://jaejong.tistory.com/60](https://jaejong.tistory.com/60)

**[Java][Android] Timer, TimerTask를 이용해 타이머 빨리 만들기 =** [https://stickode.tistory.com/9](https://stickode.tistory.com/9)

**Timer =** [https://gakari.tistory.com/entry/안드로이드-Android-Handler-와-TimerTimerTask-를-활용한-Intro-화면-구성](https://gakari.tistory.com/entry/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-Android-Handler-%EC%99%80-TimerTimerTask-%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%9C-Intro-%ED%99%94%EB%A9%B4-%EA%B5%AC%EC%84%B1)

[https://soo0100.tistory.com/1244](https://soo0100.tistory.com/1244)

```
Timer와TimerTask에 대해서 알아 보겠습니다.Timer는 간단하게 스케쥴을 관리 해주는 클래스인데요. 간단한 시간이나 반복적인 시간에 대해 컨트롤 하고 싶을 때 사용하는 클래스 입니다. 각각의 Timer는 각각의 스레드를 가지고 작업을 하고 있기 때문에 시간관리를 위해 만들어진 Thread라고 생각하시면 됩니다.

TimerTask란 Timer가 스케쥴을 관리하기 위해 사용하는"작업"이라고 생각하시면 되는데요. 위의 예제에서 Runnable의 역할이라고 생각 하시면 쉽습니다. 즉, Timer는 TimerTask를 가지고 스케쥴을 관리하고 있습니다.
```

Handler 개념?

**Android말고 Projecct로 보기**

디버깅 - 테스트폰 등

`[Intent](https://developer.android.com/reference/android/content/Intent)`는 개별 구성요소(예: 두 개의 활동) 간에 런타임 바인딩을 제공하는 객체입니다. `[Intent](https://developer.android.com/reference/android/content/Intent)`는 어떤 작업을 하려는 앱의 의도를 나타냅니다. 매우 다양한 작업에 인텐트를 사용할 수 있지만, 이 과정에서는 인텐트로 다른 활동을 시작합니다.
