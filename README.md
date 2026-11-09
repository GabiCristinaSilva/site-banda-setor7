# 🎸 Banda Setor 7 — Site Institucional

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/status-online-brightgreen?style=for-the-badge)

Site institucional da banda **Setor 7**: uma vitrine digital responsiva, com navegação
simples e conteúdo em vídeo, pensada para funcionar bem em computadores e celulares.

🌐 **Acesse o site:** [www.bandasetor7.com.br](https://www.bandasetor7.com.br)

---

## 📋 Sobre o projeto

Projeto pessoal desenvolvido em **julho de 2026**, com dois objetivos: dar à banda uma
presença online profissional e aplicar, na prática, os conhecimentos de desenvolvimento
web adquiridos na graduação em **Sistemas de Informação**.

O site é uma aplicação **estática** (sem banco de dados e sem back-end), construída
apenas com HTML5, CSS3 e JavaScript puro — o que torna a hospedagem simples, rápida e
gratuita.

## ✨ Funcionalidades

- **Layout responsivo**, adaptado a diferentes tamanhos de tela (desktop, tablet e celular)
- **Página inicial** com banner de destaque e vídeo de abertura (`video-inicio.mp4`)
- **Seção Sobre** com vídeo institucional (`video-sobre1.mp4`) e apresentação da banda
- **Repertório** — página dedicada a mostrar o que a banda toca
- **Pacotes** — apresentação das opções de contratação para eventos
- **Contato** — canais diretos de contato (WhatsApp, Instagram, TikTok e YouTube)
- **Galeria de momentos** — seleção de fotos de shows
- **Logotipos de empresas e instituições** para as quais a banda já se apresentou
- **Página de Política de Privacidade**
- Navegação amigável e de fácil leitura em todas as páginas

## 🛠 Tecnologias utilizadas

| Tecnologia     | Uso no projeto                              |
| -------------- | ------------------------------------------- |
| **HTML5**      | Estrutura semântica das páginas             |
| **CSS3**       | Estilização, layout responsivo e animações  |
| **JavaScript** | Interatividade da interface (`main.js`)     |

> Projeto sem dependências, sem frameworks e sem etapa de build — basta abrir no navegador.

## ✅ Pré-requisitos

- Um navegador moderno (Chrome, Firefox, Edge ou Safari)
- [Git](https://git-scm.com/) instalado (para clonar o repositório)
- Opcional: [VS Code](https://code.visualstudio.com/) + extensão **Live Server**, ou Python 3
  para rodar um servidor local

## 🚀 Como executar localmente

1. Clone este repositório:

   ```bash
   git clone https://github.com/GabiCristinaSilva/banda-setor7.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd banda-setor7
   ```

3. Abra a página inicial. Duas opções:

   **Opção A — abrir o arquivo direto no navegador:**

   ```bash
   cd site_moderno
   ```

   Depois abra o arquivo `index.html` no navegador.

   **Opção B — servidor local (recomendado, garante o carregamento dos vídeos):**

   ```bash
   # estando na pasta raiz do projeto
   cd site_moderno && python3 -m http.server 8000
   ```

   E acesse [http://localhost:8000](http://localhost:8000).

## 📁 Estrutura do projeto

```text
banda-setor7/
└── site_moderno/
    ├── index.html            # Página inicial
    ├── sobre.html            # Sobre a banda
    ├── repertorio.html       # Repertório
    ├── pacotes.html          # Pacotes de contratação
    ├── contato.html          # Contato
    ├── privacidade.html      # Política de privacidade
    └── assets/
        ├── css/
        │   ├── style.css         # Estilos globais
        │   ├── sobre.css         # Estilos da página Sobre
        │   ├── repertorio.css    # Estilos da página Repertório
        │   ├── pacotes.css       # Estilos da página Pacotes
        │   └── contato.css       # Estilos da página Contato
        ├── js/
        │   └── main.js           # Interatividade da interface
        ├── img/                  # Banners, fotos de shows, integrantes, logos e ícones sociais
        └── videos/
            ├── video-inicio.mp4
            └── video-sobre1.mp4
```

> Cada página HTML possui seu próprio arquivo CSS, mantendo os estilos organizados por
> contexto e facilitando a manutenção.

## 🌐 Deploy

O site pode ser publicado gratuitamente no **GitHub Pages**:

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch **main** e a pasta **/ (root)** — ou **/docs**, caso o conteúdo
   esteja dentro de uma pasta `docs`.
4. Clique em **Save** e aguarde a publicação.

O endereço gerado será `https://gabicristinasilva.github.io/banda-setor7/`.
Para usar o domínio próprio, informe `bandasetor7.com.br` em **Custom domain** e crie o
arquivo `CNAME` na raiz do repositório com esse mesmo domínio.

## 🤝 Como contribuir

Contribuições são bem-vindas! Para propor melhorias:

1. Faça um **fork** do projeto
2. Crie uma branch com a sua alteração:
   ```bash
   git checkout -b feat/minha-melhoria
   ```
3. Faça o commit seguindo o padrão de mensagens descrito abaixo:
   ```bash
   git commit -m "feat: adiciona agenda de shows"
   ```
4. Envie a branch:
   ```bash
   git push origin feat/minha-melhoria
   ```
5. Abra um **Pull Request** descrevendo a mudança

**Padrão de commits (Conventional Commits):** `feat:`, `fix:`, `docs:`, `style:`,
`refactor:`, `perf:`, `test:`, `chore:`.

## 📄 Licença

O **código-fonte** deste projeto está sob a licença **MIT** — consulte o arquivo
[LICENSE](LICENSE) para os detalhes.

> As fotografias, os vídeos, o logotipo da banda e os logotipos de terceiros (empresas,
> instituições e marcas) **não** estão cobertos pela licença MIT e permanecem de
> propriedade de seus respectivos titulares. Não é permitida a reutilização desses
> materiais sem autorização.

## 👩‍💻 Autora

**Gabriela Cristina da Silva**
Estudante de Sistemas de Informação

- GitHub: [@GabiCristinaSilva](https://github.com/GabiCristinaSilva)
- LinkedIn: [gabrielacristina1903](https://www.linkedin.com/in/gabrielacristina1903)
- Site: [bandasetor7.com.br](https://www.bandasetor7.com.br)

---

<sub>Desenvolvido com dedicação à música e ao código 🎶</sub>
