<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>프론트엔드 기술 스택</title>
  <style>
    body {
      font-family: 'Malgun Gothic', sans-serif;
      background: #f9f9f9;
      padding: 40px;
    }

    .section-title {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 16px;
    }

    .tech-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 15px;
      background: #fff;
    }

    .tech-table th {
      background: #f0f0dc;
      font-weight: bold;
      padding: 12px 16px;
      border: 1px solid #ccc;
      text-align: center;
    }

    .tech-table td {
      padding: 16px;
      border: 1px solid #ccc;
      vertical-align: middle;
    }

    .tech-table td:first-child {
      text-align: center;
      width: 220px;
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 5px;
      padding: 6px 12px;
      border-radius: 6px;
      font-size: 13px;
      font-weight: bold;
      margin: 3px;
    }

    .b-jsp       { background: #3d7ab5; color: #d6eaf8; }
    .b-js        { background: #f0c30e; color: #4a3900; }
    .b-jquery    { background: #1565a8; color: #b3d4f5; }
    .b-bootstrap { background: #6f42c1; color: #e8d5ff; }
    .b-mybatis   { background: #222;    color: #ddd;    }
  </style>
</head>
<body>

  <div class="section-title">🌐 프론트엔드</div>

  <table class="tech-table">
    <thead>
      <tr>
        <th>기술</th>
        <th>설명</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><span class="badge b-jsp">JSP</span></td>
        <td>서버 사이드 렌더링 기반 동적 HTML 생성</td>
      </tr>
      <tr>
        <td>
          <span class="badge b-js">JS JavaScript</span>
          <span class="badge b-jquery">jQuery</span>
        </td>
        <td>클라이언트 상호작용 구현 및 Ajax 요청 처리</td>
      </tr>
      <tr>
        <td><span class="badge b-bootstrap">B Bootstrap</span></td>
        <td>반응형 UI 디자인 구현</td>
      </tr>
      <tr>
        <td><span class="badge b-mybatis">MyBatis</span></td>
        <td>View와 DB 간의 데이터 매핑 처리 (JSP ↔ DAO)</td>
      </tr>
    </tbody>
  </table>

</body>
</html>