# :open_file_folder: 웹사이트 주소
[TRAVEL] (https://cherinpark.github.io/html/)

 
# :mag_right: 개발 계기
* 자율적으로 만든 첫 웹사이트인 만큼 2021년도에 갔었던 여행 기록과 사진을 볼 수 있으며, 제가 좋아하는 것들로 꾸며져 있습니다. 

* Sublime을 이용하여 제작했으며, 총 페이지 수는 메인화면 포함 5페이지 입니다.

# :date: 개발 기간
* 2021.10.07~2021.12.12

# :pushpin: 캡쳐 화면

* 메인 페이지
>Sockho가 current page인 경우
![image](https://user-images.githubusercontent.com/117168607/200254987-20c2a12a-ae29-4baf-93f9-f20dca664d23.png)


  * header에 있는 모든 페이지가 연결될수 있도록 하고 변경될때마다 current와 highlight으로 현재 페이지를 표시했습니다.

---

* Jeju 페이지
  * 슬라이드 기능을 사용하고 싶었는데 Sublime에서의 적용법을 찾지 못했습니다. 결국 리서치를 하여 Java Script 기반으로 만들어진 코드를 추가하였습니다. 
  * swiperslide의 loop는 무한대로 설정하였고, 양 옆에 화살표를 적용시켜 방향 전환도 자율적이게 했습니다.




 > Jeju.html에서의 적용된 swiperslide 코드


  <img src="https://user-images.githubusercontent.com/117168607/200257453-1cba287a-adc9-49d5-b3c9-915a954d14d3.png" width="50%" height="50%"/>


---

* Sokcho 페이지
  * 하단의 4개 이미지를 클릭하면 팝업창으로 관련 사진과 함께 감상평을 담은 container 추가


     팝업창이 제대로 뜨지 않거나 닫히지 않는 문제, 페이지 스크롤을 하면 따라오는 문제 등 편리한 인터페이스를 위해 수정을 여러번 했습니다. 
  * 사용하고 있는 Chrome에서 video를 저작권 문제로 사용할 수 없도록 막음
  
  >muted로 소리를 없애 저작권 문제를 해결했습니다.


   `<video src="pop.mp4" autoplay muted loop></video>`

  

---

* Cats 페이지
  * Cats 페이지 하단에 있는 form 창은 방문자가 찍은 귀여운 고양이 사진들을 공유받기 위해 추가했습니다.~사심을 담은~

---

* css

  * 컴퓨터에 설치되어 있는 글씨체와 웹에서 사용할 폰트들이 알맞게 호환되지 않아 어려움을 겪었습니다.


  * 해결 과정에서 웹폰트로 사용할 수 있도록 코드가 제공되는 것을 알게 되었습니다. 알파벳의 대소문자가 일치해야 하고 영문 이름을 기입해야 정확히 적용되는 점을 적용했습니다.

> 사용 폰트(캡쳐 화면)
<img src="https://user-images.githubusercontent.com/117168607/200250245-b7e407b6-024e-4fd5-bc42-9bb3ce21a6fd.png" width="50%" height="50%"/>
<img src="https://user-images.githubusercontent.com/117168607/200250391-ac12b438-330d-462f-a764-c1914b781bb7.png" width="55%" height="55%"/>
<img src="https://user-images.githubusercontent.com/117168607/200250485-c6219e8f-b77d-4f18-be40-85e32d4f6c2c.png" width="30%" height="30%"/>

# :bulb: 부가 설명
링크 공유를 위해 Github에서 제공하는 정적 웹페이지 호스팅 서비스(Git Pages)를 이용했습니다.
