# ⚔️ Os Cavaleiros do Zodíaco - Consumo de API (Front-End)

Aplicação web desenvolvida para consumo e exibição dinâmica de dados da API dos **Cavaleiros do Zodíaco** (*Saint Seiya*). O projeto foi construído utilizando tecnologias puras de Front-End para renderização dinâmica de elementos da DOM.

🔗 **Acesse o projeto online:** [https://jeffersoongomes.github.io/api-cavaleiros-zodiaco/](https://jeffersoongomes.github.io/api-cavaleiros-zodiaco/)

---

## 📌 Sobre o Projeto

Este projeto consiste em uma interface web adaptativa que realiza requisições assíncronas para uma APIRESTful de *Cavaleiros do Zodíaco*, processa a resposta em formato JSON e gera dinamicamente cards informativos contendo nome, nível/rank e imagem de cada personagem.

### 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e suporte à renderização dinâmica.
- **CSS3**: Estilização moderna em tema escuro com Flexbox, layout responsivo e efeitos de transição (*hover*).
- **JavaScript (ES6+)**:
  - Requisição assíncrona utilizando a Fetch API (`async/await`).
  - Manipulação avançada do DOM (`document.createElement`, `appendChild`, `setAttribute`).
  - Iteração de dados via `forEach`.

---

## 🚀 Como Funciona a Aplicação

1. **Requisição HTTP**: A função `getDadosAPI()` realiza um `fetch` assíncrono na URL da API pública:
   `https://back-end-saint-seiya-api.onrender.com/v1/saint-seiya/characters`
2. **Tratamento de Dados**: A resposta em JSON é convertida e repassada para a função `setCarregarDados()`.
3. **Renderização Dinâmica**: Para cada cavaleiro retornado, a aplicação gera a estrutura DOM correspondente (`div`, `h2`, `figure`, `img`, `div.caixa_texto`) e a anexa ao container principal.

---

## 👨‍💻 Autor

Desenvolvido por **Jefferson Gilvan Gomes dos Santos**  
Análise e Desenvolvimento de Sistemas
