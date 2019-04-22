# codestates_project

### 3명이 함께 진행한 sns상의 샵 데이터 수집 및 direct message 팀프로젝트입니다.

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

  <br>
  
  
### `Flow Chart`

![](http://bit.ly/2PlGAVL) 

### `Google Cloud Vision`

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/f4191b32-bd40-4b2e-93f3-831cb6c25c46/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAT73L2G45L66NENGH%2F20190422%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20190422T104117Z&X-Amz-Expires=86400&X-Amz-Security-Token=AgoJb3JpZ2luX2VjEMj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBlbidtHsnSddxlu%2Fm%2BzTLB318NbpcpEHPDLICLn9tGQAiEAzcBE3sHR71AWGPKwXCOP5SIj2vEpA7J21xcUxgXLMRMq4wMIof%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwyNzQ1NjcxNDkzNzAiDDF3nlQTTu6awxD10iq3A4GJVtC4o1m%2F9zyam1A2sBbFG6POMgvw%2FIZlZADMSw%2B55g6%2BAkDKLhEJMoBYZeM7Z8rrUuLCnmyNoZ0wYWzdOly1aTMakmrdde3xI5AZSGZxwCsPkP4xj1crhKRkgLamqnQ7ZZkxozWDsC7humu5MgRC76VYrOCt87nTZ4FHSrFU0XMgC4ykdDCSGJa2rqZwXhsVKEZH%2BQrjAnfx2Syt3VfxPOwAc9OHqjyjxKuXu%2B2okw%2BxKsyaLgvcmvvazFvj6OKlfDgxW0sGG%2BOXPeXe6j42LDzVv%2B%2FfqwCHRwBgsB35HxB%2B%2FH6BX2%2FsrMIdS%2FXiEjDh05H02DFX%2BBFiZIl%2BysIvc%2FNM0Fn8ZPD%2FEUuF9S8cDLI33oO6%2FgN2X6pQ4%2FTeJTQ25qOtdInOJ0GTrkcrOs58K1KDzHdHqeXcNWSgXeLydncQ38F3X6vfQ%2FkZZKkDTVBRpCTV74XchGuwSkgchEFxPLKuSv2tZCPs1zS%2B0KjvtKXabcwv0ic%2FKIR6RvQE5r%2FUiUHdhELBJT27dZeaxPqrzcAjglxQYG13WZ0dWfKua4dsHRFIQkn4ZmoT041Ebewtxzcaa%2FIwld315QU6tAG1%2BZwq2AEn8Oq7STkuURrJQm68PqM%2BzfPUUC0SDI5KvMCs102VDeTc6YPZePX7KJ6pjaY92neMxNL0venMyUXqXgXebMTm%2F0TtzAY4fO4R0Gld5%2BLd%2B1C9UFRWvOFOu4f9DlTbwQk%2FEP%2BBsxCCVnJ2HiGkCheNTOkasd5zNf1nN%2BUGRFfZRcByH1%2FpZWXMbqHfGLJ4vdo5B2nwccvnCl9gKXnByaU3PcDFUiKszQ6nc5BJZDg%3D&X-Amz-Signature=c33d2546ec044f414daaa6979d38e40479fe92e45a74518f2ecfa4a2f277a6f7&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22image.png%22)

### `service slide`

[서비스 소개 슬라이드](http://slides.com/betty310/deck-1#/)
