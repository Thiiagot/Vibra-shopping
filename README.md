# Vibra-shopping<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vibra Shopping</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">Vibra Shopping</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#servicos">Serviços</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Bem-vindo à Vibra Shopping</h1>
    <p>Soluções para o seu negócio crescer!</p>
    <a href="#contato" class="cta">Entre em contato</a>
  </section>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>A Vibra Shopping é especializada em administração e gestão de negócios, oferecendo soluções inteligentes para maximizar seus resultados.</p>
  </section>

  <section id="servicos">
    <h2>Nossos Serviços</h2>
    <ul>
      <li>Administração de condomínios</li>
      <li>Consultoria para negócios</li>
      <li>Planejamento estratégico</li>
    </ul>
  </section>

  <section id="contato">
    <h2>Fale Conosco</h2>
    <form action="#">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>

      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>

      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" required></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Vibra Shopping. Todos os direitos reservados.</p>
  </footer>
</body>
</html>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  line-height: 1.6;
  color: #333;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #00509E;
  color: white;
  padding: 1rem 2rem;
}

header .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li {
  margin-left: 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

.hero {
  background: #0074D9;
  color: white;
  text-align: center;
  padding: 3rem 1rem;
}

.hero h1 {
  font-size: 2.5rem;
}

.hero .cta {
  background: #FF4136;
  color: white;
  padding: 0.5rem 1rem;
  text-decoration: none;
  border-radius: 5px;
}

section {
  padding: 2rem;
  text-align: center;
}

section h2 {
  margin-bottom: 1rem;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

form input, form textarea, form button {
  width: 80%;
  margin-bottom: 1rem;
  padding: 0.5rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  background: #0074D9;
  color: white;
  border: none;
  cursor: pointer;
}

footer {
  background: #00509E;
  color: white;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}
