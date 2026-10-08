# Fluxo – Landing Page de Conversão (SaaS)

Landing page responsiva para um produto SaaS fictício, o **Fluxo** (gestão de pedidos, agenda e cobranças para pequenas empresas de serviços). Projeto de portfólio criado para demonstrar uma landing page **focada em conversão**, com copy centrada nas **dores do cliente** e não apenas em lista de funcionalidades.

> **Aviso:** o Fluxo é um produto de exemplo. Depoimentos, preços e imagens do produto estão como placeholders entre colchetes (`[...]`) e devem ser substituídos por informações reais.

## Prévia

- Link da página publicada: `[adicione aqui o link]`
- Captura de tela: `[adicione aqui uma imagem em /docs/preview.png]`

## Estrutura de arquivos

```
fluxo-landing/
├── index.html      # conteúdo e estrutura (textos, seções, botões)
├── css/
│   └── style.css   # visual (cores, fontes, espaçamentos, responsivo)
└── README.md
```

- **`index.html`** guarda *o que* aparece na página, seção por seção, com comentários numerados de 1 a 8.
- **`css/style.css`** guarda *como* aparece. As cores ficam no bloco `:root` no início do arquivo, e o restante segue a mesma ordem das seções do HTML.

## Como rodar

Abra o `index.html` no navegador (duplo clique). Não precisa instalar nada. Para publicar, ative o **GitHub Pages** nas configurações do repositório.

## Estrutura da página

A página segue uma sequência pensada para guiar o visitante até a ação:

| # | Seção | Objetivo |
|---|-------|----------|
| 1 | Topo (logo + CTA) | Identidade e botão sempre acessível |
| 2 | Hero | Promessa clara, subtítulo e CTA acima da dobra |
| 3 | Dores | Fazer o visitante se reconhecer no problema |
| 4 | Solução | Transformar cada dor em um benefício correspondente |
| 5 | Como funciona | Reduzir a insegurança com 3 passos simples |
| 6 | Prova social | Depoimento e resultado reais (placeholder) |
| 7 | Perguntas frequentes | Responder objeções de preço, instalação e cancelamento |
| 8 | CTA final | Repetir a chamada para ação |

## Decisões de design

- **Uma cor de destaque** (laranja escuro `#C2410C`) para botões e títulos de seção, com contraste adequado para leitura.
- **Uma única fonte**: [Manrope](https://fonts.google.com/specimen/Manrope) (pesos 400, 600 e 800).
- **Layout responsivo** com CSS Grid (`auto-fit`) e Flexbox: as seções se reorganizam sozinhas no celular.
- **Acessibilidade básica**: links e botões reais (`<a>`), áreas de toque de pelo menos 44 px e textos com contraste legível.

## Tecnologias

- HTML5
- CSS3 (Grid e Flexbox)
- Google Fonts

## Como personalizar

1. **Textos:** em `index.html`, substitua os placeholders `[...]` (preço, depoimentos, políticas) por dados reais.
2. **Imagem do produto:** troque o bloco `[Imagem: print do painel do produto]` por uma captura real.
3. **Cor da marca:** edite as variáveis `--cor-destaque` e `--cor-destaque-hover` no bloco `:root` de `css/style.css`.
4. **Links dos botões:** aponte o CTA para a página de cadastro ou de teste gratuito do produto.
5. **Adaptação para outro produto:** mantenha a estrutura, reescreva as dores e os benefícios com a linguagem do público.

## Como reaproveitar em outros projetos

1. Entenda o público e liste as 3 principais dores.
2. Escreva a copy antes de desenhar.
3. Para cada dor, crie um benefício correspondente.
4. Reúna depoimentos e resultados reais do cliente.
5. Adapte cores, fonte e imagens à marca.

## Autor

**[Seu nome]** – [seu perfil no GitHub / LinkedIn / portfólio]

## Licença

[Escolha uma licença, por exemplo MIT, ou remova esta seção.]
