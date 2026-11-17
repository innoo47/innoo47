<!-- 다크/라이트 모드에 따라 자동으로 바뀌는 애니메이션 헤더 (assets/ 안의 직접 만든 SVG) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg">
  <img alt="innoo47 terminal" src="./assets/header-dark.svg" width="100%">
</picture>

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,mysql,react,js,git,github,idea,notion&perline=9" />
</p>

---

### 🧩 Dev in — Architecture

> 개발하다 막힐 때, 묻고 답하는 개발자 Q&A 커뮤니티 · 팀장 / 메인 · 관리자 페이지 담당

```mermaid
flowchart LR
    U([👤 User]) --> FE["⚛️ React<br/>Main · MyPage · Admin"]
    FE -- "REST + JWT 🔐" --> BE["🍃 Spring Boot API"]
    BE --> AUTH{{"JWT Filter<br/>Access / Refresh"}}
    BE --> DB[(🐬 MySQL)]
    BE --> ADM["🛡️ Admin<br/>신고 처리 · 회원 관리"]
    style FE fill:#61dafb22,stroke:#61dafb
    style BE fill:#6db33f22,stroke:#6db33f
    style DB fill:#4479a122,stroke:#4479a1
    style AUTH fill:#a78bfa22,stroke:#a78bfa
    style ADM fill:#f472b622,stroke:#f472b6
```

<p align="right"><a href="https://github.com/likelion-backendschool-11st/basic-project-3team">→ repository</a></p>

---

### 📅 Contribution in 3D

<!-- GitHub Actions(lowlighter/metrics)가 매일 자동 생성 -->
<p align="center">
  <img src="./metrics.isocalendar.svg" width="100%" alt="isometric contribution calendar" />
</p>

<details>
<summary><b>🐍 more — snake eating my contributions</b></summary>
<br/>

<!-- GitHub Actions(Platane/snk)가 매일 자동 생성 → output 브랜치 -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/innoo47/innoo47/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/innoo47/innoo47/output/github-snake.svg">
  <img alt="snake" src="https://raw.githubusercontent.com/innoo47/innoo47/output/github-snake.svg">
</picture>

</details>

<details>
<summary><b>🎮 off-duty</b></summary>
<br/>

`FC Online` · `League of Legends` · `PUBG` · `MapleStory`

</details>
