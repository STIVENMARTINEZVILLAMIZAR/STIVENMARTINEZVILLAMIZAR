<style>
  @keyframes fall {
    0% { transform: translateY(-10vh); opacity: 1; }
    100% { transform: translateY(100vh); opacity: 0; }
  }
  
  @keyframes flicker {
    0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% { opacity: 1; }
    20%, 24%, 55% { opacity: 0.5; }
  }
  
  .hacker-header {
    position: relative;
    width: 100%;
    min-height: 250px;
    height: clamp(200px, 35vw, 300px);
    background: #000000;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    border-bottom: 3px solid #00FF00;
    box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
    padding: 20px;
    box-sizing: border-box;
  }
  
  .code-rain {
    position: absolute;
    width: 100%;
    height: 100%;
    font-family: 'Courier New', monospace;
    font-size: clamp(12px, 2vw, 18px);
    color: #00FF00;
    opacity: 0.1;
    white-space: pre-wrap;
    word-break: break-all;
    overflow: hidden;
    pointer-events: none;
    animation: flicker 3s infinite;
  }
  
  .falling-code {
    position: absolute;
    color: #00FF00;
    font-family: 'Courier New', monospace;
    font-size: clamp(10px, 1.5vw, 14px);
    opacity: 0.6;
    pointer-events: none;
    white-space: nowrap;
  }
  
  .header-text {
    position: relative;
    z-index: 10;
    font-size: clamp(28px, 8vw, 48px);
    font-weight: bold;
    color: #00FF00;
    text-shadow: 0 0 10px #00FF00, 0 0 20px #00FF00;
    letter-spacing: 2px;
    font-family: 'Courier New', monospace;
    animation: flicker 2s infinite;
    text-align: center;
    margin: 0;
  }
  
  @media (max-width: 768px) {
    .hacker-header {
      height: clamp(180px, 40vw, 250px);
      padding: 15px;
    }
    
    .header-text {
      letter-spacing: 1px;
    }
  }
  
  @media (max-width: 480px) {
    .hacker-header {
      height: clamp(150px, 45vw, 200px);
      padding: 10px;
      border-bottom-width: 2px;
    }
    
    .header-text {
      letter-spacing: 0.5px;
    }
    
    .code-rain {
      font-size: clamp(10px, 1.5vw, 14px);
    }
    
    .falling-code {
      font-size: clamp(9px, 1.2vw, 12px);
    }
  }
</style>

<div class="hacker-header">
  <div class="code-rain">
int main() { return 0; }
if (x > 10) { console.log("hack"); }
while(true) { printf("🎮"); }
for(let i=0; i<∞; i++) { code++; }
const hack = () => { penetrate(); };
sudo rm -rf /
git commit -m "exploit"
SELECT * FROM passwords;
buffer_overflow();
  </div>
  
  <div class="header-text">¡WELCOME! 👨‍💻</div>
  
  <script>
    // Crear líneas de código cayendo
    const header = document.querySelector('.hacker-header');
    const codes = ['01010110', '01001001', '00001010', 'function hack()', 'while(1)', 'console.log()', 'git push -f', 'sudo su'];
    
    setInterval(() => {
      const code = codes[Math.floor(Math.random() * codes.length)];
      const falling = document.createElement('div');
      falling.className = 'falling-code';
      falling.textContent = code;
      falling.style.left = Math.random() * 100 + '%';
      falling.style.animationDuration = (Math.random() * 3 + 2) + 's';
      falling.style.animation = `fall ${Math.random() * 3 + 2}s linear forwards`;
      header.appendChild(falling);
      
      setTimeout(() => falling.remove(), 5000);
    }, 300);
  </script>
</div>

<h1 align="center">👨‍💻 Stiven Martínez Villamizar</h1>

<p align="center">
  <img src="./media/stiven.jpg" alt="" width="220" style="border-radius: 50%; box-shadow: 0 0 25px #1E90FF;"/>
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