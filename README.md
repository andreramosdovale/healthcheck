# HealthCheck

**Acompanhe sua evolução corporal de forma simples, visual e segura.**

## Visão Geral

O **HealthCheck** é uma aplicação web que permite a qualquer pessoa registrar e acompanhar sua evolução corporal utilizando o método das 7 dobras de Pollock. O sistema é intuitivo, educativo e prioriza a privacidade do usuário, com estrutura pronta para futuras funcionalidades premium.

---

## Funcionalidades Principais (MVP)

- **Cadastro e Login:** Crie sua conta com email e senha, faça login seguro e recupere sua senha via email. Cada usuário acessa apenas seus próprios dados.
- **Onboarding Educativo:** Tutorial rápido sobre como medir corretamente as 7 dobras e a importância do acompanhamento corporal.
- **Registro das Medições:** Formulário simples para inserir as 7 dobras (tricipital, subescapular, peitoral, axilar média, supra-ilíaca, abdominal, coxa), peso, altura, sexo, idade e data da medição. Validação básica dos campos.
- **Cálculo Automático:** Percentual de gordura e composição corporal calculados automaticamente após cada registro, com explicação simples dos resultados.
- **Visualização da Evolução:** Gráficos interativos mostrando a evolução do percentual de gordura ao longo do tempo, com destaque visual para tendências (melhora, piora, estabilidade).
- **Histórico de Medições:** Listagem fácil das medições anteriores, com possibilidade de editar ou excluir registros.
- **Feedback Imediato:** Mensagem motivacional ou comparativo com a última medição após cada registro, incluindo sinalização visual de evolução (ex: setas/vermelho-verde).
- **Estrutura para Monetização:** Plano gratuito com limite básico e tela explicando as diferenças entre planos. Estrutura pronta para integração com gateway de pagamento.
- **Exportação Simples:** Botão para exportar histórico em CSV (pode ser restrito ao plano pago).
- **Notificações Básicas:** Lembrete por email para nova medição (opcional) e confirmações de cadastro/recuperação de senha.
- **Privacidade e Segurança:** Mensagem clara sobre proteção dos dados pessoais e opção de exclusão de conta pelo usuário.

---

## Tecnologias Utilizadas

- [Next.js](https://nextjs.org/) – Framework React para aplicações web modernas
- [TypeScript](https://www.typescriptlang.org/) – Tipagem estática para maior segurança
- [Tailwind CSS](https://tailwindcss.com/) – Estilização rápida e responsiva
- [Recharts](https://recharts.org/) – Visualização de gráficos
- [NextAuth.js](https://next-auth.js.org/) – Autenticação segura

---

## Como Rodar Localmente

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/healthcheck.git
   cd healthcheck
   ```

2. **Instale as dependências:**

   ```bash
   npm install
   # ou
   yarn install
   ```

3. **Configure as variáveis de ambiente:**

   - Crie um arquivo `.env.local` baseado em `.env.example` e preencha as informações necessárias (ex: conexão com backend, chaves de autenticação, etc).

4. **Inicie o servidor de desenvolvimento:**

   ```bash
   npm run dev
   # ou
   yarn dev
   ```

5. Acesse [http://localhost:3000](http://localhost:3000) no seu navegador.

---

## Roadmap

1. Cadastro/login e onboarding educativo
2. Registro das medições + cálculo automático
3. Visualização da evolução (gráficos) + histórico
4. Feedback imediato + notificações básicas
5. Estrutura para monetização + exportação simples
6. Privacidade e exclusão de conta
