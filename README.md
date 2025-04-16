# 👋 Hello, I'm Dohun!

A backend developer passionate about building scalable systems & game servers.  
Currently focusing on cloud-native architecture and real-time systems with C# & .NET.

---

[![Solved.ac 프로필](http://mazassumnida.wtf/api/generate_badge?boj=vbn930)](https://solved.ac/vbn930)
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=vbn930)](https://github.com/anuraghazra/github-readme-stats)

# 💪 Skills

### ⚙Languages & Runtime
- C#, Python, C++, C
- .NET 8, ASP.NET Core, Entity Framework

### Cloud & DevOps
- Microsoft Azure (Key Vault, Container App, ACR, Cosmos DB)
- Docker, GitHub Actions, OpenTelemetry

### Backend Engineering
- REST API, Middleware Architecture, API Security (API Key, RBAC)
- In-Memory Caching, Stateless Design, Dependency Injection
- Microservices & Service-to-Service Authentication

### Game Server Design
- Real-time gameplay logic
- Game state management with persistence strategies
- Battle system, Level scaling, Map generation, Reward logic

### Distributed Systems & Telemetry
- Distributed tracing with OpenTelemetry
- Performance optimization through cache-first reads
- Multi-layer architecture (Gateway → Game Service → DB)

# 🚀 Projects

### Discord-Based Text RPG Server  
A microservices-based text RPG game designed for Discord.  
Users play through DMs using command buttons with real-time API interaction.

- Built using **.NET 8**, **Discord.NET**, **Azure Container Apps**
- Designed with **microservices architecture**, separating Discord service and game state service
- Implemented **API Key authentication** middleware with **Azure Key Vault + In-Memory Cache**
- Cached game data to memory to minimize Cosmos DB I/O for performance (reduced response time: 200ms → 1–2ms)
- Included **OpenTelemetry tracing** for distributed diagnostics across services
- Deployed via **GitHub Actions CI/CD**, automatically pushing Docker images to Azure Container Registry

**Tech Stack:** `.NET 8`, `Discord.NET`, `Azure Key Vault`, `Cosmos DB`, `Docker`, `OpenTelemetry`, `GitHub Actions`

🔗 [View on GitHub](https://github.com/Dungeon-RPG-Discord-Game-Server)

# :mailbox_with_mail: Contacts
[![LinkedIn Badge](http://img.shields.io/badge/-LinkedIn-003D8F?style=flat-square&logo=github&link=https://soo-vely-dev.tistory.com/)](https://www.linkedin.com/in/dohun-lee-304971313/)
[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:kimsh1691@gmail.com)](mailto:vbn9302@gmail.com)
[![Naver Badge](https://img.shields.io/badge/Naver-03C75A?style=flat-square&logo=Naver&logoColor=white&link=mailto:rlatngus1691@naver.com)](mailto:vbn930@naver.com)
