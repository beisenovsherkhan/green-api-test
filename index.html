<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GREEN-API Test Page</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 20px; max-width: 600px; margin: auto; }
    input, button, textarea { width: 100%; margin: 10px 0; padding: 10px; }
    button { cursor: pointer; }
    textarea { height: 200px; }
  </style>
</head>
<body>
  <h1>GREEN-API Test Page</h1>

  <label>ID Instance</label>
  <input type="text" id="idInstance" placeholder="Введите idInstance">

  <label>API Token Instance</label>
  <input type="text" id="apiTokenInstance" placeholder="Введите ApiTokenInstance">

  <button onclick="getSettings()">getSettings</button>
  <button onclick="getStateInstance()">getStateInstance</button>

  <h3>Отправить сообщение</h3>
  <input type="text" id="phoneNumber" placeholder="Введите номер телефона (в формате 7XXXXXXXXXX)">
  <input type="text" id="messageText" placeholder="Введите текст сообщения">
  <button onclick="sendMessage()">sendMessage</button>

  <h3>Отправить файл по URL</h3>
  <input type="text" id="fileUrl" placeholder="Введите URL файла">
  <input type="text" id="fileCaption" placeholder="Введите подпись к файлу">
  <button onclick="sendFileByUrl()">sendFileByUrl</button>

  <h3>Ответ:</h3>
  <textarea id="output" readonly></textarea>

  <script>
    function getBaseUrl(method) {
      const id = document.getElementById('idInstance').value;
      const token = document.getElementById('apiTokenInstance').value;
      return `https://api.green-api.com/waInstance${id}/${method}/${token}`;
    }

    async function getSettings() {
      const response = await fetch(getBaseUrl('getSettings'));
      const data = await response.json();
      showOutput(data);
    }

    async function getStateInstance() {
      const response = await fetch(getBaseUrl('getStateInstance'));
      const data = await response.json();
      showOutput(data);
    }

    async function sendMessage() {
      const phone = document.getElementById('phoneNumber').value;
      const message = document.getElementById('messageText').value;
      const response = await fetch(getBaseUrl('sendMessage'), {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({
          chatId: phone + "@c.us",
          message: message
        })
      });
      const data = await response.json();
      showOutput(data);
    }

    async function sendFileByUrl() {
      const phone = document.getElementById('phoneNumber').value;
      const url = document.getElementById('fileUrl').value;
      const caption = document.getElementById('fileCaption').value;
      const response = await fetch(getBaseUrl('sendFileByUrl'), {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({
          chatId: phone + "@c.us",
          urlFile: url,
          fileName: "file",
          caption: caption
        })
      });
      const data = await response.json();
      showOutput(data);
    }

    function showOutput(data) {
      document.getElementById('output').value = JSON.stringify(data, null, 2);
    }
  </script>
</body>
</html>

