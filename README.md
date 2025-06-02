<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Serviços Técnicos Integrados</title>
<style>
  /* Reset */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f0f8ff;
    color: #222;
    line-height: 1.6;
  }
  header {
    background: #007acc;
    color: #fff;
    padding: 20px 10%;
    text-align: center;
    position: relative;
  }
  /* Logo SVG container */
  .logo {
    position: absolute;
    left: 10%;
    top: 50%;
    transform: translateY(-50%);
    width: 50px;
    height: 50px;
  }
  header h1 {
    font-size: 2.5rem;
    margin-bottom: 5px;
  }
  header p {
    font-size: 1.2rem;
  }
  section {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 15px;
  }
  h2 {
    color: #007acc;
    margin-bottom: 20px;
    font-size: 2rem;
    border-bottom: 3px solid #007acc;
    display: inline-block;
    padding-bottom: 5px;
  }
  .services {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 20px;
  }
  .service {
    flex: 1 1 280px;
    background: #e6f2ff;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 6px rgba(0, 122, 204, 0.3);
    transition: transform 0.3s ease;
    text-align: center;
  }
  .service:hover {
    transform: translateY(-5px);
  }
  .service h3 {
    margin: 15px 0;
    color: #005999;
  }
  /* Service SVG icons */
  .service svg {
    width: 80px;
    height: 80px;
    fill: #007acc;
  }
  form {
    background: #e6f2ff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 122, 204, 0.2);
    max-width: 500px;
    margin: 0 auto 60px auto;
  }
  form label {
    display: block;
    margin-bottom: 6px;
    font-weight: 600;
  }
  form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 4px;
    border: 1px solid #aaa;
    font-size: 1rem;
    resize: vertical;
  }
  form button {
    background: #007acc;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 5px;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  form button:hover {
    background: #005999;
  }
  /* Map */
  .map-container {
    max-width: 900px;
    margin: 0 auto 60px auto;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
  }
  iframe {
    width: 100%;
    height: 350px;
    border: none;
  }
  /* Footer */
  footer {
    background: #007acc;
    color: white;
    text-align: center;
    padding: 20px 10%;
    font-size: 1rem;
  }
  /* Social Icons */
  .social-icons {
    margin-top: 10px;
  }
  .social-icons a {
    color: white;
    margin: 0 12px;
    text-decoration: none;
    font-size: 1.6rem;
    transition: color 0.3s ease;
  }
  .social-icons a:hover {
    color: #ffd700;
  }
  /* Responsive */
  @media (max-width: 650px) {
    .services {
      flex-direction: column;
    }
    header {
      padding-left: 15%;
      position: relative;
    }
    .logo {
      position: relative;
      left: auto;
      top: auto;
      transform: none;
      margin-bottom: 10px;
      width: 60px;
      height: 60px;
    }
  }
</style>
<!-- Font Awesome CDN for social icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

<header>
  <div class="logo" aria-label="Logo Serviços Técnicos">
    <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" >
      <!-- Lightning bolt (eletricidade) -->
      <polygon points="22 2 10 30 26 30 18 62 42 24 28 24 36 2" fill="#ffd700"/>
      <!-- Gear (informática) -->
      <circle cx="48" cy="40" r="10" stroke="#007acc" stroke-width="3" fill="none" />
      <path fill="#007acc" d="M48 30v4l3 3-3 3v4h-2v-4l-3-3 3-3v-4h2z" />
    </svg>
  </div>
  <h1>Serviços Técnicos Integrados</h1>
  <p>Eletricidade | Informática | Administração de Redes e Sistemas</p>
</header>

<section id="about">
  <h2>Sobre Nós</h2>
  <p>Somos uma equipe especializada em soluções técnicas que facilitam o seu dia a dia. Oferecemos serviços de alta qualidade nas áreas de eletricidade, informática e administração de redes e sistemas, garantindo eficiência, segurança e suporte personalizado.</p>
</section>

