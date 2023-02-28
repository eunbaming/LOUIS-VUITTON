# LOUIS-VUITTON 쇼핑몰 웹사이트

실제 LOUIS-VUITTON 사이트를 참고하여 Bootstrap을 이용한 반응형 웹사이트 구축

![LOUIS-VUITTON](https://user-images.githubusercontent.com/110072947/221730869-c48c63ef-39b1-41d4-8d73-90d5a559195a.png)

+ Demo : https://hnm-website.vercel.app/


### 개발 목표

Bootstrap을 이용하여 navbar, carousel 등을 제작하고, 거기에서 더 나아가 Media Query를 이용하여
사용자의 눈에 보기 좋게 반응형 웹사이트를 개발


### 사용 기술

<a href="#"><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=Bootstrap&logoColor=white"/></a>


### Advanced Feature

+ Bootstrap을 이용하여 navbar, carousel를 디자인하고, Container/Row/Col 속성을 사용하여 웹사이트를 반응형으로 개발

[Web ver.]

![LOUIS-VUITTON](https://user-images.githubusercontent.com/110072947/221736855-960becd9-999d-4ab2-83bf-1cd7a5e41619.png)

[Mobile ver.]

<img src="https://user-images.githubusercontent.com/110072947/221737223-bdced515-dac4-4096-8b4c-f30102db2456.png" width="400">

+ margin, padding 등을 css가 아닌 Bootstrap으로 html에 보다 더 간결한 코드로 개발

```html
<div class="text-center mt-5 mb-5">
  <h2 style="font-weight: 300;">JOURNEY HOME FOR THE HOLIDAY</h2>
  <p>Starring Alicia Vikander</p>
  <button type="button" class="btn btn-dark">Discover the Campagine</button>
</div>
```

+ Media Query를 이용하여 반응형 footer 개발

[web ver.]

![LOUIS-VUITTON](https://user-images.githubusercontent.com/110072947/221751308-8b64fe60-8185-4dce-b128-06dfedee46cf.png)

[Mobile ver.]

<img src="https://user-images.githubusercontent.com/110072947/221751199-53bb14fb-e716-4c16-8c01-0d35fd5ef6db.png" width="500">

```css
@media screen and (max-width:48rem){
  .first-line {
    text-align: center;
  }
  .second-line {
    padding-left: 1rem;
    padding-right: 1rem;
    border-bottom: 1px solid #392d23;
  }
  .flag {
    display: none;
  }
  .third-line {
    display: block;
    color: white;
  }
}
```


### 개선 사항

+ carousel 슬라이드의 이미지들을 비율에 각각 알맞게 편집 필요

+ 상품 디테일 페이지 

