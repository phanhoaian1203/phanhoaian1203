<!-- HEADER SECTION -->
<div align="center">
  <h1>Phan Hoài An</h1>
  <p><strong>FPT University Da Nang | Backend Software Engineer (.NET & C#)</strong></p>
  
  <p align="center">
    <a href="https://linkedin.com/in/phanhoaian1203" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:anph.dev@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://facebook.com/phanhoaian1203" target="_blank">
      <img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook" />
    </a>
  </p>
</div>

<br />

<!-- CODELANDING / PERSONALIZED IDENTITY -->
```csharp
// PhanHoaiAn.cs
using System;
using System.Threading.Tasks;

namespace DeveloperProfile
{
    public class PhanHoaiAn : BackendDeveloper
    {
        public string Education   => "FPT University Da Nang 🎓";
        public string PrimaryCore => "C# / .NET Core / ASP.NET Web API";
        public string Frontend    => "TypeScript / React.js";
        public string Databases   => "SQL Server & PostgreSQL";
        public string DevOps      => "Docker & GitHub Actions CI/CD";

        public async Task EngineeringGoalAsync()
        {
            await ImplementCleanArchitectureAsync();
            await BuildScalableServicesAsync();
            await ContainerizeAndAutomateAsync();
        }
    }
}
```

---

## 🌟 Professional Blueprint & Philosophy

As a software engineering student at **FPT University Da Nang**, I specialize in building highly scalable, performant backend architectures while bridging the gap to the client layer using modern frontend technologies. I believe software engineering is about crafting reliable systems, automating workflows, and writing self-documenting code.

- 🛠️ **System Mindset:** Writing code with SOLID principles, design patterns, and clean architecture.
- 🐳 **Automation First:** Streamlining deployment via multi-stage Docker builds and automated CI/CD pipelines.
- ⚡ **Performance & Quality:** Designing optimal SQL queries and database schemas for quick execution.

---

## 📊 Tech Stack System Architecture

Unlike generic lists, here is how my technical skills connect and interact within a production system architecture:

```mermaid
graph TD
    %% Custom Styles
    classDef client fill:#1f2937,stroke:#3178C6,stroke-width:2px,color:#fff;
    classDef backend fill:#1f2937,stroke:#512BD4,stroke-width:2px,color:#fff;
    classDef db fill:#1f2937,stroke:#316192,stroke-width:2px,color:#fff;
    classDef devops fill:#1f2937,stroke:#2496ED,stroke-width:2px,color:#fff;

    Client["🎨 TypeScript & React.js <br> Modern, Type-Safe UI"]:::client
    API["💻 ASP.NET Core API <br> Clean Architecture & CQRS"]:::backend
    EF["⚡ Entity Framework Core <br> ORM Data Mapping"]:::backend
    DB["🗄️ SQL Server & PostgreSQL <br> Optimized Storage"]:::db
    Docker["🐳 Docker Packaging <br> Lightweight Containerization"]:::devops
    CICD["🔄 GitHub Actions CI/CD <br> Automation & Pipelines"]:::devops

    Client -->|RESTful HTTP requests| API
    API --> EF
    EF -->|Data Persistence| DB
    Docker -.->|Containers| API
    CICD -.->|Automates| Docker
```

---

## 🛠️ Technical Stack & Tools

* **Languages & Core:** 
  ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
  ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

* **Backend & Web Frameworks:**
  ![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
  ![Entity Framework Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
  ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

* **Databases & Infrastructure:**
  ![Microsoft SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

* **DevOps & Developer Tools:**
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
  ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
  ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visual-studio&logoColor=white)
  ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

---

## 📁 Featured Projects

| Project Name | Scope & System Architecture | Core Tech Stack | Repo Link |
| :--- | :--- | :--- | :---: |
| **🚀 Enterprise E-Commerce API** | High-performance REST API incorporating Clean Architecture, CQRS pattern, and secure JWT authentication. | `.NET 8`, `EF Core`, `SQL Server`, `Docker` | [📂 View Repo](https://github.com/phanhoaian1203) |
| **🎨 Management Control Center** | Client-side dashboard focusing on type-safe components, structured state, and smooth UI/UX workflows. | `React`, `TypeScript`, `Tailwind CSS`, `PostgreSQL` | [📂 View Repo](https://github.com/phanhoaian1203) |
| **🔄 Automated Deployment Pipeline** | Automated CI/CD workflow packaging lightweight multi-stage Docker builds onto live servers. | `Docker`, `GitHub Actions`, `Linux` | [📂 View Repo](https://github.com/phanhoaian1203) |

---

## 📊 System Metrics & Analytics

<div align="center">
  <table border="0" cellpadding="0" cellspacing="0">
    <tr>
      <td>
        <a href="https://github.com/phanhoaian1203">
          <img src="https://github-readme-stats.vercel.app/api?username=phanhoaian1203&show_icons=true&include_all_commits=true&theme=transparent&title_color=007acc&text_color=adbac7&icon_color=007acc&hide_border=true" alt="Phan Hoài An's GitHub Stats" height="180" />
        </a>
      </td>
      <td>
        <a href="https://github.com/phanhoaian1203">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=phanhoaian1203&layout=compact&theme=transparent&title_color=007acc&text_color=adbac7&icon_color=007acc&hide_border=true&langs_count=6" alt="Top Languages" height="180" />
        </a>
      </td>
    </tr>
  </table>
  
  <br />
  
  <a href="https://github.com/phanhoaian1203">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=phanhoaian1203&theme=transparent&hide_border=true&stroke=007acc&ring=007acc&fire=007acc&currStreakLabel=007acc" alt="Phan Hoài An's GitHub Streak" />
  </a>
  
  <br /><br />
  
  <!-- VISITOR COUNTER -->
  <img src="https://komarev.com/ghpvc/?username=phanhoaian1203&color=007acc&style=flat-square&label=PROFILE+VIEWS" alt="Visitor Counter" />
</div>