<section id="services">
  <h2>Serviços</h2>
  <div class="services">
    <div class="service" aria-label="Serviço Eletricidade">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <polygon points="22 2 10 30 26 30 18 62 42 24 28 24 36 2" />
      </svg>
      <h3>Eletricidade</h3>
      <p>Instalações residenciais e comerciais, manutenção elétrica, sistemas de iluminação, cabeamento e soluções de energia sustentável.</p>
    </div>
    <div class="service" aria-label="Serviço Informática">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="12" y="14" width="40" height="36" rx="4" ry="4" stroke-width="3" stroke="#007acc" fill="none" />
        <circle cx="32" cy="46" r="4" fill="#007acc" />
        <rect x="24" y="18" width="16" height="8" fill="#007acc" />
      </svg>
      <h3>Informática</h3>
      <p>Suporte técnico, reparos em hardware e software, configuração de computadores, backup de dados e recuperação de sistemas.</p>
    </div>
    <div class="service" aria-label="Serviço Administração de Redes e Sistemas">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <circle cx="32" cy="32" r="14" stroke="#007acc" stroke-width="3" fill="none"/>
        <path d="M32 18v-6M32 46v-6M46 32h6M18 32h6M44.5 19.5l4.5-4.5M15.5 44.5l4.5-4.5M44.5 44.5l4.5 4.5M15.5 19.5l4.5 4.5" stroke="#007acc" stroke-width="3"/>
      </svg>
      <h3>Administração de Redes e Sistemas</h3>
      <p>Configuração e monitoramento de redes, segurança da informação, servidores, manutenção preventiva e suporte remoto.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contato</h2>
  <form id="contactForm" onsubmit="return handleSubmit(event)" aria-label="Formulário de contato">
    <label for="name">Nome</label>
    <input type="text" id="name" name="name" required placeholder="Seu nome" />

    <label for="email">Email</label>
    <input type="email" id="email" name="email" required placeholder="seuemail@exemplo.com" />

    <label for="message">Mensagem</label>
    <textarea id="message" name="message" rows="5" required placeholder="Escreva sua mensagem aqui..."></textarea>

    <button type="submit">Enviar</button>
  </form>
</section>

<section id="location">
  <h2>Localização</h2>
  <div class="map-container" aria-label="Mapa de localização">
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12003.98293319391!2d35.55367113642602!3d-25.066927425465122!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1ee21d2b03ae1f83%3A0xd96e6913aef9e1ef!2sChongoene!5e0!3m2!1spt-BR!2smz!4v1696299936829!5m2!1spt-BR!2smz"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
      title="Mapa da localização">
    </iframe>
  </div>
</section>

<footer>
  <p>&copy; 2025 Serviços Técnicos Integrados - Todos os direitos reservados</p>
  <div class="social-icons" aria-label="Redes sociais">
    <a href="https://www.facebook.com" target="_blank" rel="noopener" aria-label="Facebook">
      <i class="fab fa-facebook"></i>
    </a>
    <a href="https://www.linkedin.com" target="_blank" rel="noopener" aria-label="LinkedIn">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://www.instagram.com" target="_blank" rel="noopener" aria-label="Instagram">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="https://wa.me/258867517682" target="_blank" rel="noopener" aria-label="WhatsApp">
      <i class="fab fa-whatsapp"></i>
    </a>
  </div>
</footer>

<script>
  function handleSubmit(event) {
    event.preventDefault();
    alert('Obrigado por entrar em contato! Responderemos em breve.');
    document.getElementById('contactForm').reset();
    return false;
  }
</script>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Serviços Técnicos Integrados</title>
<style>
  /* Reset */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #f0f8ff;
    color: #222;
    line-height: 1.6;
  }
  header {
    background: #007acc;
    color: #fff;
    padding: 20px 10%;
    text-align: center;
    position: relative;
  }
  /* Logo SVG container */
  .logo {
    position: absolute;
    left: 10%;
    top: 50%;
    transform: translateY(-50%);
    width: 50px;
    height: 50px;
  }
  header h1 {
    font-size: 2.5rem;
    margin-bottom: 5px;
  }
  header p {
    font-size: 1.2rem;
  }
  section {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 15px;
  }
  h2 {
    color: #007acc;
    margin-bottom: 20px;
    font-size: 2rem;
    border-bottom: 3px solid #007acc;
    display: inline-block;
    padding-bottom: 5px;
  }
  .services {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 20px;
  }
  .service {
    flex: 1 1 280px;
    background: #e6f2ff;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 6px rgba(0, 122, 204, 0.3);
    transition: transform 0.3s ease;
    text-align: center;
  }
  .service:hover {
    transform: translateY(-5px);
  }
  .service h3 {
    margin: 15px 0;
    color: #005999;
  }
  /* Service SVG icons */
  .service svg {
    width: 80px;
    height: 80px;
    fill: #007acc;
  }
  form {
    background: #e6f2ff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 122, 204, 0.2);
    max-width: 500px;
    margin: 0 auto 60px auto;
  }
  form label {
    display: block;
    margin-bottom: 6px;
    font-weight: 600;
  }
  form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 4px;
    border: 1px solid #aaa;
    font-size: 1rem;
    resize: vertical;
  }
  form button {
    background: #007acc;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 5px;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  form button:hover {
    background: #005999;
  }
  /* Map */
  .map-container {
    max-width: 900px;
    margin: 0 auto 60px auto;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
  }
  iframe {
    width: 100%;
    height: 350px;
    border: none;
  }
  /* Footer */
  footer {
    background: #007acc;
    color: white;
    text-align: center;
    padding: 20px 10%;
    font-size: 1rem;
  }
  /* Social Icons */
  .social-icons {
    margin-top: 10px;
  }
  .social-icons a {
    color: white;
    margin: 0 12px;
    text-decoration: none;
    font-size: 1.6rem;
    transition: color 0.3s ease;
  }
  .social-icons a:hover {
    color: #ffd700;
  }
  /* Responsive */
  @media (max-width: 650px) {
    .services {
      flex-direction: column;
    }
    header {
      padding-left: 15%;
      position: relative;
    }
    .logo {
      position: relative;
      left: auto;
      top: auto;
      transform: none;
      margin-bottom: 10px;
      width: 60px;
      height: 60px;
    }
  }
