<html>
<svg fill="none" viewBox="0 0 600 400" width="600" height="400" xmlns="http://www.w3.org/2000/svg"></svg>
<foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
        <style>
             * {
                margin: 0;
        padding: 0;
        color: inherit;
        text-decoration: none;
        list-style: none;
        outline: none;
        box-sizing: border-box;
    }

    .body {
        --color-main: #ff9b71;
        --color-primary: #ff4444;
        --color-secondary: #e8e677;
        --color-background: #0d1117;
        --color-link: #fef29e;
        --color-link-active: #ff4444;
        height: 400px;
        width: 100%;
        text-transform: uppercase;
        display: flex;
        align-items: center;
        justify-content: center;

        background-image: radial-gradient(var(--color-main), var(--color-primary), var(--color-secondary));
        animation: border 5s linear infinite;
        background-size: 200% 200%;
        background-position: 0 0;
        border: 24px solid;
        border-color: var(--color-background);
      }
      .container {
        background: var(--color-background);
        height: calc(100% - 10px);
        width: calc(100% - 10px);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

h1 {
    font-size: 3.5rem;
    font-weight: 800;
        font-family: "Open Sans", sans-serif;
        text-align: center;
      }
      h1 a {
        display: block;
      }
      h1 a span {
        overflow: hidden;
        transition: transform 0.25s cubic-bezier(0.5, 0, 0.25, 1.25);
        display: block;
      }
      h1 a span em {
        display: block;
      }
      h1 a span:nth-child(1) {
        color: var(--color-main);
        margin-bottom: 6px;
        animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.3) -1s 1;
    }
      h1 a span:nth-child(1) em {
        margin-top: 30px;
        line-height: 0rem;
        margin-bottom: -10px;
    }
      h1 a span:nth-child(2) {
        color: var(--color-primary);
        margin-bottom: 6px;
        animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.2) -0.9s 1;
    }
      h1 a span:nth-child(2) em {
        margin-top: -6px;
        line-height: 1rem;
    }
      h1 a span:nth-child(3) {
        color: var(--color-secondary);
        animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.1) -0.8s 1;
    }
      h1 a span:nth-child(3) em {
        margin-top: -36px;
        line-height: 3rem;
    }
      h1 a:hover span,
      h1 a:focus span {
        transition: transform 0.125s cubic-bezier(0.5, 0, 0.25, 2.5);
      }
      h1 a:hover span:nth-child(1),
      h1 a:focus span:nth-child(1) {
        transform: translateX(1vw);
      }
      h1 a:hover span:nth-child(3),
      h1 a:focus span:nth-child(3) {
        transform: translateX(-1vw);
      }
      .items {
        margin-top: 24px;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
      }
      ul {
        font-size: 16px;
        line-height: 26px;
        color: var(--color-main);
        font-weight: 700;
        font-family: "Open Sans", sans-serif;
      }
      ul li {
        display: flex;
        letter-spacing: 0.125vw;
      }
      ul li a {
        margin-left: 5px;
    }
    ul li a:hover,
      ul li a:focus {
        color: var(--color-link-active);
      }
      ul li a {
        color: var(--color-link);
      }
      .hi {
        display: inline-block;
        transform-origin: 70% 70%;
        animation: hi 3s linear -2s infinite;
    }

@keyframes border {
    0% { background-position: 0 0; }
        20% { background-position: 100% 0; }
        40% { background-position: 100% 100%; }
        60% { background-position: 0 100%; }
        100% { background-position: 0 0; }
    }

@keyframes hi {
    25% { transform: rotate(0deg); }
        30% { transform: rotate(15deg); }
        35% { transform: rotate(0deg); }
        40% { transform: rotate(15deg); }
        45% { transform: rotate(0deg); }
        80% { transform: rotate(0deg); }
        85% { transform: rotate(15deg); }
        90% { transform: rotate(0deg); }
        95% { transform: rotate(15deg); }
        100% { transform: rotate(0deg); }
    }
    @keyframes intro {
        0%, 75% { transform: translateX(-100vw); }
        100% { transform: translateX(0); }
      }

      @keyframes fade {
        0%, 75% { opacity: 0; }
        100% { opacity: 1; }
      }
      @media (prefers-color-scheme: light) {
        .body {
          --color-main: #3300ff;
          --color-primary: #81ecff;
          --color-secondary: #008cff;
          --color-background: #ffffff;
          --color-link: #81ffff;
          --color-link-active: #F15BB5;
        }
      }
      @media (prefers-reduced-motion) {
        .body {
          animation: none;
        }

        .hi {
          animation: none;
        }

        ul li {
            opacity: 1;
            animation: none;
        }

        h1 a span:nth-child(1),
        h1 a span:nth-child(2),
        h1 a span:nth-child(3) {
          animation: none;
        }
      }
    </style>
    <body></body>
    <div class='body'>
        <div class='container'>
            <h1>
                <a href="https://github.com/nikolalsvk">
                  <span><em>nikola đuza</em></span>
                  <span><em>nikola đuza</em></span>
                  <span><em>nikola đuza</em></span>
                </a>
              </h1>
              <section class='items'>
                <ul>
                    <li>Writer &#38; Software Engineer</li>
                </ul>
                <ul>
                    <li>at <a href="https://pragmaticpineapple.com">Pragmatic Pineapple</a></li>
                </ul>
                <ul>
                  <li><a href="mailto:nikolaseap@gmail.com" role="button"><span class='hi'>👋</span></a></li>
                </ul>
              </section>
            </div>
        </div>
      </div>
      </foreignObject>
    </svg>
<h1 align="center">Hi 👋, I'm Sultan Al-Dawsari</h1>
<h3 align="center">Passionate Web Developer | Specializing in Programming and Web Development</h3>




<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/ewew759" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="ewew759" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/sultan-aldawsari-ab5b73277?lipi=urn%3ali%3apage%3ad_flagship3_profile_view_base_contact_details%3b%2btc4khr4sl6xazljjqjqqg%3d%3d" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/sultan-aldawsari-ab5b73277?lipi=urn%3ali%3apage%3ad_flagship3_profile_view_base_contact_details%3b%2btc4khr4sl6xazljjqjqqg%3d%3d" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://dart.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=sultantan353&show_icons=true&locale=en" alt="sultantan353" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=sultantan353&" alt="sultantan353" /></p>
</body>
</html>
