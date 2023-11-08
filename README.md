# Louis Vuiton 쇼핑몰 웹사이트 
부트스트랩을 이용한 반응형 쇼핑몰 웹페이지를 구축. 
![](https://i.imgur.com/5Tb5RzN.jpg)

* Demo: https://noona-louisvuitton.netlify.app/

### 개발 목표 
부트스트랩의 다양한 컴포넌트와 클래스 사용 및 부트스트랩 Grid 이해. 미디어쿼리를 이용한 반응형 웹페이지 구축
### 사용 기술
* HTML
* CSS
* Bootstrap
* Media Query
### Advanced Feature
* 미디어 쿼리를 이용한 footer 개발 <br>
 _(web 버전)_
![](https://i.imgur.com/4uqRyU0.png)
 _(모바일 버전)_ <br>
![](https://i.imgur.com/Clb1bdW.png)
```css=
@media screen and (max-width: 48rem) {
  .second-line {
    padding: 0 2rem;
  }

  .flag {
    display: none;
  }

  .first-line {
    text-align: center;
  }

  .mobile-footer {
    display: block;
  }
}
.col {
  padding-bottom: 1rem;
}
.flag-img {
  margin: 0 0.5rem;
}
```
* 부트스트랩 Grid를 이용한 반응형 레이아웃 구축<br>
 _(web 버전)_
![](https://i.imgur.com/Z8VL6OC.png)
 _(모바일 버전)_ <br>
![](https://i.imgur.com/xHGAWlc.png)
```html=
 <div class="container pt-5 pb-5">
    <div class="row"> 
        <div class="col-md-4 col-sm-12">
            <div class="card">
                <img src="https://www.louisvuitton.com/images/louis-vuitton--U_Holidays_2020_Push5_V2_DI1.jpg?wid=656"
                    class="card-img-top" alt="...">
                <div class="card-body text-center">
                    <h2 class="card-text">LATEST SELECTION</h2>
                </div>
            </div> 
        </div>
        <div class="col-md-4 col-sm-12">
            <div class="card">
                <img src="https://www.louisvuitton.com/images/louis-vuitton--U_Holidays_2020_Push6_V2_DI1.jpg?wid=656"
                    class="card-img-top" alt="...">
                <div class="card-body">
                    <h2 class="card-text text-center">GIFTS FOR HIM</h2>
                </div>
            </div>
        </div>
        <div class="col-md-4 col-sm-12">
            <div class="card">
                <img src="https://www.louisvuitton.com/images/louis-vuitton--U_Holidays_2020_Push7_V2_DI1.jpg?wid=656"
                    class="card-img-top" alt="...">
                <div class="card-body">
                    <h2 class="card-text text-center">GIFTS FOR HER</h2>
                </div>
            </div>
        </div>
    </div>
</div>
```

* 부트스트랩에서 제공하는 클래스들을 사용해 CSS 코드의 불필요한 중복을 없앰


### 개선사항
* Discover the Campagine 버튼에 hover 이벤트 필요
* 이미지 로딩이 속도 해결 필요


