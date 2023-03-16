<h1 align="center">Android Architecture Study</h1><br/>

## Architecture
![image](./final-architecture.png)<br></br>

## 과제
### Naver open api 를 이용하여 검색 앱 개발

**step1.**
* 사용자 입력 값으로 검색한 결과를 리스트 형태로 보여준다.
* 하단 3개의 탭 구성. (영화, 이미지, 블로그 검색 탭)
* 무한 스크롤


**필수 구현 사항**
* AAC 를 활용한 MVVM 구조로 프로젝트 설계
* Repository Pattern 적용하여 Data, Repository, DataSource layer 분리
* DI - Hilt
* AAC - LiveData, Navigation, ViewModel, Databinding, Room
* Retrofit2 + Okhttp3
