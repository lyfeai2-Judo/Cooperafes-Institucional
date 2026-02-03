# 02 — Como este site foi feito (passo a passo)

Este documento explica, de forma simples, como o site do Observatório Cultural de Sergipe foi criado e colocado no ar.

A ideia é que qualquer pessoa — mesmo sem experiência técnica — consiga entender o processo e, se quiser, repetir.

---

## Passo 1 — Organização da base no GitHub

Primeiro, criamos um repositório no GitHub para guardar tudo do site.

O GitHub funciona como uma **pasta grande na internet**, onde ficam:
- os arquivos do site
- os textos
- a estrutura
- e a documentação do processo

Dentro do repositório, criamos a pasta principal chamada:

site/

Tudo que aparece no site público fica dentro dessa pasta.

---

## Passo 2 — Separação dos conteúdos

Para manter tudo organizado, o conteúdo foi separado em partes:

- `index.html`  
  → é a página principal (a “capa” do site)

- `textos/`  
  → guarda os textos institucionais (Home, Observatório, Contato, etc.)

- `docs/`  
  → guarda a documentação explicando como o site foi feito

Essa separação ajuda a:
- não bagunçar os arquivos
- facilitar manutenção
- permitir que outras pessoas aprendam com o processo

---

## Passo 3 — Criação da página inicial (index.html)

Dentro da pasta `site/`, foi criado o arquivo:

index.html

Esse arquivo contém:
- o título do site
- uma mensagem de boas-vindas
- links para os textos institucionais
- um status do projeto (fases)

Neste primeiro momento, o design foi mantido **simples de propósito**.
O foco inicial foi:
- colocar o site no ar
- provar que a estrutura funciona
- permitir evolução futura

---

## Passo 4 — Publicação do site com a Vercel

Depois que a estrutura estava pronta no GitHub, o site foi publicado usando a plataforma **Vercel**.

A Vercel faz o seguinte:
- lê os arquivos do GitHub
- publica automaticamente o site
- gera um link público acessível a qualquer pessoa

Neste projeto, foi configurado:
- o repositório correto
- a pasta `site` como diretório raiz
- o nome do projeto

Com isso, o site ficou disponível online.

---

## Passo 5 — Evolução em fases (importante)

O site foi pensado para crescer em etapas:

**Fase 1 — Concluída**
- Site no ar
- Estrutura funcionando
- Conteúdo inicial disponível

**Fase 2 — Próxima**
- Melhorar visual (cores, fontes, layout)
- Transformar textos em páginas definitivas
- Ajustes de navegação

**Fase 3 — Final**
- Configurar domínio próprio
- Ajustes finais
- Publicação oficial

---

## Conclusão

Este site não foi feito com pressa nem com ferramentas complicadas.

Ele foi feito com:
- organização
- clareza
- documentação
- e foco em crescimento sustentável

Tudo o que está aqui pode ser reaproveitado para outros projetos.
