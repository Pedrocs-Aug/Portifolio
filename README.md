## 💼 Pedro Augusto - Portfólio Pessoal

Este projeto é um **Portfólio Pessoal** dinâmico e visualmente engajador, desenvolvido como um projeto de estudo focado em aprimorar habilidades em **HTML e CSS**.

---

### ✨ Visão Geral do Projeto

O portfólio apresenta um layout moderno de duas colunas, dividido em:

1.  **Seção de Perfil (`.container_1`):** Estilizada com um fundo vermelho vibrante (`rgba(253, 2, 2, 0.986)`), exibe a foto de perfil e contém links diretos para as principais redes sociais do desenvolvedor (Instagram, GitHub, Facebook e LinkedIn).
2.  **Seção de Projetos (`.section_projects`):** Estilizada com um fundo preto elegante (`rgba(0, 0, 0, 0.863)`), apresenta uma galeria de projetos com um diferencial interativo.

### 💡 Destaque Técnico: O Efeito Card Flip

O principal destaque do projeto é o efeito interativo aplicado aos cartões de projetos (`.card-flip`):

* **Interação em 3D:** Ao passar o mouse (`:hover`) sobre qualquer projeto, o contêiner interno (`.flipper`) executa uma **rotação em 3D** (`transform: rotateY(180deg)`).
* **Demonstração Dupla:**
    * O lado "frontal" (`.front`) exibe a **visualização** do projeto (`img_project_preview`).
    * O lado "traseiro" (`.back`) é rotacionado inicialmente (`transform: rotateY(180deg)`) e se revela durante o hover, mostrando uma imagem do **código-fonte** correspondente (`img_project_preview`).
* **Implementação CSS:** Utiliza as propriedades `perspective: 1000px`, `transform-style: preserve-3d` e `backface-visibility: hidden` para criar a ilusão de profundidade e o efeito de rotação.

### 🛠️ Tecnologias Utilizadas

* **HTML5:** Para a estrutura semântica e inclusão de conteúdo.
* **CSS3:** Para toda a estilização e a criação do efeito de *flip card*.
    * Utilização de `flexbox` para o alinhamento de layout.
    * Importação da fonte **'Overpass'** do Google Fonts.
* **Design:** Implementação de um `box-shadow` chamativo na imagem de perfil.

### 📌 Próximos Passos e Implementações

1.  **Funcionalidade de Download do CV:** O botão (`.btn_download_cv`) na seção de perfil está estilizado e a próxima etapa é adicionar a funcionalidade para permitir o download direto do currículo.
2.  **Responsividade:** O layout atual utiliza medidas relativas como `vw` e `vh`. É crucial implementar *media queries* para garantir que o portfólio seja totalmente responsivo e otimizado para dispositivos móveis.

---

Para acessar o projeto e interagir com os cards, clique nos links de projeto na seção de projetos!

---

Gostaria de ajuda para começar a implementação da funcionalidade de **download do CV**?