<style>
  @keyframes hologram-glow {
    0%, 100% { 
      filter: drop-shadow(0 0 10px #00FF00) drop-shadow(0 0 20px #00FF00);
      transform: scale(1);
    }
    50% { 
      filter: drop-shadow(0 0 20px #00FF00) drop-shadow(0 0 30px #00FF00) drop-shadow(0 0 40px #0099FF);
      transform: scale(1.05);
    }
  }
  
  @keyframes float-up {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-15px); }
  }
  
  .hacker-header-simple {
    position: relative;
    width: 100%;
    height: 300px;
    background: #000000;
    display: flex;
    align-items: center;
    justify-content: space-around;
    overflow: hidden;
    border-bottom: 3px solid #00FF00;
    box-shadow: 0 0 30px rgba(0, 255, 0, 0.3);
    margin: 20px auto;
    padding: 20px;
    box-sizing: border-box;
  }
  
  .welcome-text {
    font-size: clamp(32px, 8vw, 56px);
    font-weight: bold;
    color: #00FF00;
    text-shadow: 0 0 10px #00FF00, 0 0 20px #00FF00;
    font-family: 'Courier New', monospace;
    letter-spacing: 3px;
    animation: float-up 3s ease-in-out infinite;
    flex: 1;
    text-align: center;
  }
  
  .hologram-profile {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    background: radial-gradient(circle at 30% 30%, rgba(0, 255, 0, 0.3), rgba(0, 0, 0, 0.8));
    box-shadow: 0 0 30px #00FF00, inset 0 0 30px rgba(0, 255, 0, 0.2);
    animation: hologram-glow 3s ease-in-out infinite, float-up 3s ease-in-out infinite;
    overflow: hidden;
    border: 3px solid #00FF00;
    flex-shrink: 0;
  }
  
  .hologram-profile img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter: brightness(1.1) contrast(1.2);
  }
  
  @media (max-width: 768px) {
    .hacker-header-simple {
      height: 250px;
      flex-direction: column;
      gap: 20px;
    }
    
    .welcome-text {
      order: 1;
    }
    
    .hologram-profile {
      order: 2;
      width: 150px;
      height: 150px;
    }
  }
</style>

<div class="hacker-header-simple">
  <div class="welcome-text">¡WELCOME!</div>
  <div class="hologram-profile">
    <img src="./media/stiven.png" alt="Stiven Martinez"/>
  </div>
</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Courier+New&size=20&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&width=600&height=60&lines=int%20main()%20%7B%20return%200%3B%20%7D;if%20(x%20%3E%2010)%20%7B%20hack()%3B%20%7D;while(true)%20%7B%20code()%3B%20%7D;01010110%2001001001%2000001010" alt="hacking code rain"/>
</p>

<p align="center">
  <em>
    Desarrollador de Software | Apasionado por la programación, el aprendizaje constante y los retos tecnológicos.
  </em>
</p>

---

###  Sobre mí  

Soy **Stiven Martínez Villamizar**, tengo **20 años** y soy un apasionado por la programación y el desarrollo de software.  
Desde que descubrí este mundo, la tecnología se convirtió en mi forma de expresarme, de crear y de superar cada reto que se presenta.  

Durante mi formación en **Desarrollo de Software** en las **Unidades Tecnológicas de Santander (UTS)**, he fortalecido mis bases en **lógica de programación, estructuras de datos y desarrollo web**, aprendiendo a transformar ideas en soluciones reales.  

He complementado mi aprendizaje con **cursos prácticos e intensivos en Campuslands**, donde enfrenté proyectos exigentes que me ayudaron a mejorar mis habilidades técnicas, mi capacidad para trabajar en equipo y mi mentalidad de crecimiento continuo.  

Actualmente manejo diversos **lenguajes de programación**, comandos de **terminal** y **control de versiones con Git**, y sigo ampliando mis conocimientos en **frameworks y nuevas tecnologías**.  

Me considero una persona **disciplinada, curiosa y perseverante**, siempre en busca de aprender algo nuevo y de dejar una huella positiva a través del código.  
Mi objetivo es continuar creciendo como desarrollador, creando proyectos que inspiren e impacten de forma real.

---

### 💡 Tecnologías y herramientas

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,nodejs,mysql,git,linux,vscode" />
</p>

---

### 🌐 Conecta conmigo

<div align="center">
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
  <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="discord logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitch logo"  />
  <img src="https://img.shields.io/static/v1?message=dev.to&logo=dev.to&label=&color=0A0A0A&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="devto logo"  />
</div>

---

### 📈 En constante crecimiento

> _“El aprendizaje no tiene fin, y cada error es una oportunidad para mejorar.”_

---

<p align="center">
  🚀 <strong>Gracias por visitar mi perfil. ¡El código es mi forma de crear futuro!</strong> 💻
</p>

---

<!-- 🎮 Pacman contribution graph -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/STIVENMARTINEZVILLAMIZAR/STIVENMARTINEZVILLAMIZAR/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/STIVENMARTINEZVILLAMIZAR/STIVENMARTINEZVILLAMIZAR/output/pacman-contribution-graph.svg">
    <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/STIVENMARTINEZVILLAMIZAR/STIVENMARTINEZVILLAMIZAR/output/pacman-contribution-graph.svg">
  </picture>
</p>