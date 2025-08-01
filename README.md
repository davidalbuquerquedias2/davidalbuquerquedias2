<style>
  /* Animação fade-in suave */
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* Aplica fade-in em todos os elementos com essa classe */
  .fade-in {
    animation: fadeIn 1s ease forwards;
    opacity: 0;
  }

  /* Delays para cascata */
  .fade-in.delay-1 { animation-delay: 0.3s; }
  .fade-in.delay-2 { animation-delay: 0.6s; }
  .fade-in.delay-3 { animation-delay: 0.9s; }

  /* Efeito hover suave para ícones */
  .tech-icons img {
    transition: transform 0.3s ease, filter 0.3s ease;
    cursor: pointer;
  }

  .tech-icons img:hover {
    transform: scale(1.2) rotate(10deg);
    filter: drop-shadow(0 0 6px #6c63ff);
  }

  /* Botões sociais também ganham hover */
  .social-links a img {
    transition: transform 0.3s ease, filter 0.3s ease;
  }

  .social-links a img:hover {
    transform: scale(1.1);
    filter: drop-shadow(0 0 5px #0a66c2);
  }

  /* Centralizar texto e melhorar espaçamento */
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #121212;
    color: #eee;
    margin: 20px;
  }

  h1, h3 {
    color: #6c63ff;
  }

  p {
    max-width: 600px;
    margin: 10px auto;
    line-height: 1.5;
  }
</style>

<h1 align="center" class="fade-in delay-1">Welcome to my profile!💪🏻</h1>

<h3 align="center" class="fade-in delay-2">👩‍💻  About Me</h3>
<p class="fade-in delay-3">Estudante de Análise e Desenvolvimento de Sistemas e apaixonado por resolver problemas com código. Comecei minha jornada há 8 meses e, desde então, mergulhei no mundo da programação com curiosidade e disciplina.</p>
<p class="fade-in delay-3">Hoje, meu foco é em front-end — HTML, CSS e JavaScript são minhas ferramentas preferidas. Mas o que realmente me move é entender como as coisas funcionam por trás da tela e como melhorar códigos que não estão indo bem.</p>
<p class="fade-in delay-3">Busco um estágio para continuar aprendendo na prática, crescer com gente boa e contribuir com projetos reais.</p>

<h3 align="center" class="fade-in delay-2">🛠 Techs</h3>

<div align="center" class="tech-icons fade-in delay-3" style="display: flex; justify-content: center; align-items: center; gap: 12px;">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5 logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3 logo" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" height="40" alt="JavaScript logo" />
</div>

<div align="center" class="social-links fade-in delay-3" style="margin-top: 10px; display: flex; justify-content: center; gap: 10px;">
  <a href="https://www.instagram.com/davi_dalbuquerqueof/?hl=pt-br" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://www.linkedin.com/in/david-dias-712ba7361" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</div>