</style>
<!-- Font Awesome CDN for social icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

<header>
  <div class="logo" aria-label="Logo Serviços Técnicos">
    <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" >
      <!-- Lightning bolt (eletricidade) -->
      <polygon points="22 2 10 30 26 30 18 62 42 24 28 24 36 2" fill="#ffd700"/>
      <!-- Gear (informática) -->
      <circle cx="48" cy="40" r="10" stroke="#007acc" stroke-width="3" fill="none" />
      <path fill="#007acc" d="M48 30v4l3 3-3 3v4h-2v-4l-3-3 3-3v-4h2z" />
    </svg>
  </div>
  <h1>Serviços Técnicos Integrados</h1>
  <p>Eletricidade | Informática | Administração de Redes e Sistemas</p>
</header>

<section id="about">
  <h2>Sobre Nós</h2>
  <p>Somos uma equipe especializada em soluções técnicas que facilitam o seu dia a dia. Oferecemos serviços de alta qualidade nas áreas de eletricidade, informática e administração de redes e sistemas, garantindo eficiência, segurança e suporte personalizado.</p>
</section>

<section id="services">
  <h2>Serviços</h2>
  <div class="services">
    <div class="service" aria-label="Serviço Eletricidade">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <polygon points="22 2 10 30 26 30 18 62 42 24 28 24 36 2" />
      </svg>
      <h3>Eletricidade</h3>
      <p>Instalações residenciais e comerciais, manutenção elétrica, sistemas de iluminação, cabeamento e soluções de energia sustentável.</p>
    </div>
    <div class="service" aria-label="Serviço Informática">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="12" y="14" width="40" height="36" rx="4" ry="4" stroke-width="3" stroke="#007acc" fill="none" />
        <circle cx="32" cy="46" r="4" fill="#007acc" />
        <rect x="24" y="18" width="16" height="8" fill="#007acc" />
      </svg>
      <h3>Informática</h3>
      <p>Suporte técnico, reparos em hardware e software, configuração de computadores, backup de dados e recuperação de sistemas.</p>
    </div>
    <div class="service" aria-label="Serviço Administração de Redes e Sistemas">
      <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <circle cx="32" cy="32" r="14" stroke="#007acc" stroke-width="3" fill="none"/>
        <path d="M32 18v-6M32 46v-6M46 32h6M18 32h6M44.5 19.5l4.5-4.5M15.5 44.5l4.5-4.5M44.5 44.5l4.5 4.5M15.5 19.5l4.5 4.5" stroke="#007acc" stroke-width="3"/>
      </svg>
      <h3>Administração de Redes e Sistemas</h3>
      <p>Configuração e monitoramento de redes, segurança da informação, servidores, manutenção preventiva e suporte remoto.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contato</h2>
  <form id="contactForm" onsubmit="return handleSubmit(event)" aria-label="Formulário de contato">
    <label for="name">Nome</label>
    <input type="text" id="name" name="name" required placeholder="Seu nome" />

    <label for="email">Email</label>
    <input type="email" id="email" name="email" required placeholder="seuemail@exemplo.com" />

    <label for="message">Mensagem</label>
    <textarea id="message" name="message" rows="5" required placeholder="Escreva sua mensagem aqui..."></textarea>

    <button type="submit">Enviar</button>
  </form>
</section>

<section id="location">
  <h2>Localização</h2>
  <div class="map-container" aria-label="Mapa de localização">
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12003.98293319391!2d35.55367113642602!3d-25.066927425465122!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1ee21d2b03ae1f83%3A0xd96e6913aef9e1ef!2sChongoene!5e0!3m2!1spt-BR!2smz!4v1696299936829!5m2!1spt-BR!2smz"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
      title="Mapa da localização">
    </iframe>
  </div>
</section>

<footer>
  <p>&copy; 2025 Serviços Técnicos Integrados - Todos os direitos reservados</p>
  <div class="social-icons" aria-label="Redes sociais">
    <a href="https://www.facebook.com" target="_blank" rel="noopener" aria-label="Facebook">
      <i class="fab fa-facebook"></i>
    </a>
    <a href="https://www.linkedin.com" target="_blank" rel="noopener" aria-label="LinkedIn">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://www.instagram.com" target="_blank" rel="noopener" aria-label="Instagram">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="https://wa.me/258867517682" target="_blank" rel="noopener" aria-label="WhatsApp">
      <i class="fab fa-whatsapp"></i>
    </a>
  </div>
</footer>

<script>
  function handleSubmit(event) {
    event.preventDefault();
    alert('Obrigado por entrar em contato! Responderemos em breve.');
    document.getElementById('contactForm').reset();
    return false;
  }
</script>

</body>
</html>

</body>
</html>
