# SC Software (Soares & Carvalho)

Bem-vindo à organização **SC Software**.

Nossa missão é desenvolver soluções inovadoras para o setor da **construção civil**. Estamos construindo softwares robustos para transformar o gerenciamento de obras, faturas e processos construtivos.

> 🚧 **Em Desenvolvimento**: Nossas soluções estão em constante evolução para atender às demandas do futuro da construção.

## 🎯 Pilares da Organização

Nossos projetos estão divididos em três áreas principais de atuação:

- **Plataforma Web (Frontend)**: Interfaces modernas, responsivas e intuitivas para gestão e visualização de dados de obras.
- **Serviços de Backend**: APIs escaláveis e seguras que garantem a integridade das regras de negócio e processamento de dados.
- **Infraestrutura e DevOps**: Automação de deploy e gerenciamento de ambientes em nuvem.

## 🛠️ Stack Tecnológica

Utilizamos um conjunto moderno de tecnologias para garantir performance e manutenibilidade:

### Backend

- **Core**: .NET 8 (C#)
- **Banco de Dados**: SQL Server, Entity Framework Core
- **Arquitetura**: RESTful API, Docker Support

### Frontend

- **Framework**: Vue 3 (Composition API)
- **Build Tool**: Vite
- **Estilização**: Tailwind CSS v4
- **Estado Global**: Pinia

### Infraestrutura

- **Cloud**: Amazon Web Services (AWS EC2)
- **Containerização**: Docker & Docker Compose
- **S.O.**: Amazon Linux / Ubuntu

## 📂 Estrutura dos Repositórios

Aqui está uma visão geral de como nosso código está organizado:

| Repositório                 | Descrição                                                                                                                      |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **`elp-building-backend`**  | O núcleo da nossa aplicação. Contém a API, lógica de negócios, migrações de banco de dados e scripts de seed.                  |
| **`elp-building-frontend`** | O painel administrativo e interface do usuário. Inclui funcionalidades de leitura de QR Code, gráficos e gestão de documentos. |
| **`elp-infrastructure`**    | Scripts de automação, guias de setup de servidores (EC2) e configurações de ambiente.                                          |

> _Nota: Detalhes técnicos específicos de instalação e execução podem ser encontrados no `README.md` de cada repositório individual._

## 🤝 Como Contribuir

Ficamos felizes com o interesse em contribuir para a SC Software! Para começar:

1. **Escolha um Repositório**: Navegue até o projeto que deseja contribuir.
2. **Leia o README Local**: Cada projeto possui instruções específicas de "Quick Start" (ex: `make fullrun` no backend ou `npm run dev` no frontend).
3. **Padrões de Código**:
   - Backend: Seguimos as convenções padrão do .NET e Clean Architecture.
   - Frontend: Utilizamos ESLint e Prettier para manter a consistência.
4. **Abra um Pull Request**: Descreva claramente suas alterações e o problema que elas resolvem.

---

_SC Software - Inovando para o futuro da construção._

