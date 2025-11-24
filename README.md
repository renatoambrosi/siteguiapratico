# Landing Page - Guia Prático para Reprogramar a Mente

## 📛 Nome do Projeto, Objetivos e Principais Características
- **Nome:** Guia Prático para Reprogramar a Mente – Suellen Seragi
- **Objetivo:** Apresentar o guia digital, explicar seus benefícios e direcionar o visitante para a compra.
- **Principais características:** layout responsivo, foco em conversão, linguagem visual alinhada com a identidade de Suellen Seragi, navegação por âncoras e conteúdo estruturado em seções temáticas.

## ✅ Funcionalidades Entregues
- Header fixo com fundo branco, nova identidade visual (`images/logo-header.jpg`) e navegação atualizada.
- Logo do rodapé apontando para `images/logo-footer.jpg` (aguardando arquivo definitivo do servidor) e links institucionais.
- Menu hambúrguer para mobile com overlay, correção de camada (z-index) e bloqueio de scroll ao abrir.
- Imagem da hero estática (remoção do efeito flutuante) e CTA destacado, com contorno removido e espaçamento otimizado no mobile entre imagem, header e texto.
- Seção "Origin" refinada com textos atualizados, ícones vetoriais brancos alinhados (todos os círculos com a mesma cor de fundo), frase centralizada logo após o subtítulo no desktop e destaque ampliado com cards reorganizados abaixo.
- CTA remodelada para layout estilo cartão central (seguindo o print de referência): título do produto, preço parcelado em destaque, preço à vista abaixo, lista com ícones de check e botão 100% de largura. Todo o conteúdo (títulos, valores e itens) foi mantido conforme a LP atual.
- FAQ reconstruída com o visual do print mobile: cards brancos com bordas suaves, fundo em degradê, ícones de seta girando e estados ativos com destaque dourado, mantendo o mesmo conteúdo original.
- Seção "Tudo baseado em" otimizada no mobile: título reduzido para caber em uma linha, cartões bege/branco expandidos horizontalmente para eliminar a sensação de estreitamento e card branco centralizado para leitura equilibrada.
- Barra de progresso no topo, rolagem suave, acordeão de FAQ e demais seções descritivas (Problem, Solution, Origin, Creators, Package, Testimonials, CTA, FAQ).
- Efeito de partículas da hero removido, mantendo o fundo limpo e estável.

## 🔗 Canais de Entrada / URIs
- **`/index.html`** – Landing page principal com todas as seções e CTAs.
- Âncoras internas: `#hero`, `#solution`, `#package`, `#testimonials`, `#problem`, `#faq` (acessadas via menu e botões).

## 🚫 Funcionalidades Não Implementadas
- Integração com formulários de captura ou automações de e-mail.
- Métricas/analytics ou disparo de eventos personalizados.
- Backend ou persistência de dados (todo o conteúdo é estático no momento).

## 🔜 Próximos Passos Recomendados
1. Substituir o arquivo `images/logo-footer.jpg` assim que o link oficial estiver acessível (o download atual retornou HTTP 403, por isso foi mantido o arquivo anterior com o novo nome).
2. Avaliar inclusão de prova social adicional (vídeos ou depoimentos em carrossel) para aumentar conversão.
3. Configurar ferramentas de monitoramento (Pixel, Google Analytics) caso desejado.
4. Publicar o site pela aba **Publish** para disponibilizar o link público.

## 🌐 URLs Públicas
- **Landing page:** `index.html` (publique pela aba **Publish** para gerar o link público).
- **Checkout:** https://pay.kiwify.com.br/GMsuKhV

## 🧱 Estruturas de Dados e Serviços Utilizados
- Conteúdo puramente estático em HTML/CSS/JS.
- Nenhum uso do Table API ou outros serviços de dados neste momento.

## 📁 Estrutura de Pastas
```
.
├── index.html
├── images/
│   ├── logo-header.jpg
│   ├── logo-footer.jpg
│   ├── logo-suellen-header.jpg (backup)
│   └── logo-suellen-footer.jpg (backup)
└── README.md
```

## 📝 Observações
- O smooth scroll agora ignora links com `href="#"`, evitando erros no console.
- O menu mobile abre corretamente sobrepondo o overlay graças ao ajuste de `z-index`.
- Hero (desktop e mobile): cards “E-book”, “Exercícios Práticos” e “Aulão” preservam as dimensões originais, com ícones nivelados na mesma linha, textos alinhados e espaçamentos interno superior/inferior espelhados para distribuição uniforme.
- Responsividade aprimorada na hero: ajustes de gap e largura garantem que os três cards e os ícones “+” permaneçam na mesma linha sem ultrapassar as margens nas telas mobile.
- Ícones principais da seção “Você sabe o que precisa mudar…” (fa-user-circle e fa-graduation-cap) reposicionados com espaçamento calibrado para alinhamento vertical dos bullets e respiro uniforme em relação aos títulos.
- Ajustada a pseudo-marcação de check na lista “EXERCÍCIOS PRÁTICOS” para que o símbolo fique alinhado ao primeiro termo de cada item, refinando novamente o espaçamento para manter o ícone colado ao texto mesmo em linhas quebradas, sem alterar a formatação textual.
- No desktop, a frase “Sem processos confusos…” aparece centralizada logo após o subtítulo e o container de destaque ocupa maior largura, com os cards “No seu ritmo” e “Prática real” posicionados abaixo dele.
- Botão “Comprar Agora” do header mantém o texto branco em hover, foco e clique, preservando o destaque do CTA.
- A seção de preço da CTA agora se ajusta automaticamente no mobile, centralizando o valor e mantendo os elementos alinhados.
- Botão principal da CTA centralizado horizontalmente e com largura ajustada para permanecer contido dentro do card em todos os breakpoints.
- Perguntas Frequentes com botões acessíveis (`aria-expanded`, `aria-controls`) e transições suaves, replicando a experiência mobile da landing original.
- O efeito de partículas foi removido e não há elementos animados adicionais que possam causar scroll lateral indesejado.
- Para colocar o projeto online, utilize a aba **Publish** da plataforma.
