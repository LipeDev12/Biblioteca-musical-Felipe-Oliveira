# 🎵 Sistema Musical — Web App (Fase 1)

Projeto de desenvolvimento front-end para um sistema de gerenciamento de músicas, artistas e acervo musical, desenvolvido para a disciplina do **Professor Denani**.

Esta etapa corresponde à **Fase 1 (Protótipo Front-End)**, contemplando a estrutura semântica em HTML5 e a estilização responsiva em CSS3, estruturada para futura integração backend (PHP/MySQL) na Fase 2[cite: 1, 2, 3, 4, 5, 6].

---

## 📌 Funcionalidades e Telas

O sistema é composto por 5 telas principais interligadas:

1. **🔒 Tela de Login (`login.html`)**
   - Interface de autenticação para usuários.
   - Formulário estruturado para submissão POST de credenciais[cite: 6].
   - Exibição de dica de credenciais de teste (`admin` / `123`)[cite: 6].

2. **🏠 Menu Principal / Dashboard (`index.html`)**
   - Painel inicial de navegação do sistema após login.
   - Cards visuais com links de navegação para os módulos do sistema[cite: 4].
   - Botão de logout no cabeçalho[cite: 4].

3. **🎤 Cadastro e Gestão de Artistas (`cadastro_artista.html`)**
   - Formulário para inclusão de artistas (Nome, Gênero, País e Foto)[cite: 2].
   - Suporte a upload de imagem (`enctype="multipart/form-data"`)[cite: 2].
   - Tabela de listagem dos artistas cadastrados com botões de ação (Editar, Excluir, Músicas)[cite: 2].

4. **🎵 Cadastro de Músicas (`cadastro_musica.html`)**
   - Formulário com seleção de artista via `<select>`[cite: 3].
   - Campos para Título, Álbum, Gênero, Link do YouTube, Capa do Álbum e Letra[cite: 3].
   - Tabela de pré-visualização das músicas cadastradas[cite: 3].

5. **🎼 Biblioteca Musical (`listagem_musicas.html`)**
   - Consulta completa das músicas do acervo[cite: 5].
   - Filtros superiores por busca textual, artista e gênero[cite: 5].
   - Tabela com ações de edição, exclusão e atalho para assistir ao clipe no YouTube[cite: 5].

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação semântica, validação nativa de campos (`required`, `type="url"`, `type="file"`) e acessibilidade[cite: 2, 3, 6].
- **CSS3**:
  - **Variáveis CSS (`:root`)**: Padronização de cores, tipografia, sombras e cantos arredondados[cite: 1].
  - **Flexbox & CSS Grid**: Disposição responsiva de formulários, cards de navegação e tabelas[cite: 1].
  - **Media Queries (`@media`)**: Design adaptável para telas móbiles e tablets[cite: 1].

---
