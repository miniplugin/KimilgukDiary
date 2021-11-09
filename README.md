### 스프링서버의 사용자별 개인일기를 작성가능한 앱을 만듭니다.
- 개발환경: Android Studio 4.1.2 (https://developer.android.com/studio)
- 빌드버전: Configure 메뉴에서 installed 버전 확인 가능 Android11.0(R):API30
- 자바JVM버전: OpenJDK1.8.0242
- Empty Activity 로 프로젝트 생성
- 프로젝트명: KimilgukDiary
- 패키지명: edu.android.kimilgukdiary
- 개발언어: 자바
- Minimum SDK: API 19:Android4.4(KitKat) = 삼성겔럭시S1 까지 지원
- Use legacy android.support libraries 체크:안함.(com.android.support:appcompat-v7사용안하고, androidx.appcompat 사용)
- 목표: 스프링 서버의 사용자별 인증 후 개별 일기를 작성가능하게 처리
- 회원가입은 WebView 사용: https://kimilguk.herokuapp.com/join

#### 20211110(수)
- KimilgukDiary 신규프로젝트 생성 및 깃 저장소 연동
- VCS > Create Git Repository 로 시작.
- VCS > Commit 후 Git > Push 로 진행