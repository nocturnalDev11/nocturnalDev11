<div align="center">
    <img 
        width="100%" 
        src="https://cdn.jsdelivr.net/gh/nocturnalDev11/nocturnalDev11/MasterHeader_2.gif" 
    />
</div>

<details>
  <summary>
      <h3> About me (Click to expand)</h3>
  </summary>

  ```PHP
  <?php
  
  $introduction = [
      "name" => "Lutreze Hue Jacinto",
      "current_year" => "4th-year",
      "course" => "Information Technology",
      "role" => "Student Developer",
      "skills" => [
          "HTML", "CSS", "JavaScript", "MySQL", "PHP"
      ],
      "frameworks_i_used" => [
          "Tailwind", "Laravel"
      ],
      "software_skills" => [
          "Photoshop", "Adobe Illustrator", "Adobe Lightroom", "Figma"
      ],
      "future_learning_goals" => "MERN stack"
  ];
  
  function introduce_myself($info) {
      $skills = $info['skills'];
      $frameworks = $info['frameworks_i_used'];
      $software = $info['software_skills'];
  
      $skills_list = [];
      foreach ($skills as $skill) {
          if ($skill === "CSS" && in_array("Tailwind", $frameworks)) {
              $skills_list[] = $skill . " (including Tailwind)";
          } else {
              $skills_list[] = $skill;
          }
      }
  
      $skills_list_str = implode(", ", array_slice($skills_list, 0, -1)) . " and " . end($skills_list);
  
      $frameworks_str = implode(", ", array_slice($frameworks, -1));
      $software_str = implode(", ", $software);
  
      echo "Hello! My name is " . $info['name'] . ". I'm a " . $info['current_year'] . " " . $info['course']
      . " student and a self-taught web developer with experience in PHP frameworks (including " 
      . $frameworks_str . "). I'm constantly learning and expanding my skillset, which currently includes " 
      . $skills_list_str . ".<br>";
      
      echo "In addition to web development, I'm passionate about design and enjoy using tools like " 
      . $software_str . ". I'm also eager to learn the " . $info['future_learning_goals'] 
      . " and delve into it in the near future.";
  }
  
  introduce_myself($introduction);
  ?>
````
</details>

### Programming Languages

<div align="left">
  <img src="https://skillicons.dev/icons?i=html" height="40" alt="html5 logo" title="HTML" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=css" height="40" alt="css3 logo" title="CSS"/>
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=js" height="40" alt="javascript logo" title="JavaScript"/>
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=cpp" height="40" alt="cplusplus logo" title="C++" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=py" height="40" alt="python logo" title="Python" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=dart" height="40" alt="dart logo" title="Dart" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=php" height="40" alt="php logo" title="PHP" />
  <img width="12" />
</div>

### Tools and Technologies

<div align="left">
  <img src="https://skillicons.dev/icons?i=laravel" height="40" alt="laravel logo" title="Laravel" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=tailwind" height="40" alt="tailwindcss logo" title="Tailwind Css" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=jquery" height="40" alt="jquery logo" title="JQuery" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=vite" height="40" alt="vite logo" title="Vite" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=flutter" height="40" alt="flutter logo" title="Flutter" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=npm" height="40" alt="npm logo" title="npm" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=androidstudio" height="40" alt="androidstudio logo" title="Android Studio" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=vscode" height="40" alt="vscode logo" title="VS Code" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=visualstudio" height="40" alt="visualstudio logo" title="Visual Studio" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="git logo" title="Git" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ubuntu" height="40" alt="ubuntu logo" title="Ubuntu" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=powershell" height="40" alt="powershell logo" title="Powershell" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=mysql" height="40" alt="mysql logo" title="MySQL" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=firebase" height="40" alt="firebase logo" title="Firebase" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ps" height="40" alt="photoshop logo" title="Photoshop" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=figma" height="40" alt="figma logo" title="Figma" />
  <img width="12" />
</div>

### GitHub Stats 
<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nocturnalDev11&theme=tokyonight" width="100%" height="auto" />
</div>
<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=nocturnalDev11&theme=tokyonight" width="49%" height="auto" style="display: inline;" />
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=nocturnalDev11&theme=tokyonight" width="49%" height="auto" style="display: inline;" />
</div>
<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=nocturnalDev11&theme=tokyonight" width="49%" height="auto" style="display: inline;" />
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=nocturnalDev11&theme=tokyonight&utcOffset=+6.5" width="49%" height="auto" style="display: inline;" />
</div>

<div align="center">
    <img src="https://raw.githubusercontent.com/nocturnalDev11/nocturnalDev11/output/snake.svg" alt="Snake animation" width="100%" height="auto" />
</div>

