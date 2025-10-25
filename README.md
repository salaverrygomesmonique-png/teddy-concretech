# API c/ Nest + React + TypeScript + Vite + TypeORM + Postgres + Docker
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

O projeto respeita os principios da Well-architecture da AWS, com padrões REST, e metodologia SOLID, TDD/DDD.

1) Quanto tempo disponibilizariamos para a criação da aplicação?
   
Não há um número fixo de sprints para construir uma aplicação em microsserviços, pois a quantidade varia muito dependendo de diversos fatores. Ao invés de ser um processo único, é um esforço contínuo de design, desenvolvimento e refatoração. A agilidade da abordagem em microsserviços permite que o desenvolvimento e as entregas aconteçam em um ritmo sustentável e adaptável. 

2) Quantos desenvolvedores seriam necessários para a costrução da aplicação?

Equipes que visam a entrega contínua podem ter sprints curtos, mas contínuos, com diversas implantações por dia. 
Pelo menos 1 Fullstack, 1 Backend, 1 analista de testes ou Devops

3) Qual a senioridade dos desenvolvedores?

Equipes com mais experiência em arquitetura de microsserviços podem estimar e executar as tarefas de forma mais eficiente. O ideal seria contar com desenvolvedores pleno e senior. 

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.


## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

TypeScript é uma linguagem tipada estaticamente que é um superconjunto estrito da sintaxe do JavaScript. Oferece segurança de tipo aprimorada e suporte a ferramentas, tornando-se uma escolha popular para projetos de maior escala.

Nest é um framework para construir aplicações eficientes e escaláveis no lado do servidor com Node.js. Ele fornece uma estrutura e uma gama de recursos que facilitam o desenvolvimento e o teste de aplicações.

Postgres é um poderoso sistema de gerenciamento de banco de dados relacional de código aberto que é bem adequado para estruturas de dados complexas e processamento de dados em grande escala.

TypeORM é uma ferramenta de Mapeamento Objeto-Relacional (ORM) de código aberto que fornece uma maneira de interagir com bancos de dados relacionais como MySQL, PostgreSQL e SQLite. Ajuda você a escrever código relacionado a banco de dados usando programação orientada a objetos em TypeScript ou JavaScript, em vez de escrever instruções SQL brutas. O TypeORM oferece muitos recursos, como gerenciamento de transações, migrações de banco de dados, pooling de conexões, etc., que facilitam o trabalho com bancos de dados em suas aplicações.

Docker é uma plataforma de contêineres que facilita o deploy e a execução de aplicações em diferentes ambientes. Vamos lançar um banco de dados Postgres e serviço de suporte no docker.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.



Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
