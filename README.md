# 🎬 CG Filmes

Bem-vindo ao repositório do **CG Filmes**! Este projeto é uma simulação completa de um website de cinema (Front-end), desenvolvido com foco em design responsivo, organização estrutural e experiência do usuário.

---

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica das páginas.
* **CSS3:** Estilização avançada.
    * **Flexbox:** Para alinhamento e distribuição de elementos (navbar, cards).
    * **CSS Gradients:** Fundo escuro e moderno (`linear-gradient`).
    * **Media Queries:** Design totalmente responsivo (adaptável a celulares e tablets).
    * **Animações:** Efeitos de *hover* e transições suaves em botões e imagens.

---

## 📂 Estrutura do Projeto

O projeto está organizado nas seguintes pastas:
* `/html`: Contém todas as páginas do site.
* `/style`: Arquivos de estilo separadas para cada página, facilitando a manutenção.
* `/imgs`: Recursos gráficos (pósteres, banners, fotos dos combos e logos).

---

## 📖 Funcionalidades e Páginas

### 1. Home (`home.html`)
![Página Principal](/imgs/readme/image.png)
A página inicial serve como o *hub* central do cinema.
* **Banner Principal:** Destaque visual com botão.
* **Mais Assistidos:** Exibição dos filmes populares (ex: *Interestelar*, *Conclave*) com sinopses curtas.
* **Mais Pedidos:** Atalho para os combos de pipoca mais vendidos.
* **Navegação:** Menu fixo no topo e rodapé completo com links rápidos.

### 2. Em Cartaz (`cartaz.html`)
![Página Em Cartaz](/imgs/readme/image-1.png)
Catálogo completo dos filmes disponíveis.
* **Visualização:** Cards com os pósteres dos filmes.
* **Interatividade:** Efeito de escurecimento ao passar o rato sobre o póster.
* **Horários:** Lista de sessões (Dublado, Legendado, 3D).
    * *Detalhe:* Horários indisponíveis aparecem desativados visualmente (cinzento), enquanto horários ativos levam à simulação de compra.
* **Em Breve:** Seção dedicada a lançamentos futuros (ex: *Zootopia 2*, *Avatar 3*).

### 3. Comidas & Bebidas (`comidas.html`)
![Página de Comidas](/imgs/readme/image-2.png)
A experiência do cinema não está completa sem pipocas.
* **Combos Promocionais:** Cards detalhando o conteúdo (pipoca, bebida, doces) e o preço.
* **Combos Temáticos:** Edições especiais baseadas em filmes (ex: *Viúva Negra*, *Shazam*, *Tartarugas Ninja*).

### 4. Contato (`contato.html`)
![Página de Contato](/imgs/readme/image-3.png)
Canal de comunicação com o cliente.
* Formulário estilizado com campos para Nome, E-mail, CPF, Telefone e Mensagem.
* Design consistente com o tema escuro do site.

### 5. Login (`login.html`)
![Página de Login](/imgs/readme/image-4.png)
Simulação de área de acesso ao utilizador.
* Campos de e-mail e senha.
* Opções de "Lembre-se de mim" e "Esqueci a senha".
* Link para cadastro de novos membros.

---

## 🎨 Design e Estilo

O projeto segue uma identidade visual forte e coesa:
* **Paleta de Cores:** Fundo escuro (`#1a1a1a`, `#0f0f0f`) contrastando com detalhes em vermelho vibrante (`#d30f0f`) e texto claro (`#f0f0f0`).
* **Tipografia:** Uso da fonte *Roboto Condensed*, garantindo legibilidade e um visual moderno.
* **Componentes Reutilizáveis:** Botões, inputs e cards seguem padrões definidos no `style.css` global.

---

## 🔧 Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/seu-usuario/CG-Filmes.git](https://github.com/seu-usuario/CG-Filmes.git)
    ```
2.  Navegue até a pasta do projeto.
3.  Abra o ficheiro `html/home.html` no seu navegador.


