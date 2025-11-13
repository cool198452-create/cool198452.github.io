<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>회사 소개</title>
  <style>
    /* --- 기본 스타일 --- */
    body {
      font-family: 'Noto Sans KR', sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #222;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      position: sticky;
      top: 0;
    }

    header h1 {
      font-size: 1.4rem;
    }

    nav a {
      color: #fff;
      margin: 0 12px;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.2s;
    }

    nav a:hover {
      color: #00bcd4;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }

    /* 홈 */
    #home {
      text-align: center;
      padding-top: 100px;
    }

    #home h2 {
      font-size: 2.2rem;
    }

    /* 소개 */
    #about {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    /* 갤러리 */
    #gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    #gallery img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    /* 회원가입 */
    form {
      disp
