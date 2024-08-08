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
    @php
    $introduction = [
        "name" => "Lutreze Hue Jacinto",
        "current_year" => "4th-year",
        "course" => "Information Technology",
        "role" => "Student Developer",
        "skills" => ["HTML", "CSS", "JavaScript", "MySQL", "PHP"],
        "frameworks_i_used" => ["Tailwind", "Laravel"],
        "software_skills" => ["Photoshop", "Adobe Illustrator", "Adobe Lightroom", "Figma"],
        "future_learning_goals" => "MERN stack"
    ];
    
    $skills_list = array_map(fn($skill) => $skill === "CSS" && in_array("Tailwind", $introduction['frameworks_i_used']) ?
    "$skill (including Tailwind)" : $skill, $introduction['skills']);
    
    $formatList = fn($list) => count($list) > 1 ? implode(', ', array_slice($list, 0, -1)) . ' and ' . end($list) : $list[0];
    @endphp
    
    <div>
        <p>
            Hello! My name is {{ $introduction['name'] }}. I'm a {{ $introduction['current_year'] }} 
            {{ $introduction['course'] }} student and a self-taught web developer with experience in PHP 
            frameworks (including {{ $formatList($introduction['frameworks_i_used']) }}).
            I'm constantly learning and expanding my skillset, which currently includes {{ $formatList($skills_list) }}.
        </p>
        
        <p>
            In addition to web development, I'm passionate about design and enjoy using tools like 
            {{ $formatList($introduction['software_skills']) }}. I'm also eager to learn the 
            {{ $introduction['future_learning_goals'] }} and delve into it in the near future.
        </p>
    </div>
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

