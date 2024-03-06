## 🛠 기술스택

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white">
<img src="https://img.shields.io/badge/reactquery-3FF4154?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">


## 📺 화면구성   

![image](https://github.com/peeChulchul/my_portfolio/assets/144536397/1665cb21-e2f2-4ac8-9ea5-dfab859c1c5b)


## ❓ 주요기능

- **영상 검색**: 검색어에 따른 영상 검색
- **검색어 캐싱**: 검색결과를 캐싱하여 api 중복호출 방지

## ⚠ 트러블슈팅

### API 중복호출 및 무한스크롤시 캐싱된 데이터 값이 덮어 씌워지는 현상

<details><summary>문제
</summary>
<br/>
무한스크롤 사용으로 인해 검색어에 캐싱된 데이터가 마지막으로 호출한 Page Token의 데이터로 덮어 씌워짐
<br/>
</details>

<details><summary>해결
</summary>
<br/>
page Token도 query Key에 추가하여 첫페이지를 우선 보여주고 스크롤을 내렸을때 이미 캐싱된 page Token일 경우 로딩없이 바로 추가 페이지를 보여줄 수 있게되었습니다.
<br/>
</details>

---


