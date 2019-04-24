# codestates_project

### 3명이 함께 진행한 sns상의 샵 데이터 수집 및 direct message 팀프로젝트입니다.

<div align=center>

[![](/img/kimbeomgyu.png)](https://github.com/kimbeomgyu)
[![](/img/Hyegyeong310.png)](https://github.com/Hyegyeong310)
[![](/img/pjj0714.png)](https://github.com/pjj0714)

</div>

<br>

## 기본 환경 설치

- node@latest

<br>

## Client Package Dependencies

- [Axios](https://www.npmjs.com/package/axios)
- [React](https://reactjs.org/docs/react-api.html)
- [React-dom](https://reactjs.org/docs/react-dom.html)
- [React-bootstrap](https://react-bootstrap.github.io/)
- [next](https://nextjs.org/docs)

## Server Package Dependencies

- [express](https://www.npmjs.com/package/express)
- [sequelize](https://www.npmjs.com/package/sequelize)
- [aws-sdk](https://www.npmjs.com/package/aws-sdk)
- [@google-cloud/vision](https://www.npmjs.com/package/@google-cloud/vision)
- [puppeteer](https://www.npmjs.com/package/puppeteer)

<br>

## 설명

- gelato와 제휴되지 않은 네일샵을 sns상에서 데이터 수집
- 수집한 데이터를 바탕으로 실제 가치있는 데이터로 판별 후 정제
- 정제한 네일샵들의 정보를 이용하여 제휴 요청 및 제휴 전환률 체크
- 제휴를 맺도록 하는 admin page 및 crawler 구현

> 로그인기능

![](/img/login_on_off.gif)
로그인기능을 추가해 보안을 강화했습니다.

![](/img/search_and_filter_and_pagination.gif)
각 샵들에 대한 정보를 검색 및 필터 작업이 가능하며 페이지를 나누어 로딩속도를 높혔습니다.

![](/img/message_template_create.gif)
보낼 메세지를 생성하여 저장합니다.

![](/img/message_send.gif)
메세지를 보내고 모바일 화면에서 받는 장면입니다.

<br>

### `Flow Chart`

![](/img/GelatoLab_project_flow_chart.png)

### `Google Cloud Vision`

![](/img/Google_Cloud_Vision_example.png)

### `service slide`

[서비스 소개 슬라이드](http://slides.com/betty310/deck-1#/)

### `service site`

[서비스 실행 사이트](https://codelab-no028chbo.now.sh/)
