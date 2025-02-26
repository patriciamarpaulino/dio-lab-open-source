<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Guia de Contribuição</span>
</h1>

[![Star](https://img.shields.io/github/stars/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/stargazers)
[![Forks](https://img.shields.io/github/forks/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/forks)
[![GitHub Issues](https://img.shields.io/github/issues/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/issues/)

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além do seu exemplo de Profile README, é inserir outros utilitários na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils), ou melhorar a página de pesquisa dos READMEs fazendo modificações nos arquivos da pasta [`docs`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/docs). <br>
 Além disso, você também pode contribuir:
 
⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**) 

##  Contribuindo no diretório "Community" 
 A contribuição no diretório "Community" é uma das formas de completar o Desafio do lab "**Contribuindo em um Projeto Open Source no GitHub**" da [Digital Innovation One](https://www.dio.me/). Você pode colaborar criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade. <br>
 Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem. Além disso, você pode inserir também links para seus desafios de projeto e artigos na plataforma da [Digital Innovation One](https://www.dio.me/). <br>
 Inspire-se consultando os exemplos na pasta [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), confira alguns utilitários na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils) e use sua criatividade para criar o seu 😊💙.

### 1) Faça um **Fork** deste Repositório
Acesse a página principal do repositório e clique no botão "Fork" no canto superior direito da página.
> [!NOTE]  
> Um "fork" no GitHub é uma cópia de um repositório que pode ser criada por qualquer usuário. <br>
> Para mais detalhes, reveja a aula ou acesse a documentação do GitHub: [Criar fork de um repositório](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

### 2) Clone localmente
Abra o seu Git Bash e digite o comando `git clone` seguido da URL do seu fork para clonar o seu repositório localmente. Por exemplo:
```bash
git clone https://github.com/SEU_USERNAME/dio-lab-open-source.git
```
Pressione enter, e uma cópia do seu fork no GitHub será criada localmente.

### 3) Crie uma nova **branch** 
Utilize o comando `git checkout -b` para criar e alternar para a nova branch e nomeie-a como `feat/community/SEU_USERNAME`
> Exemplo: `git checkout -b feat/community/falvojr`

### 4) Crie o seu Profile README
 Dentro da pasta [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), crie um arquivo em Markdown (extensão `.md`) e nomeie com o mesmo nome do seu usuário no GitHub:

> Exemplo: `community/falvojr.md`

#### 4.1) Desenvolva o seu Profile README
Para isso, você pode se inspirar nos exemplos no diretório [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community) e adicionar alguns dos utilitários presentes na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils)

### 5) Adicione suas alterações à "staging area" 
Utilize o comando `git add community/SEU_USERNAME.md` para adicionar sua alteração (nesse caso o arquivo markdown criado)  à "staging area" no Git.

### 6) Crie um Commit
Crie um commit e adicione a mensagem indicando a adição do seu perfil:
```bash
git commit -m"feat: add SEU_USERNAME profile"
```
>[!IMPORTANT]
> Verifique a [`Convenção de Commits`](https://github.com/digitalinnovationone/dio-lab-open-source/blob/main/CONTRIBUTING.md#conven%C3%A7%C3%A3o-de-commits) para escrever a mensagem do seu commit de forma clara e padronizada.

### 7) Envie as Alterações para o seu Repositório Remoto
Envie as alterações realizadas no seu repositório local para a branch `feat/community/SEU_USERNAME` no seu repositório remoto com o comando:
```bash
git push origin feat/community/SEU_USERNAME
```
>[!WARNING]
> Caso você tenha criado seu arquivo diretamente no repositório remoto no GitHub, esse processo não será necessário.

### 8) Crie um **Pull Request**.

Atente-se para a seguir as orientações para a contribuição, principalmente:
- Seu PR deve modificar apenas o arquivo community/SEU_USERNAME.md (dê uma olhadinha na aba "Files changed");
- O nome desse arquivo deve ser exatamente igual ao nome de usuário no GitHub (nossa validação é case-sensitive).

>[!NOTE]
> Caso não saiba como criar uma solicitação de pull, reveja o lab ou acesse a documentação do GitHub: [Como criar uma solicitação de pull
](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

Após criar o seu Pull Request, nossa automação irá validar a sua submissão. Caso esteja tudo certo, será retornada uma mensagem indicado que seu PR foi aprovado. Do contrário, leia atentamente as orientações e verifique os arquivos modificados para saber se atende as instruções para contribuição.

    ### 🚀 **Convenção de Commits – Bootcamp Heineken - Inteligência Artificial Aplicada a Dados com Copilot**  

Esta convenção mantém o histórico de commits **organizado, legível e consistente**, facilitando a colaboração e rastreabilidade no projeto.  

---

#### 🎯 **Formato padrão:**  


🔎 **Regras:**  
- Use **verbos no imperativo** na descrição (ex.: "adiciona", "corrige").  
- Descrição **curta e objetiva** (máximo 72 caracteres).  
- Separe corpo e rodapé com **uma linha em branco** (se necessário detalhar).  
- **Referencie issues ou tarefas** no rodapé se aplicável (ex.: `Refs: #123`).  

---

#### 📝 **Tipos de commit:**  

| Tipo        | Descrição                                       | Exemplo                                      |
|-------------|-------------------------------------------------|----------------------------------------------|
| **feat**    | Adição de nova funcionalidade                   | `feat(data): adiciona script para limpeza`  |
| **fix**     | Correção de bugs                                | `fix(api): corrige erro na requisição`      |
| **docs**    | Atualizações de documentação                    | `docs(readme): atualiza instruções de uso`  |
| **style**   | Mudanças visuais ou de formatação (sem lógica)  | `style(code): ajusta indentação e espaçamento`|
| **refactor**| Refatorações que não alteram a funcionalidade   | `refactor(data): melhora legibilidade do código`|
| **test**    | Criação ou ajuste de testes                     | `test(model): adiciona testes unitários`    |
| **chore**   | Tarefas administrativas e configurações         | `chore(env): atualiza variáveis de ambiente`|
| **perf**    | Melhorias de performance                        | `perf(query): otimiza consultas SQL`        |
| **ci**      | Alterações no pipeline de integração contínua   | `ci(github-actions): ajusta workflow de deploy`|
| **revert**  | Reversão de commits                             | `revert: desfaz commit anterior`            |

---

#### 🧩 **Escopos sugeridos:**  

- **data** – Manipulação e tratamento de dados  
- **copilot** – Implementações com Microsoft Copilot  
- **sql** – Scripts e consultas SQL  
- **ai** – Funcionalidades relacionadas à inteligência artificial  
- **api** – Endpoints e comunicação entre sistemas  
- **docs** – Documentação do projeto  
- **config** – Arquivos de configuração e ambiente  
- **deps** – Gerenciamento de dependências  
- **tests** – Criação e manutenção de testes  

---

#### 📖 **Exemplos práticos:**  

- `feat(ai): implementa modelo preditivo de vendas`  
- `fix(sql): corrige erro em consulta de usuários`  
- `docs(readme): adiciona instruções de configuração`  
- `style(code): remove espaços desnecessários`  
- `refactor(data): simplifica função de transformação`  
- `test(api): cria testes para endpoint de produtos`  
- `chore(deps): atualiza dependências do projeto`  
- `ci(actions): corrige falha no workflow de build`  

---

#### 💡 **Dicas:**  
✅ **Commits pequenos e frequentes** ajudam no controle de alterações.  
✅ Use `git commit --amend` para corrigir o último commit (antes do push).  
✅ **Prefira `git rebase` ao invés de `git merge`** para um histórico limpo.  
✅ Referencie tarefas ou issues sempre que possível.  

### 📚 Referências Bibliográficas  

CONVENTIONAL COMMITS. *Conventional Commits Specification v1.0.0.* 2024. Disponível em: <https://www.conventionalcommits.org>. Acesso em: 21 fev. 2025.  

GIT DOCUMENTATION. *Git Tools - Rewriting History.* 2024. Disponível em: <https://git-scm.com/docs>. Acesso em: 21 fev. 2025.  

ANGULAR. *Git Commit Guidelines.* 2024. Disponível em: <https://github.com/angular/angular/blob/main/CONTRIBUTING.md#commit>. Acesso em: 21 fev. 2025.  

KEEP A CHANGELOG. *Principles of Changelogs.* 2024. Disponível em: <https://keepachangelog.com>. Acesso em: 21 fev. 2025.  

GITHUB DOCS. *About commits.* 2024. Disponível em: <https://docs.github.com>. Acesso em: 21 fev. 2025.  



