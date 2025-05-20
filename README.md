- 👋 Hi, I’m @loukas9767
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Projeto de Alta Fidelidade</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Montserrat', sans-serif;
    background: #f0f4f8;
    color: #333;
    line-height: 1.6;
  }
  header {
    background: linear-gradient(135deg, #667eea, #764ba2);
    padding: 40px 20px;
    color: white;
    text-align: center;
    box-shadow: 0 4px 8px rgba(102, 126, 234, 0.4);
  }
  header h1 {
    font-weight: 700;
    font-size: 2.8rem;
    margin: 0 0 10px;
    letter-spacing: 2px;
  }
  header p {
    font-size: 1.2rem;
    font-weight: 400;
    margin: 0;
  }
  main {
    max-width: 960px;
    margin: 40px auto;
    padding: 0 20px;
  }
  section {
    margin-bottom: 48px;
  }
  h2 {
    font-weight: 700;
    font-size: 2rem;
    color: #4a4a4a;
    margin-bottom: 20px;
    border-bottom: 3px solid #667eea;
    display: inline-block;
    padding-bottom: 6px;
  }
  p {
    font-size: 1.1rem;
    margin-bottom: 16px;
  }
  ul.benefits-list {
    list-style: none;
    padding-left: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
  }
  ul.benefits-list li {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(102, 126, 234, 0.1);
    font-weight: 500;
    font-size: 1rem;
  }
  .showcase {
    display: flex;
    flex-wrap: wrap;
    gap: 24px;
    justify-content: center;
  }
  .card {
    background: white;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(118, 75, 162, 0.15);
    width: 280px;
    overflow: hidden;
    cursor: pointer;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 30px rgba(118, 75, 162, 0.3);
  }
  .card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
  }
  .card-content {
    padding: 16px 20px;
  }
  .card-content h3 {
    margin-top: 0;
    margin-bottom: 8px;
    color: #667eea;
  }
  .card-content p {
    font-size: 0.95rem;
    color: #555;
  }
  footer {
    background: #333;
    color: #ddd;
    text-align: center;
    padding: 24px 20px;
    font-size: 0.9rem;
    margin-top: 60px;
  }
  a.cta-button {
    display: inline-block;
    background: #764ba2;
    color: white;
    padding: 14px 28px;
    border-radius: 36px;
    font-weight: 700;
    text-decoration: none;
    transition: background-color 0.3s ease;
    margin-top: 12px;
  }
  a.cta-button:hover {
    background-color: #5a3581;
  }
  @media(max-width: 480px){
    header h1 {
      font-size: 2rem;
    }
    .card {
      width: 100%;
    }
  }
</style>
</head>
<body>
<header>
  <h1>Projeto de Alta Fidelidade</h1>
  <p>Transformando ideias em experiências digitais profissionais e imersivas</p>
</header>
<main>
  <section id="introducao">
    <h2>O que é um Projeto de Alta Fidelidade?</h2>
    <p>Um projeto de alta fidelidade é um protótipo detalhado e realista que representa uma aplicação ou website quase na sua forma final. É utilizado para validar visualmente e funcionalmente o design, permitindo a validação de usabilidade, interação e estética antes do desenvolvimento.</p>
    <p>Este tipo de projeto contém elementos reais como imagens, texto realmente formatado, navegação funcional e simulação de interações, ajudando equipes e clientes a entender exatamente como será o produto final.</p>
  </section>
  <section id="beneficios">
    <h2>Benefícios do Projeto de Alta Fidelidade</h2>
    <ul class="benefits-list">
      <li>Compreensão clara das funcionalidades e design</li>
      <li>Feedback preciso e construtivo</li>
      <li>Redução de erros na fase de desenvolvimento</li>
      <li>Alinhamento eficiente entre equipe e cliente</li>
      <li>Teste de usabilidade realista</li>
      <li>Economia de tempo e recursos no projeto final</li>
    </ul>
  </section>
  <section id="exemplos">
    <h2>Exemplos de Projetos de Alta Fidelidade</h2>
    <div class="showcase">
      <div class="card" tabindex="0" aria-label="Protótipo mobile de aplicativo de finanças">
        <img src="https://images.unsplash.com/photo-1519648023493-d82b5f8d7b9a?auto=format&fit=crop&w=600&q=80" alt="Protótipo mobile" />
        <div class="card-content">
          <h3>App Financeiro Mobile</h3>
          <p>Protótipo interativo para controle financeiro pessoal com dashboard moderno e navegação intuitiva.</p>
        </div>
      </div>
      <div class="card" tabindex="0" aria-label="Protótipo website de ecommerce">
        <img src="https://images.unsplash.com/photo-1502877338535-766e1452684a?auto=format&fit=crop&w=600&q=80" alt="Protótipo website" />
        <div class="card-content">
          <h3>Website E-commerce</h3>
          <p>Protótipo visualmente rico com páginas de produtos, filtro dinâmico e checkout simplificado.</p>
        </div>
      </div>
      <div class="card" tabindex="0" aria-label="Protótipo dashboard administrativo">
        <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=600&q=80" alt="Protótipo dashboard" />
        <div class="card-content">
          <h3>Dashboard Administrativo</h3>
          <p>Protótipo detalhado para gestão de dados corporativos com gráficos interativos e relatórios.</p>
        </div>
      </div>
    </div>
  </section>
  <section id="contato">
    <h2>Quer saber mais?</h2>
    <p>Entre em contato para desenvolver seu projeto de alta fidelidade e transformar suas ideias em experiências incríveis!</p>
    <a class="cta-button" href="mailto:contato@altafidelidade.com">Fale Conosco</a>
  </section>
</main>
<footer>
  &copy; 2024 Projeto de Alta Fidelidade &mdash; Todos os direitos reservados
</footer>
<script>
  // Optional subtle animation - highlight card on focus for better accessibility
  document.querySelectorAll('.card').forEach(card => {
    card.addEventListener('focus', () => {
      card.style.transform = 'translateY(-8px)';
      card.style.boxShadow = '0 12px 30px rgba(118, 75, 162, 0.3)';
    });
    card.addEventListener('blur', () => {
      card.style.transform = '';
      card.style.boxShadow = '0 8px 20px rgba(118, 75, 162, 0.15)';
    });
  });
</script>
</body>
</html>
