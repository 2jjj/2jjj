# Pedro Sakamoto

```console
root@2jjj:~# whoami
pedro sakamoto — desenvolvedor back-end — ribeirão preto, br
cursando engenharia da computação na unaerp
```

Construo back-end e coloco em produção. **Node.js**, **Go** e **PostgreSQL** no dia a dia, com TypeScript e React quando a interface precisa existir. Gosto da parte que não aparece no print: modelagem de dados, integração de pagamento, fila, teste automatizado e o deploy que não quebra.

Três sistemas meus estão rodando agora: um bot de vendas no WhatsApp para uma loja de artigos marciais, um SaaS de gestão de importações com checkout e conciliação e um dashboard que busca vagas e organiza candidaturas. Todos com case study público — arquitetura, decisões e o que deu errado no caminho.

📍 Ribeirão Preto, SP &nbsp;·&nbsp; 💼 Aberto a estágio e posição júnior &nbsp;·&nbsp; 🌎 Remoto ou presencial

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-sakamoto-3b94091a1/)
[![Portfólio](https://img.shields.io/badge/pedrosakamoto.site-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.pedrosakamoto.site)
[![Currículo](https://img.shields.io/badge/Curr%C3%ADculo-PDF-1F6FEB?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://www.pedrosakamoto.site/curriculo/curriculo-pedro-sakamoto.pdf)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedrosakamoto27@gmail.com)

---

## Em produção

| Sistema | O que resolve | Stack |
|---|---|---|
| [**Kamikaze Bot**](https://www.pedrosakamoto.site/projetos/kamikaze-bot) | Vendas por WhatsApp para loja de artes marciais. Catálogo de **219 produtos e 568 variações** sincronizado da loja real, pedido do "oi" até o registro, painel com inbox, Kanban e métricas. **63 testes** automatizados. | `TypeScript` `Node.js` `SQLite` `Playwright` |
| [**ImportFlow**](https://www.pedrosakamoto.site/projetos/importflow) | SaaS de gestão de importações. **2 gateways** de pagamento (Stripe com cartão, Pix e boleto, e InfinitePay), webhooks assinados, conciliação, painel admin e provisionamento de usuário. | `React` `TypeScript` `Supabase` `Edge Functions` |
| [**StartANewDay**](https://www.pedrosakamoto.site/projetos/startanewday) | Dashboard que agrega **4 fontes** de vagas, calcula compatibilidade com o perfil e organiza candidaturas. Automação de navegador com Playwright e API em Express. | `Node.js` `Express` `Playwright` `React` |

## Stack

| Área | O que uso |
|---|---|
| Back-end | Node.js, Express, Go, APIs REST |
| Dados | PostgreSQL, SQLite, modelagem relacional, migrações |
| Front-end | React, TypeScript, Vite, Tailwind |
| Qualidade | Vitest, testes de integração, lint, CI no GitHub Actions |
| Infra | Docker, Vercel, Supabase, GitHub Actions |
| Segurança | recon, engenharia reversa defensiva, análise de PE, YARA/Sigma |

```bash
$ ls ~/arsenal
node  go  postgres  docker  python  ghidra  wireshark  burp
```

## Projetos abertos

| Projeto | Descrição | Stack |
|---|---|---|
| [**reconkit**](https://github.com/2jjj/reconkit) | Toolkit de recon para bug bounty e testes autorizados: subdomínios, port scan com banner, HTTP probe, headers, caça a segredos e fingerprinting. Sem dependência externa. | `Python` |
| [**cron-help**](https://github.com/2jjj/cron-help) | CLI que traduz expressão cron para texto em português e lista as próximas execuções. | `JavaScript` |
| [**gofetch**](https://github.com/2jjj/gofetch) | Cliente HTTP em Go sem dependências, com retry, backoff exponencial e rate limit. | `Go` |
| [**prism**](https://github.com/2jjj/prism) | Extrai a paleta dominante de uma imagem e exporta em hex, JSON, CSS ou Tailwind. | `Python` |
| [**use-debounce**](https://github.com/2jjj/use-debounce) | Hooks React: debounce, throttle, debounced callback, interval e timeout. | `TypeScript` |
| [**treino-seguro-60**](https://github.com/2jjj/treino-seguro-60) | Página de vendas e guia em PDF para um programa de treino de força para maiores de 60 anos. | `HTML` |
| [**detoxdigital**](https://github.com/2jjj/detoxdigital) | Back-end Spring Boot e extensão do Chrome que mede tempo em sites distrativos e avisa quando voltar ao foco. | `Java` |
| [**BadgesPlus**](https://github.com/2jjj/BadgesPlus) | Plugin para Vesktop/Vencord com badges de perfil e busca de membros por badge, com instalador automático. | `TypeScript` |

## Segurança

Entrei por curiosidade e ficou: leio binário, mapeio superfície e escrevo detecção. Já analisei um stealer real (PE empacotado com PyInstaller, C2 via Discord, injeção com `CreateRemoteThread`) em ambiente isolado e publiquei o reporte defensivo com regras **YARA** e **Sigma** e script de remediação.

Só em escopo autorizado — CTF, lab próprio e programa de bug bounty. Divulgação responsável, sempre.

## Trajetória

- **Engenharia da Computação** na Unaerp — em andamento.
- **3 anos** à frente de uma loja de artigos de alto padrão: produto, atendimento, vendas e a parte técnica, tudo junto. Foi onde aprendi que sistema bom é o que aguenta o dia inteiro de cliente de verdade.
- Programo desde 2021. Comecei por bot de Discord, passei por ferramenta interna e cheguei em produto com pagamento e estoque.

## Contato

- 📧 [pedrosakamoto27@gmail.com](mailto:pedrosakamoto27@gmail.com)
- 💼 [linkedin.com/in/pedro-sakamoto-3b94091a1](https://www.linkedin.com/in/pedro-sakamoto-3b94091a1/)
- 🌐 [pedrosakamoto.site](https://www.pedrosakamoto.site) · [currículo em PDF](https://www.pedrosakamoto.site/curriculo/curriculo-pedro-sakamoto.pdf) · [código do site](https://github.com/2jjj/portfolio)
