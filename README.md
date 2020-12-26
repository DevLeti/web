# nice features - web

개인적으로 웹에서 쓸만하다 생각하는 외부 라이브러리들 정리.

## website
1. [LOLCOLORS](https://www.webdesignrankings.com/resources/lolcolors)
   - 컬러팔레트.

## js
1. [slick.js](http://kenwheeler.github.io/slick/)
   - 간단하게 구현 가능한 슬라이더 라이브러리. 직접 들어가서 코드 보면 되게 쉽게 되어있다.
2. [fullPage.js](https://alvarotrigo.com/fullPage/ko/)
   - 스크롤 웹사이트 라이브러리. [배달의민족](https://www.baemin.com/)과 [네이버 모두](https://www.modoo.at/home)에서 이 라이브러리를 사용한 것 같다.
   - 이걸로 웹사이트를 상업적으로 제작하면 비용 지불 해야함.
3. [clipboard.js](https://clipboardjs.com/)
   - 클립보드에 값을 복사하게 해주는 라이브러리.
   - [MIT License](https://github.com/zenorocha/clipboard.js/blob/master/LICENSE)여서 상업 이용 가능.
4. [moment.js](https://momentjs.com/)
   - 시간과 관련된 정보를 나타낼 때 유용한 라이브러리.
   - 시간을 나타내는 형식(format dates)을 다양하게 표현할 수 있음
   - 시간 비교&계산(Relative & Calendar Time), Multiple Locale을 지원.
   - [MIT License](https://github.com/zenorocha/clipboard.js/blob/master/LICENSE)여서 상업 이용 가능.
4. [Day.js](https://momentjs.com/)
   - moment.js의 경량화 버젼 라이브러리. 2KB로 매우 작은 용량이 특징.
   - 변경 불가능(immutable)해서 변수에 할당된 day.js 객체를 add, subtract등으로 값을 변경하면 다시 변수에 할당해줘야함.
   - 추가 기능은 플러그인으로 지원 (Timezone, Locale 등등)
   - 많은 기능이 필요하지 않으면 이쪽이 괜찮은 선택일 것 같다.