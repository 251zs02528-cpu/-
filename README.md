<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>自己紹介ページ</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f0f0f0;
      text-align: center;
      padding: 40px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <h1>自作Webページ</h1>
  <p id="message">ボタンを押してください</p>
  <button onclick="changeText()">クリック</button>

  <script>
    function changeText() {
      document.getElementById("message").textContent = "JavaScriptで文字を変更しました";
    }
  </script>

</body>
</html>
