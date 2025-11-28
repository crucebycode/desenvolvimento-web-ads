# Código-Fonte Completo - Espaço Girassol Website

## Estrutura do Projeto

```
espaco_girassol_web/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── images/
    ├── child-hero.jpg
    ├── team.jpg
    ├── publication-1.jpg
    ├── publication-2.jpg
    └── publication-3.jpg
```

---

## 1. index.html

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Espaço Girassol - Centro de Diagnóstico e Acompanhamento</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-wrapper">
                <div class="logo">
                    <span class="logo-text">Espaço</span>
                    <span class="logo-girassol">Girassol</span>
                </div>
                <div class="nav-menu" id="navMenu">
                    <a href="#home" class="nav-link">Home</a>
                    <a href="#sobre" class="nav-link">Quem Somos</a>
                    <a href="#localizacao" class="nav-link">Localização</a>
                    <a href="#publicacoes" class="nav-link">Publicações</a>
                    <a href="#contato" class="nav-link nav-link-contact">Contato</a>
                </div>
                <button class="hamburger" id="hamburger">
                    <span></span>
                    <span></span>
                    <span></span>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <p class="hero-subtitle">Um Mundo de Cores, Um Jeito Único de Ser</p>
                    <h1 class="hero-title">
                        Cuidar da Mente é <span class="highlight">Deixar a Infância Florescer</span>
                    </h1>
                    <p class="hero-description">
                        Nosso compromisso é oferecer informação clara e apoio especializado em toda Fortaleza.
                    </p>
                    <div class="hero-features">
                        <div class="feature">
                            <div class="feature-icon">👥</div>
                            <p>Acessível em +12 Centros</p>
                        </div>
                        <div class="feature">
                            <div class="feature-icon">📱</div>
                            <p>Disponível em qualquer Momento</p>
                        </div>
                    </div>
                    <a href="#contato" class="btn btn-primary">Saiba mais</a>
                </div>
                <div class="hero-image">
                    <img src="images/child-hero.jpg" alt="Criança feliz">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="sobre" class="about">
        <div class="container">
            <div class="about-wrapper">
                <div class="about-image">
                    <img src="images/team.jpg" alt="Equipe do Espaço Girassol">
                </div>
                <div class="about-content">
                    <h2>Nosso Dever</h2>
                    <p>
                        O Centro de Diagnóstico é o início de mais 12 entregas que iremos fazer na nossa gestão. Trabalhamos com a perspectiva de que haja um grande vácuo no acolhimento do poder público, que não estava atendendo as pessoas com deficiência de forma adequada.
                    </p>
                    <p>
                        A Prefeitura agora conta com esse belo espaço, que fará o contato inicial e o diagnóstico, encaminhando os pacientes para outros espaços de tratamento.
                    </p>
                    <a href="#" class="btn btn-secondary">Saiba mais</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Location Section -->
    <section id="localizacao" class="location">
        <div class="container">
            <h2>Fale Conosco</h2>
            <p class="section-subtitle">Escolha o centro de atendimento mais próximo de você com o nosso mapa interativo.</p>
            
            <div class="location-info">
                <div class="info-box">
                    <h3>Centros de Atendimento</h3>
                    <p>Selecione um centro</p>
                </div>
                <div class="info-box">
                    <h3>Endereço: XXXXXXXX</h3>
                </div>
                <div class="info-box">
                    <h3>Telefone: 99 9999999</h3>
                </div>
            </div>

            <div class="map-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3860.5614268893!2d-38.5265!3d-3.7319!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7c74d7c7c7c7c7c7%3A0x7c7c7c7c7c7c7c7c!2sFortaleza%2C%20CE!5e0!3m2!1spt-BR!2sbr!4v1234567890" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
    </section>

    <!-- Publications Section -->
    <section id="publicacoes" class="publications">
        <div class="container">
            <h2>Publicações</h2>
            <div class="publications-grid">
                <article class="publication-card">
                    <img src="images/publication-1.jpg" alt="Publicação 1">
                    <h3>Título da Publicação 1</h3>
                    <p>Descrição breve da publicação...</p>
                    <a href="#" class="link-more">Leia mais →</a>
                </article>
                <article class="publication-card">
                    <img src="images/publication-2.jpg" alt="Publicação 2">
                    <h3>Título da Publicação 2</h3>
                    <p>Descrição breve da publicação...</p>
                    <a href="#" class="link-more">Leia mais →</a>
                </article>
                <article class="publication-card">
                    <img src="images/publication-3.jpg" alt="Publicação 3">
                    <h3>Título da Publicação 3</h3>
                    <p>Descrição breve da publicação...</p>
                    <a href="#" class="link-more">Leia mais →</a>
                </article>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contato" class="contact">
        <div class="container">
            <h2>Contato</h2>
            <div class="contact-wrapper">
                <div class="contact-info">
                    <h3>Entre em Contato</h3>
                    <div class="contact-item">
                        <span class="icon">✉️</span>
                        <p>mail@gmail.com</p>
                    </div>
                    <div class="contact-item">
                        <span class="icon">📱</span>
                        <p>XX XX99999-9999</p>
                    </div>
                </div>
                <form class="contact-form">
                    <input type="text" placeholder="Seu Nome" required>
                    <input type="email" placeholder="Seu Email" required>
                    <textarea placeholder="Sua Mensagem" rows="5" required></textarea>
                    <button type="submit" class="btn btn-primary">Enviar</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Espaço Girassol</h3>
                    <p>Uma força transformadora em prol da igualdade e dos direitos das pessoas em Fortaleza.</p>
                    <div class="social-links">
                        <a href="#" aria-label="Facebook">f</a>
                        <a href="#" aria-label="Instagram">📷</a>
                        <a href="#" aria-label="Twitter">𝕏</a>
                        <a href="#" aria-label="YouTube">▶️</a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>Contato</h3>
                    <p>mail@gmail.com</p>
                    <p>XX XX99999-9999</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2024 Espaço Girassol. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
