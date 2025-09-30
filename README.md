# <p align="center">💻 Raul Aragall Taberner 📈
<p align="center">
 Raul Aragall Taberner <!-- follower-counter -->2438<!-- /follower-counter --> followers
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Animación de Nombre</title>
  <style>
    #nombre {
      font-size: 2em;
      font-family: monospace;
      white-space: pre;
    }
  </style>
</head>
<body>
  <div id="nombre"></div>
  <script>
    const texto = "Tu Nombre"; // Cambia esto por el nombre que quieras
    const elemento = document.getElementById('nombre');
    let idx = 0;
    let modo = 'escribir';

    function animar() {
      if (modo === 'escribir') {
        if (idx <= texto.length) {
          elemento.textContent = texto.slice(0, idx);
          idx++;
          setTimeout(animar, 150);
        } else {
          modo = 'borrar';
          setTimeout(animar, 700);
        }
      } else if (modo === 'borrar') {
        if (idx >= 0) {
          elemento.textContent = texto.slice(0, idx);
          idx--;
          setTimeout(animar, 80);
        } else {
          modo = 'escribir';
          setTimeout(animar, 700);
        }
      }
    }

    animar();
  </script>
</body>
</html>
<p align="center">
<br/>
<a href="https://www.linkedin.com/in/erwinlejeune-lkn">
  <img alt="guilyx's LinkdeIN" width="50px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" />
</a>
<a href="https://open.spotify.com/user/11147618695?si=zZFn6uAGRLyoU02lsG50GA">
  <img alt="guilyx's Spotify" width="50px" src="https://user-images.githubusercontent.com/43545812/144035120-1ad5169b-91c7-4078-bef9-6a82c733f373.png" />
</a>
<br>
</p>

<p align="center">
  <img alig src="https://github-profile-trophy.vercel.app/?username=guilyx&theme=onedark&column=-1" />
</p>

[![activity graph](https://github-readme-activity-graph.vercel.app/graph?username=guilyx&theme=github-dark-dimmed&custom_title=Guilyx%20Activity%20Graph&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

```yaml
Name: Raul Aragall Taberner
Located in: Valencia, España
From: Valencia (España)
Currently: Estudiante Master IA en EDEM
Education: ADE en la UPV


🌞 Morning                915 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   09.52 % 
🌆 Daytime                3940 commits        ██████████░░░░░░░░░░░░░░░   40.99 % 
🌃 Evening                3572 commits        █████████░░░░░░░░░░░░░░░░   37.17 % 
🌙 Night                  1184 commits        ███░░░░░░░░░░░░░░░░░░░░░░   12.32 % 
```




<!--END_SECTION:waka-simple-->

Liked it ?

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer"/>
</p>