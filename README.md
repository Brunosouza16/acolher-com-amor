<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Acolher com Amor</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --primary: #1e90ff;
      --secondary: #f4f4f4;
      --dark: #333;
      --primary-hover: #1874d2;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: Arial, sans-serif; line-height: 1.6; background: var(--secondary); color: var(--dark); }
    header { background: var(--primary); color: white; padding: 1rem 0; text-align: center; }
    nav { display: flex; justify-content: center; background: var(--primary-hover); flex-wrap: wrap; }
    nav a { color: white; padding: 0.75rem 1.5rem; text-decoration: none; transition: background 0.3s; }
    nav a:hover { background: #105aa0; }
    .hero { background: url('https://images.unsplash.com/photo-1526256262350-7da7584cf5eb?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover; height: 60vh; display: flex; justify-content: center; align-items: center; text-align: center; color: white; flex-direction: column; padding: 0 1rem; background-blend-mode: overlay; background-color: rgba(30, 144, 255, 0.5); }
    .hero h1 { font-size: 2.5rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.2rem; max-width: 600px; }
    section { padding: 3rem 1rem; max-width: 1000px; margin: auto; }
    h2 { text-align: center; margin-bottom: 1.5rem; color: var(--primary); }
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; }
    .card { background: white; padding: 1.5rem; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    .card h3 { margin-bottom: 0.75rem; }
    .card p { margin-bottom: 1rem; }
    .card a { display: inline-block; padding: 0.5rem 1rem; background: var(--primary); color: white; border-radius: 5px; text-decoration: none; transition: background 0.3s; }
    .card a:hover { background: var(--primary-hover); }
    form { display: flex; flex-direction: column; gap: 0.75rem; max-width: 500px; margin: 1rem auto 0; }
    form input, form textarea, form select { padding: 0.75rem; border: 1px solid #ccc; border-radius: 5px; }
    form button { padding: 0.75rem; background: var(--primary); color: white; border: none; border-radius: 5px; cursor: pointer; transition: background 0.3s; }
    form button:hover { background: var(--primary-hover); }
    footer { background: var(--dark); color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>
  <header>
    <h1>Acolher com Amor</h1>
    <p>Juntos podemos transformar vidas nas ruas</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#ajudar">Como Ajudar</a>
    <a href="#cadastro">Cadastro</a>
    <a href="#eventos">Eventos</a>
    <a href="#noticias">Notícias</a>
    <a href="voluntariado.html" target="_blank">Voluntariado</a>
    <a href="#contato">Contato</a>
  </nav>

  <div class="hero">
    <h1>Estenda sua mão a quem mais precisa</h1>
    <p>Nosso objetivo é apoiar pessoas e famílias que acolhem pessoas em situação de vulnerabilidade, arrecadando alimentos, roupas e doações financeiras.</p>
  </div>

  <section id="sobre">
    <h2>Quem Somos</h2>
    <p>Somos um grupo solidário dedicado a apoiar pessoas e abrigos que acolhem pessoas em situação de vulnerabilidade. Organizamos campanhas de arrecadação, conectamos doadores e promovemos ações sociais que geram impacto real na vida de quem mais precisa.</p>
  </section>

  <section id="ajudar">
    <h2>Como Você Pode Ajudar</h2>
    <div class="cards">
      <div class="card">
        <h3>🍽 Doar Alimentos</h3>
        <p>Contribua com alimentos não perecíveis para famílias e abrigos parceiros.</p>
        <a href="#">Quero Doar</a>
      </div>
      <div class="card">
        <h3>👕 Doar Roupas</h3>
        <p>Ajude com roupas em bom estado para enfrentar o frio e o dia a dia.</p>
        <a href="#">Quero Ajudar</a>
      </div>
      <div class="card">
        <h3>💰 Apoio Financeiro</h3>
        <p>Faça parte da mudança com qualquer valor. Sua contribuição faz diferença.</p>
        <a href="#">Contribuir</a>
      </div>
    </div>
  </section>

  <section id="cadastro">
    <h2>Cadastro de Voluntários / Doadores</h2>
    <p style="text-align:center; max-width:700px; margin:0 auto 1.5rem;">
      Junte-se a nós na missão de transformar vidas! 💙<br>
      Ao se cadastrar, você estará contribuindo diretamente para apoiar pessoas em situação de rua, oferecendo alimento, roupas, carinho e esperança. Cada gesto conta, e juntos podemos fazer a diferença na vida de quem mais precisa.
    </p>
    <form>
      <input type="text" placeholder="Nome completo" required>
      <input type="email" placeholder="E-mail" required>
      <input type="tel" placeholder="Telefone (opcional)">
      <select required>
        <option value="">Selecione seu interesse</option>
        <option value="voluntario">Quero ser voluntário</option>
        <option value="doacoes">Quero fazer doações</option>
        <option value="parceria">Quero propor parceria</option>
      </select>
      <textarea rows="4" placeholder="Conte-nos mais sobre você (opcional)"></textarea>
      <button type="submit">Cadastrar</button>
    </form>
  </section>

  <section id="eventos">
    <h2>Próximos Eventos</h2>
    <p style="text-align:center; max-width:700px; margin:0 auto 1.5rem;">
      Participe das nossas ações e campanhas! 💙<br>
      Cada evento é uma oportunidade de apoiar quem precisa, compartilhar solidariedade e fazer parte de uma comunidade que transforma vidas.
    </p>
    <div class="cards">
      <div class="card">
        <h3>🍲 Campanha de Alimentos</h3>
        <p>Data: <br>Local: Praça Central</p>
        <a href="#">Participar</a>
      </div>
      <div class="card">
        <h3>👕 Coleta de Roupas</h3>
        <p>Data: <br>Local: Centro Comunitário</p>
        <a href="#">Participar</a>
      </div>
      <div class="card">
        <h3>💖 Dia do Voluntário</h3>
        <p>Data: <br>Local: Abrigo São João</p>
        <a href="#">Participar</a>
      </div>
    </div>
  </section>

  <section id="noticias">
    <h2>Notícias e Atualizações</h2>
    <p style="text-align:center; max-width:700px; margin:0 auto 1.5rem;">
      Fique por dentro das nossas últimas ações, campanhas e histórias de transformação! 💙
    </p>
    <div class="cards">
      <div class="card">
        <h3>🎉 Campanha de Inverno Concluída</h3>
        <p>Mais de 500 peças de roupas foram entregues a quem mais precisava. Agradecemos a todos os voluntários!</p>
        <a href="#">Leia mais</a>
      </div>
      <div class="card">
        <h3>🍽 Doações de Alimentos em Novembro</h3>
        <p>Arrecadamos mais de 1.200 kg de alimentos não perecíveis, beneficiando diversas famílias.</p>
        <a href="#">Leia mais</a>
      </div>
      <div class="card">
        <h3>💖 Dia do Voluntário 2025</h3>
        <p>Celebramos nossos voluntários com uma confraternização e reconhecimento por toda dedicação.</p>
        <a href="#">Leia mais</a>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Entre em Contato</h2>
    <p style="text-align:center; max-width:700px; margin:0 auto 1.5rem;">
      Tem dúvidas, sugestões ou quer mais informações sobre como ajudar? 💙<br>
      Envie sua mensagem e nossa equipe entrará em contato o mais rápido possível.
    </p>
    <form>
      <input type="text" placeholder="Nome completo" required>
      <input type="email" placeholder="Seu e-mail" required>
      <input type="tel" placeholder="Telefone (opcional)">
      <textarea placeholder="Sua mensagem" rows="5" required></textarea>
      <button type="submit">Enviar Mensagem</button>
    </form>
    <p style="text-align:center; margin-top:1rem;">
      Ou fale conosco pelo <a href="mailto:contato@acolhercomamor.com" style="color:var(--primary); text-decoration:none;">e-mail</a> ou <a href="https://wa.me/559999999999" target="_blank" style="color:var(--primary); text-decoration:none;">WhatsApp</a>.
    </p>
  </section>

  <footer>
    <p>© 2025 Acolher com Amor — Todos os direitos reservados</p>
  </footer>
</body>
</html>