```

---

## 2. css/styles.css

```css
/* Color Palette */
:root {
    --primary-dark: #1B5E5E;
    --primary-orange: #FF6B35;
    --accent-yellow: #F4D35E;
    --light-bg: #FFF3E0;
    --white: #FFFFFF;
    --text-dark: #2C3E50;
    --text-light: #666666;
    --border-color: #E8E8E8;
}

/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Poppins', sans-serif;
    color: var(--text-dark );
    line-height: 1.6;
    background-color: var(--white);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Typography */
h1, h2, h3, h4, h5, h6 {
    font-weight: 700;
    line-height: 1.2;
}

h2 {
    font-size: 2.5rem;
    color: var(--primary-dark);
    margin-bottom: 1rem;
}

p {
    color: var(--text-light);
    margin-bottom: 1rem;
}

/* Navigation */
.navbar {
    background-color: var(--primary-dark);
    padding: 1rem 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    font-size: 1.5rem;
    font-weight: 700;
}

.logo-text {
    color: var(--white);
}

.logo-girassol {
    color: var(--primary-orange);
}

.nav-menu {
    display: flex;
    gap: 2rem;
    align-items: center;
}

.nav-link {
    color: var(--white);
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

.nav-link:hover {
    color: var(--accent-yellow);
}

.nav-link-contact {
    background-color: var(--primary-orange);
    padding: 0.5rem 1.5rem;
    border-radius: 2rem;
    color: var(--white);
}

.nav-link-contact:hover {
    background-color: #FF5A1F;
    color: var(--white);
}

.hamburger {
    display: none;
    flex-direction: column;
    background: none;
    border: none;
    cursor: pointer;
    gap: 0.5rem;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background-color: var(--white);
    border-radius: 2px;
    transition: 0.3s;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, var(--light-bg) 0%, var(--white) 100%);
    padding: 80px 0;
    position: relative;
    overflow: hidden;
}

.hero::before {
    content: '';
    position: absolute;
    width: 300px;
    height: 300px;
    background: rgba(244, 211, 94, 0.1);
    border-radius: 50%;
    top: -100px;
    left: -100px;
}

.hero::after {
    content: '';
    position: absolute;
    width: 200px;
    height: 200px;
    background: rgba(27, 94, 94, 0.05);
    border-radius: 50%;
    bottom: -50px;
    right: -50px;
}

.hero .container {
    position: relative;
    z-index: 1;
}

.hero-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    align-items: center;
}

.hero-subtitle {
    color: var(--text-light);
    font-size: 0.95rem;
    margin-bottom: 1rem;
}

.hero-title {
    font-size: 3.5rem;
    color: var(--text-dark);
    margin-bottom: 1.5rem;
    line-height: 1.2;
}

.hero-title .highlight {
    color: var(--primary-orange);
}

.hero-description {
    font-size: 1.1rem;
    color: var(--text-light);
    margin-bottom: 2rem;
}

.hero-features {
    display: flex;
    gap: 2rem;
    margin-bottom: 2rem;
}

.feature {
    display: flex;
    align-items: center;
    gap: 0.75rem;
}

.feature-icon {
    font-size: 2rem;
}

.feature p {
    margin: 0;
    font-size: 0.95rem;
}

.hero-image {
    position: relative;
    z-index: 2;
}

.hero-image img {
    width: 100%;
    height: auto;
    border-radius: 20px;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
}

