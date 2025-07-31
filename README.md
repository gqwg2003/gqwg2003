<style>
  .animated-badge {
    transition: all 0.3s ease;
    animation: pulse 2s infinite;
  }
  
  .animated-badge:hover {
    transform: scale(1.1) rotate(2deg);
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  }
  
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
  }
  
  .animated-divider {
    height: 4px;
    background: linear-gradient(90deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4, #feca57, #ff9ff3, #54a0ff);
    background-size: 200% 100%;
    animation: gradientShift 3s ease infinite;
    border-radius: 2px;
    margin: 20px 0;
  }
  
  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  .skill-bar {
    background: linear-gradient(90deg, #0969DA, #4ecdc4);
    background-size: 200% 100%;
    animation: skillAnimation 2s ease-in-out infinite;
    height: 10px;
    border-radius: 5px;
    transition: all 0.3s ease;
  }
  
  .skill-bar:hover {
    transform: scaleY(1.2);
    box-shadow: 0 2px 4px rgba(9, 105, 218, 0.3);
  }
  
  @keyframes skillAnimation {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  .animated-title {
    background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4);
    background-size: 300% 300%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: titleGradient 4s ease infinite;
  }
  
  @keyframes titleGradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
</style>

<table align="center">
  <tr>
    <td colspan="5"><h3 align="center" class="animated-title">💼 Уверенно владею</h3></td>
  </tr>
  <tr align="center">
    <td>
      <img class="animated-badge" src="https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
    </td>
    <td>
      <img class="animated-badge" src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    </td>
    <td>
      <img class="animated-badge" src="https://img.shields.io/badge/-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td colspan="5"><h3 align="center" class="animated-title">🌱 Активно изучаю</h3></td>
  </tr>
  <tr align="center">
    <td>
      <img class="animated-badge" src="https://img.shields.io/badge/-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
    </td>
    <td>
      <img class="animated-badge" src="https://img.shields.io/badge/-C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
    </td>
  </tr>
</table>

<div align="center">
  <div class="animated-divider"></div>
</div>

## <img src="https://media.giphy.com/media/1ynCEtlgMPAeNAqdnu/giphy.gif" width="25"> Языки общения

<div align="center">
  <table style="border:none; border-collapse: separate; border-spacing: 15px;" align="center">
    <tr>
      <td align="right" width="180"><h3>🇷🇺 Русский</h3></td>
      <td align="left" width="300">
        <div style="display: flex; align-items: center;">
          <div class="skill-bar" style="width: 250px;"></div>
          <span style="margin-left: 10px; font-weight: bold; color: #0969DA;">100%</span>
        </div>
      </td>
    </tr>
    <tr>
      <td align="right" width="180"><h3>🇬🇧 Английский</h3></td>
      <td align="left" width="300">
        <div style="display: flex; align-items: center;">
          <div class="skill-bar" style="width: 185px; background: linear-gradient(90deg, #0969DA 74%, #E0E0E0 74%);"></div>
          <span style="margin-left: 10px; font-weight: bold; color: #0969DA;">74%</span>
        </div>
      </td>
    </tr>
  </table>
</div>

<div align="center">
  <div class="animated-divider"></div>
</div>
