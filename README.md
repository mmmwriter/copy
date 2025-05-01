<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>계좌번호 복사됨</title>
  <script>
    const text = decodeURIComponent(window.location.search.split('=')[1] || '신한은행 110414056104');
    navigator.clipboard.writeText(text).then(() => {
      alert('📋 계좌번호가 복사되었습니다: ' + text);
    });
  </script>
</head>
<body>
  <h2>📌 송금 계좌번호가 복사되었습니다</h2>
  <p>이제 토스 또는 은행 앱에서 붙여넣기 해주세요 😊</p>
</body>
</html>