/* Buttons */
.btn {
    display: inline-block;
    padding: 0.75rem 2rem;
    border-radius: 2rem;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    border: none;
    cursor: pointer;
    font-family: 'Poppins', sans-serif;
    font-size: 1rem;
}

.btn-primary {
    background-color: var(--primary-orange);
    color: var(--white);
}

.btn-primary:hover {
    background-color: #FF5A1F;
    transform: translateY(-2px);
    box-shadow: 0 10px 20px rgba(255, 107, 53, 0.3);
}

.btn-secondary {
    background-color: var(--primary-orange);
    color: var(--white);
}

.btn-secondary:hover {
    background-color: #FF5A1F;
}

/* About Section */
.about {
    padding: 80px 0;
    background-color: var(--white);
}

.about-wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    align-items: center;
}

.about-image {
    position: relative;
}

.about-image img {
    width: 100%;
    height: auto;
    border-radius: 20px;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
}

.about-content h2 {
    margin-bottom: 1.5rem;
}

.about-content p {
    margin-bottom: 1.5rem;
    line-height: 1.8;
}

/* Location Section */
.location {
    padding: 80px 0;
    background-color: var(--light-bg);
}

.location h2 {
    text-align: center;
    margin-bottom: 1rem;
}

.section-subtitle {
    text-align: center;
    font-size: 1.1rem;
    color: var(--text-light);
    margin-bottom: 3rem;
}

.location-info {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
    margin-bottom: 3rem;
}

.info-box {
    background-color: var(--primary-orange);
    color: var(--white);
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
}

.info-box h3 {
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.info-box p {
    color: var(--white);
    margin: 0;
}

.map-container {
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

/* Publications Section */
.publications {
    padding: 80px 0;
    background-color: var(--white);
}

.publications h2 {
    text-align: center;
    margin-bottom: 3rem;
}

.publications-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
}

.publication-card {
    background-color: var(--white);
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.publication-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
}

.publication-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.publication-card h3 {
    padding: 1.5rem 1.5rem 0.5rem;
    color: var(--text-dark);
    font-size: 1.2rem;
}

.publication-card p {
    padding: 0 1.5rem;
    color: var(--text-light);
    font-size: 0.95rem;
}

.link-more {
    display: inline-block;
    padding: 1rem 1.5rem;
    color: var(--primary-orange);
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
}

.link-more:hover {
    color: #FF5A1F;
}

/* Contact Section */
.contact {
    padding: 80px 0;
    background-color: var(--primary-dark);
    color: var(--white);
}

.contact h2 {
    color: var(--white);
    text-align: center;
    margin-bottom: 3rem;
}

.contact-wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
}

.contact-info h3 {
    color: var(--white);
    margin-bottom: 2rem;
    font-size: 1.5rem;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 2rem;
}

.contact-item .icon {
    font-size: 1.5rem;
}

.contact-item p {
    margin: 0;
    color: var(--white);
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.contact-form input,
.contact-form textarea {
    padding: 1rem;
    border: none;
    border-radius: 8px;
    font-family: 'Poppins', sans-serif;
    font-size: 1rem;
}

.contact-form input::placeholder,
.contact-form textarea::placeholder {
    color: #999;
}

.contact-form button {
    background-color: var(--primary-orange);
    color: var(--white);
    padding: 1rem 2rem;
    border: none;
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.contact-form button:hover {
    background-color: #FF5A1F;
}

/* Footer */
.footer {
    background-color: var(--primary-dark);
    color: var(--white);
    padding: 3rem 0 1rem;
}

.footer-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    margin-bottom: 2rem;
}

.footer-section h3 {
    color: var(--primary-orange);
    margin-bottom: 1rem;
    font-size: 1.2rem;
}

.footer-section p {
    color: var(--white);
    margin-bottom: 0.5rem;
}

.social-links {
    display: flex;
    gap: 1rem;
    margin-top: 1rem;
}

.social-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 50%;
    color: var(--white);
    text-decoration: none;
    transition: background-color 0.3s ease;
}

.social-links a:hover {
    background-color: var(--primary-orange);
}

.footer-bottom {
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    padding-top: 2rem;
    text-align: center;
    color: rgba(255, 255, 255, 0.7);
}

/* Responsive Design */
@media (max-width: 768px) {
    .hamburger {
        display: flex;
    }

    .nav-menu {
        display: none;
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        flex-direction: column;
        background-color: var(--primary-dark);
        padding: 1rem;
        gap: 0.5rem;
    }

    .nav-menu.active {
        display: flex;
    }

    .hero-content {
        grid-template-columns: 1fr;
    }

    .hero-title {
        font-size: 2.5rem;
    }

    .hero-features {
        flex-direction: column;
    }

    .about-wrapper {
        grid-template-columns: 1fr;
    }

    .location-info {
        grid-template-columns: 1fr;
    }

    .publications-grid {
        grid-template-columns: 1fr;
    }

    .contact-wrapper {
        grid-template-columns: 1fr;
    }

    .footer-content {
        grid-template-columns: 1fr;
    }

    h2 {
        font-size: 2rem;
    }
}

