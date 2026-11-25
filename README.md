# Projeto Orbi — MVP

**Integrantes:** Giovanna e Marcos  
**Tecnologias:** HTML5, CSS3 e JavaScript (sem framework)  
**Tipo:** MVP acadêmico front-end

## Sobre o projeto
O Orbi é uma plataforma demonstrativa de aprendizagem pessoal. A proposta é ajudar o usuário a transformar curiosidade em aprendizado contínuo por meio de interesses, conteúdos curtos e acompanhamento de progresso.

## Executar localmente
1. Clone ou baixe este repositório.
2. Abra a pasta no Visual Studio Code.
3. Abra `index.html` com a extensão **Live Server** ou dê dois cliques no arquivo para abrir no navegador.

Não é necessário executar `npm install` ou `npm run dev`: o projeto não utiliza Node.js, build ou dependências externas.

## Funcionalidades já presentes no MVP
- Cadastro e login demonstrativos.
- Seleção de interesses.
- Catálogo com busca e filtros.
- Visualização de conteúdo textual.
- Registro de conteúdo iniciado, em andamento ou concluído.
- Painel de progresso e retomada.
- Persistência local com `localStorage`.

## Estrutura
```text
orbi-mvp/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── workflows/
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/
├── app.js
├── index.html
├── styles.css
├── .gitignore
└── README.md
```

## Organização da dupla
- **Giovanna:** interface, experiência do usuário, responsividade e validação visual.
- **Marcos:** lógica JavaScript, persistência, testes funcionais e integração.
- **Ambos:** refinamento do backlog, decisões de produto, revisão de Pull Requests, testes de aceitação e apresentação.

A divisão é inicial e pode ser ajustada conforme a disponibilidade e o andamento das tarefas.

## GitHub e fluxo de trabalho
1. Cada tarefa deve ter uma Issue com responsável e critérios de aceite.
2. Mover a Issue no GitHub Projects conforme o trabalho avança.
3. Criar uma branch por tarefa.
4. Fazer commits pequenos e objetivos.
5. Abrir Pull Request para `main` e solicitar revisão do outro integrante.
6. Após aprovação e testes, integrar e fechar a Issue.

Consulte:
- [`docs/PLANO_DE_IMPLEMENTACAO.md`](docs/PLANO_DE_IMPLEMENTACAO.md)
- [`docs/QUADRO_E_BACKLOG.md`](docs/QUADRO_E_BACKLOG.md)
- [`docs/CRITERIOS_DE_ACEITE.md`](docs/CRITERIOS_DE_ACEITE.md)

## Limitações e cuidados
Este MVP é uma prova de conceito front-end. Não possui backend, autenticação real, sincronização entre dispositivos ou armazenamento seguro em servidor. As credenciais e o progresso ficam no navegador. Utilizem somente dados fictícios e não apresentem a aplicação como pronta para produção.

## Publicação
O repositório pode ser público. Para publicar a aplicação com GitHub Pages, acesse **Settings → Pages** e configure a publicação por **GitHub Actions**. O workflow incluído neste repositório publica os arquivos estáticos quando houver push na branch `main`.

## Licença
Nenhuma licença foi definida. Um repositório público permite visualizar o código, mas não concede automaticamente permissões amplas de reutilização. Escolham e adicionem uma licença (por exemplo, MIT) somente se desejarem autorizar formalmente a reutilização.
