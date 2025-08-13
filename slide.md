---
marp: true
theme: academic-erbase
paginate: true
math: katex
---

<!-- _class: lead -->

![top-right](https://i.imgur.com/aG9Btbp.png)

## Como criar seu TCC com o VixeText: Automatizando trabalhos acadêmicos com Markdown

**AUTORES**: Reinan Gabriel Dos Santos Souza

<!-- _footer: '13 de agosto de 2025' -->

---

![bg left:40% 80%](https://www.qrtag.net/api/qr_1280.png?url=https://github.com/ReinanHS/vixetext-erbase-presentation)

**Material utilizado na apresentação**

Todos os materiais relacionados à apresentação estão disponíveis digitalmente no meu repositório do **GitHub**. Para acessar esses recursos, basta escanear o **QR Code** na imagem ao lado.

> https://github.com/reinanhs/vixetext-erbase-presentation

---

![bg left:40% 80%](https://avatars.githubusercontent.com/u/28494067?v=4)

**Reinan Gabriel dos Santos Souza**

Formado em **Sistemas de Informação** pelo **Instituto Federal de Sergipe (IFS)** em 2024, sou um profissional apaixonado por tecnologia.

Atualmente atuo como **Engenheiro DevOps Pleno** na **MOVA & Serasa Experian**.

🔗 [linktr.ee/reinanhs](https://linktr.ee/reinanhs)

---

<!-- _header: Sumário -->

- Introdução ao VixeText
- Criação e estrutura de projetos acadêmicos
- Inserção de elementos textuais, pré-textuais e pós-textuais
- Referências bibliográficas e citações
- Formatos de referência e geração de PDFs
- Automação com CI/CD (GitHub Actions)
- Apresentações acadêmicas com Marp

---

<!-- _header: Introdução ao VixeText -->

A concepção do **VixeText** teve início em **17 de setembro de 2022**, durante o período da minha graduação.

![center h:300](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-do-primeiro-commit.png)

Naquela ocasião, enfrentava recorrentes limitações ao utilizar ferramentas amplamente adotadas, como o **Microsoft Word** e o **Overleaf**. 

---

<!-- _header: Problemas principais identificados naquele período -->

1. **Complexidade** na formatação de trabalhos acadêmicos;
1. **Limitações** nas ferramentas de escrita acadêmica;
1. **Dificuldades** na criação de apresentações acadêmicas;
1. **Falta de integração** entre ferramentas de escrita e apresentação;
1. **Carência** de automatização no processo de elaboração de trabalhos acadêmicos.

---

Esse cenário motivou a busca por uma alternativa que possibilitasse a **escrita acadêmica** por meio do **Markdown**.

![center h:450](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-do-uso-markdown.png)

---

<!-- _header: Gráfico comparando a curva de aprendizado entre Markdown e LaTeX -->

![center h:400](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/grafico-markdown-latex.png)

- Markdown: A curva mostra uma ascensão rápida na proficiência com poucas horas de estudo. Isso reflete sua simplicidade e sintaxe intuitiva.

---

<!-- _header: Exemplo de código em LaTeX -->

![center h:550](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-de-codigo-latex.png)

---

<!-- _header: Exemplo de código em Markdown -->

![center h:550](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-do-uso-markdown-2.png)

---

<!-- _header: Do conceito à ferramenta -->

A partir dessa motivação, nasceu o **VixeText** 

Ele é uma solução que integra **Markdown**, **Limarka** e **processos automatizados** para simplificar a produção de trabalhos acadêmicos.

O objetivo central foi criar um ambiente **simples**, **padronizado** e **eficiente**, permitindo que estudantes e pesquisadores concentrem-se no conteúdo, sem se preocupar com formatação complexa.

---

<!-- _header: Ilustração da integração -->

![center h:600](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/ilustracao-da-integracao.png)

---

<!-- _header: Características principais do VixeText -->

- **Escrita em Markdown**: Sintaxe simples e legível, facilitando a criação de conteúdo.

![center h:500](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-de-uso-vscode.png)

---

<!-- _header: Características principais do VixeText -->

- **Compatibilidade com normas ABNT**: Geração automática de documentos no formato exigido.
- **Gerenciamento de referências**: Uso de BibLaTeX para controle bibliográfico.

![center h:400](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-de-caracteristicas.png)

---

<!-- _header: Características principais do VixeText -->

- **Automação com CI/CD**: Compilação e publicação automáticas a partir do repositório.

![center h:450](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-de-automacao-ci-cd.png)

---

<!-- _header: Características principais do VixeText -->

- **Suporte a apresentações**: Integração com Marp para criação de slides acadêmicos.

![center h:450](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-vetor.png)

---

<!-- _header: Benefícios para o usuário -->

O **VixeText** elimina barreiras comuns no processo de escrita acadêmica:

1. **Padronização** de formatação sem esforço manual.
2. **Agilidade** na criação e atualização de documentos.
3. **Integração** de texto, figuras, tabelas e referências de forma automatizada.
4. **Acessibilidade** do conteúdo em diferentes formatos, como PDF e apresentações.

> Com o VixeText, o foco deixa de ser “como formatar” e passa a ser “o que escrever”.

---

<!-- _header: Benefícios para o usuário -->

![center h:800](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-de-controle-de-versao.png)

---

<!-- _header: Benefícios para o usuário -->

![center h:500](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-gerenciamento-das-atividades-pelo-kanban.png)

---

<!-- _header: Comparação de ferramentas -->

![center](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/markdown-image-779812.png)

---

<!-- _header: Exemplos práticos com o VixeText -->

O **VixeText** demonstra sua versatilidade na produção, formatação e publicação de:

- Documentos acadêmicos
- Apresentações de slides
- Páginas web  

> O conteúdo é escrito em **Markdown** e transformado automaticamente em produtos finais padronizados e prontos para uso.

---

<!-- _header: Exemplo de TCC -->

O VixeText possibilita criar **Trabalhos de Conclusão de Curso (TCC)** totalmente formatados conforme normas acadêmicas da ABNT, prontos para submissão ou impressão.

Características:

- Estrutura padronizada de capa, folha de rosto, sumário e referências.
- Formatação automática de títulos, subtítulos, citações e legendas.
- Listas automáticas de figuras, tabelas e abreviaturas.

---

<!-- _header: Exemplos de TCC -->

- [Exemplo básico de TCC](https://vixetext.github.io/vixetext-template/assets/files/titulo-do-trabalho.pdf)
- [TCC por Reinan Souza](https://reinanhs.github.io/tcc-bsi-ifs/assets/files/automatizacao-e-padronizacao-da-escrita-academica-com-limarka-e-marp-um-estudo-de-caso-para-o-ifs.pdf)
- [TCC por José Santana](https://apolos7.github.io/sentilytics-tcc/assets/files/sentilytics-analise-automatizada-de-sentimentos-em-redes-sociais.pdf)

---

<!-- _header: Apresentações de slides -->

O VixeText também converte o conteúdo do TCC em **apresentações HTML** usando o **Marp**.

Vantagens:

- Design limpo e responsivo
- Compatibilidade com navegadores modernos
- Suporte a imagens, gráficos e código
- Transições suaves

> **Dica:** O conteúdo vem do próprio TCC, garantindo consistência.

---

<!-- _header: Exemplos de slides -->

- [Slides básicos](https://vixetext.github.io/vixetext-template/slide)
- [Slides por Reinan Souza](https://reinanhs.github.io/tcc-bsi-ifs/slide)
- [Slides por José Santana](https://apolos7.github.io/sentilytics-tcc/slide)

---

<!-- _header: Página web do trabalho -->

O VixeText gera uma **página web centralizada** com todos os materiais acadêmicos.

Funcionalidades:

- Acesso rápido a PDF, slides e anexos
- Organização por seções
- Layout responsivo

> **Benefício:** Ideal para publicação e compartilhamento com banca e comunidade.

---

<!-- _header: Exemplos de páginas web -->

- [Página básica](https://vixetext.github.io/vixetext-template/)
- [Página por Reinan Souza](https://reinanhs.github.io/tcc-bsi-ifs/)
- [Página por José Santana](https://apolos7.github.io/sentilytics-tcc/)

---

<!-- _header: Considerações -->

O **VixeText** automatiza todo o fluxo acadêmico, gerando simultaneamente:

- **Documento final** (PDF)
- **Apresentação** (slides)
- **Repositório online** (página web)

Benefícios:

- Elimina retrabalho de formatação
- Garante conformidade com normas
- Otimiza tempo de estudantes e orientadores

---

<!-- _header: Guia de início rápido -->

Este guia ajuda **novos usuários** a configurar e utilizar o **VixeText** de forma ágil e eficiente.

Dois modos de uso:

1. **Navegador** (Playground) — sem instalação local.
1. **Navegador** (GitHub Codespaces) — sem instalação local.
2. **Linha de comando (CLI)** — para maior controle.

> https://vixetext.com/comecando/guia-de-inicio-rapido

---

<!-- _header: Utilizando no navegador (Playground) -->

Para começar, basta acessar o site do **vixetext** sem necessidade de cadastro.

Vantagens:

- Nenhuma instalação local necessária.
- Ideal para testes rápidos.

Desvantagens:

- Este é um ambiente básico destinado apenas para testes por iniciantes.

---

Acesse o site da ferramenta Vixetext. Ao entrar no portal, selecione o botão de **playground**.

Consulte o exemplo ilustrado na imagem abaixo:

![center h:400](https://raw.githubusercontent.com/ReinanHS/vixetext-erbase-presentation/refs/heads/master/img/exemplo-do-playground.png)

> https://vixetext.com/

---

<!-- _header: Utilizando no navegador (GitHub Codespaces) -->

A forma mais simples de começar: **GitHub Codespaces**.

Vantagens:

- Ambiente virtual pré-configurado.
- Nenhuma instalação local necessária.
- Ideal para testes rápidos.

---

**Passos:**
1. Clique no botão [Open in GitHub Codespaces](https://codespaces.new/vixetext/vixetext-template?machine=standardLinux2gb).
2. Selecione **"New Codespace"**.
3. Aguarde a configuração automática.
4. Ambiente pronto para edição e compilação.

> **Ideal para iniciantes**

---

<!-- _header: Utilizando via linha de comando (CLI) -->

Opção para usuários que preferem **ambiente local** ou **maior controle**.

Pré-requisitos:
- **Docker** instalado e em execução.
- Conhecimento básico de terminal.

**Passo 1:** Clonar o repositório

```sh
git clone https://github.com/vixetext/vixetext-template.git
cd vixetext-template
````

---

<!-- _header: Utilizando via linha de comando (CLI) -->

**Passo 2:** Executar compilação

```sh
docker run --rm -it \
    -v "$(pwd)":/usr/src/trabalho \
    --entrypoint="/bin/bash" \
    reinanhs/limarka-help:1.0.0 \
    -c "limarka-help"
```

Esse comando:

* Monta o diretório no contêiner Docker.
* Processa o conteúdo em Markdown.
* Gera automaticamente o **PDF final** no diretório do projeto.

---

<!-- _header: Próximos passos -->

Após a configuração inicial, você pode:

* Editar arquivos `.md` com seu conteúdo.
* Ajustar `configuracao.yaml` (título, autor, orientador etc.).
* Adicionar referências com **BibTeX**.
* Criar apresentações com **Marp**.
* Publicar como página web.

---

<!-- _header: Próximas seções - Modo prático -->
<!-- _class: lead -->

# 🚀 Próximas seções

As próximas etapas serão **100% práticas**.  
Para esses casos, **não seguiremos o slide**,  
mas sim a **[documentação oficial do VixeText](https://vixetext.com/)**.

---

## 📋 Conteúdos práticos

- Criação e estrutura de projetos acadêmicos  
- Inserção de elementos textuais, pré-textuais e pós-textuais  
- Referências bibliográficas e citações  
- Formatos de referência e geração de PDFs  
- Automação com CI/CD (GitHub Actions)  
- Apresentações acadêmicas com Marp

---

<!-- _header: Nível de familiaridade -->

Antes de iniciarmos,  
quero entender como está o nível de conhecimento de vocês  
sobre as ferramentas que iremos utilizar:

- **Git**
- **GitHub**
- **Docker**
- **LaTeX**
- **Markdown**
- **CI/CD** (GitHub Actions)

💬 Quem já usou alguma delas?  

---

<!-- _header: Perguntas e respostas -->
<!-- _class: lead -->

# ❓ Espaço para dúvidas

Este é o momento para  
**perguntas, comentários e discussões**.

---

<!-- _class: lead -->

# ✅ Encerramento

Obrigado pela participação! 🙌

📌 Mais informações e documentação completa:  
[https://vixetext.com/](https://vixetext.com/)  

💬 Em caso de dúvidas futuras, entre em contato.  
Foi um prazer compartilhar esse conteúdo com vocês!