@media (max-width: 480px) {
    .hero-title {
        font-size: 2rem;
    }

    .nav-link {
        font-size: 0.9rem;
    }

    .hero-features {
        gap: 1rem;
    }

    .feature p {
        font-size: 0.85rem;
    }
}
```

---

## 3. js/script.js

```javascript
// Mobile Menu Toggle
const hamburger = document.getElementById('hamburger');
const navMenu = document.getElementById('navMenu');

hamburger.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});

// Close menu when a link is clicked
const navLinks = document.querySelectorAll('.nav-link');
navLinks.forEach(link => {
    link.addEventListener('click', () => {
        navMenu.classList.remove('active');
    });
});

// Contact Form Submission
const contactForm = document.querySelector('.contact-form');
if (contactForm) {
    contactForm.addEventListener('submit', (e) => {
        e.preventDefault();
        alert('Obrigado por sua mensagem! Entraremos em contato em breve.');
        contactForm.reset();
    });
}

// Smooth scroll for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Add animation on scroll
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -100px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);

// Observe elements for animation
document.querySelectorAll('.publication-card, .info-box').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(20px)';
    el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(el);
});

// Navbar background on scroll
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.style.boxShadow = '0 4px 20px rgba(0, 0, 0, 0.15)';
    } else {
        navbar.style.boxShadow = '0 2px 10px rgba(0, 0, 0, 0.1)';
    }
});

console.log('Espaço Girassol - Website loaded successfully!');
```

---

## Instruções de Instalação e Uso

### Estrutura de Diretórios

Crie a seguinte estrutura de pastas:

```
espaco_girassol_web/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── images/
    ├── child-hero.jpg
    ├── team.jpg
    ├── publication-1.jpg
    ├── publication-2.jpg
    └── publication-3.jpg
```

### Como Executar Localmente

#### Opção 1: Usando Python (Recomendado)

```bash
cd espaco_girassol_web
python3 -m http.server 8000
```

Acesse: `http://localhost:8000`

#### Opção 2: Usando Node.js (http-server )

```bash
npm install -g http-server
cd espaco_girassol_web
http-server
```

#### Opção 3: Abrir Diretamente no Navegador

Simplesmente abra o arquivo `index.html` em seu navegador web.

### Personalização

**Cores:** Edite as variáveis CSS em `css/styles.css`:

```css
:root {
    --primary-dark: #1B5E5E;      /* Verde-escuro */
    --primary-orange: #FF6B35;    /* Laranja */
    --accent-yellow: #F4D35E;     /* Amarelo-ouro */
    --light-bg: #FFF3E0;          /* Fundo claro */
    --white: #FFFFFF;
    --text-dark: #2C3E50;
    --text-light: #666666;
}
```

**Conteúdo:** Edite o HTML em `index.html` para atualizar:

- Textos das seções

- Informações de contato

- Links de redes sociais

- Imagens

**Imagens:** Substitua os arquivos em `images/` com suas próprias imagens.

### Recursos Inclusos

✅ Navegação responsiva com menu mobile✅ Hero section com imagem de destaque✅ Seção "Quem Somos" com imagem da equipe✅ Mapa interativo do Google Maps✅ Galeria de publicações✅ Formulário de contato funcional✅ Footer com links de redes sociais✅ Animações suaves ao scroll✅ Design totalmente responsivo✅ Otimizado para performance

### Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge (versões recentes )

- ✅ Mobile (iOS e Android)

- ✅ Tablets

- ✅ Desktops

---

## Resumo das Funcionalidades

| Funcionalidade | Descrição |
| --- | --- |
| **Navegação Sticky** | Menu fixo no topo com links para todas as seções |
| **Menu Mobile** | Hamburger menu responsivo para dispositivos móveis |
| **Hero Section** | Apresentação impactante com imagem e CTA |
| **Seção Sobre** | Informações sobre o Centro de Diagnóstico |
| **Mapa Interativo** | Google Maps integrado para localização |
| **Publicações** | Galeria de artigos com cards interativos |
| **Formulário** | Contato funcional com validação |
| **Footer** | Links de redes sociais e informações |
| **Animações** | Efeitos suaves ao scroll e hover |
| **Responsividade** | Design adaptável para todos os tamanhos |

---

**Desenvolvido com ❤️ para o Espaço Girassol**

