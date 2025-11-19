# YouTube Semantic Layout

Projeto de clone do YouTube construído com HTML5 e CSS3 semânticos para demonstrar o uso prático das tags semânticas do HTML.

Cada tag utilizada é explicada no código HTML com comentários detalhados sobre sua função, contexto de uso e impacto na acessibilidade/SEO. Este README complementa essas explicações com descrições mais aprofundadas.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica seguindo as melhores práticas de acessibilidade
* **CSS3:** Estilização responsiva com Flexbox e Grid
* **ARIA:** Atributos de acessibilidade para reforçar a semântica

---

## 📚 Estrutura HTML Semântica

### Tags de Estrutura Principal

| Tag | Função | Justificativa de Uso |
| :--- | :--- | :--- |
| `<nav>` | Seção de navegação | Agrupa os links de navegação principal do site (menu lateral e superior) |
| `<main>` | Conteúdo principal | Envolve todo o conteúdo único da página, separando-o do header e sidebar |
| `<section>` | Seção temática | Agrupa logicamente diferentes áreas como "Vídeos em Alta", "Recomendados" |
| `<article>` | Conteúdo independente | Cada vídeo individual que pode existir de forma autônoma |
| `<aside>` | Conteúdo complementar | Sidebar com canais sugeridos e informações secundárias |
| `<footer>` | Rodapé | Informações de copyright e links institucionais |

### Tags de Conteúdo Específico

| Tag | Propósito | Justificativa de Uso |
| :--- | :--- | :--- |
| `<h1>`-`<h3>` | Hierarquia de títulos | Estrutura semântica: H1 para título principal, H2 para seções, H3 para vídeos |
| `<figure>` | Mídia com contexto | Agrupa thumbnail do vídeo com suas informações relacionadas |
| `<figcaption>` | Legenda da mídia | Fornece título e descrição do vídeo para o thumbnail |
| `<img>` | Imagens | Thumbnails dos vídeos e avatares dos canais com alt text descritivo |
| `<time>` | Informação temporal | Marca semanticamente quando o vídeo foi publicado |
| `<address>` | Informações de contato | Dados do canal/criador do conteúdo |

---

## 📖 Explicações Detalhadas das Tags

### nav
Representa seções de navegação da página, sendo fundamental para a estrutura de um site como o YouTube. No contexto deste projeto, é utilizada tanto para o menu lateral quanto para a navegação superior, permitindo que leitores de tela identifiquem rapidamente as áreas de navegação. Para SEO, estrutura hierarquicamente os links do site, facilitando a indexação e compreensão da arquitetura da informação pelos motores de busca.

### main
Define o conteúdo principal do documento, sendo essencial em layouts complexos como o YouTube. Esta tag permite que usuários de tecnologias assistivas pulem diretamente ao conteúdo principal, ignorando navegação e sidebars. Para motores de busca, identifica claramente qual é o conteúdo mais relevante da página, melhorando a indexação e o ranking nos resultados de pesquisa.

### section
Agrupa conteúdo relacionado tematicamente, sendo ideal para organizar diferentes categorias de vídeos no YouTube. Melhora significativamente a estrutura semântica do documento para SEO, permitindo que motores de busca compreendam a organização do conteúdo. Para acessibilidade, permite que tecnologias assistivas naveguem entre seções distintas, oferecendo uma experiência mais organizada aos usuários.

### article
Representa conteúdo independente e autocontido, perfeito para cada vídeo individual no YouTube. É fundamental para SEO pois define unidades de conteúdo que podem ser distribuídas independentemente, facilitando a indexação de vídeos específicos. Para acessibilidade, permite que leitores de tela identifiquem cada vídeo como uma unidade completa de informação.

### aside
Define conteúdo complementar ao conteúdo principal, ideal para sidebars com canais sugeridos e informações secundárias. Melhora a acessibilidade permitindo que usuários de leitores de tela identifiquem facilmente conteúdo secundário versus principal. Para SEO, ajuda motores de busca a distinguir entre conteúdo principal e complementar, evitando que informações secundárias diluam a relevância do conteúdo principal.

### footer
Representa o rodapé de uma seção ou documento, essencial para organizar informações institucionais do YouTube. Para acessibilidade, fornece um local previsível para informações de contexto, contato e navegação secundária. É importante para SEO ao organizar metadados, links relacionados e informações corporativas que agregam credibilidade ao site.

### h1, h2, h3
Definem hierarquia de cabeçalhos, sendo cruciais para a estrutura semântica do YouTube. São fundamentais para SEO pois estruturam o conteúdo de forma que motores de busca compreendam a importância relativa de cada seção. Para acessibilidade, são essenciais pois permitem que usuários de leitores de tela naveguem rapidamente entre seções usando atalhos de teclado específicos para cabeçalhos.

### figure e figcaption
Agrupam conteúdo visual com sua legenda, sendo essenciais para thumbnails de vídeos no YouTube. Para acessibilidade, fornecem contexto completo para imagens e vídeos, permitindo que usuários com deficiência visual compreendam o conteúdo visual através das legendas. São importantes para SEO ao associar descrições textuais ao conteúdo visual, tornando-o indexável e compreensível pelos motores de busca.

### img
Incorpora imagens no documento, sendo fundamental para thumbnails e avatares no YouTube. É crucial para acessibilidade quando usado com atributo alt descritivo, permitindo que leitores de tela descrevam as imagens para usuários com deficiência visual. Para SEO, fornece conteúdo visual indexável pelos motores de busca através dos atributos alt e title.

### time
Representa datas e horários específicos, perfeita para marcar quando vídeos foram publicados no YouTube. Melhora a acessibilidade fornecendo informações temporais estruturadas que podem ser interpretadas corretamente por tecnologias assistivas. Para SEO, facilita que motores de busca compreendam e indexem dados temporais, permitindo filtros por data e melhor organização cronológica do conteúdo.

### address
Define informações de contato, ideal para dados dos criadores de conteúdo no YouTube. É importante para acessibilidade ao identificar claramente dados de contato e autoria para usuários de tecnologias assistivas. Para SEO, é valioso ao fornecer informações estruturadas sobre autoria e contato, contribuindo para a credibilidade e autoridade do conteúdo nos algoritmos de busca.

---

## ♿ Atributos ARIA para Acessibilidade

O projeto utiliza atributos ARIA (Accessible Rich Internet Applications) para reforçar a acessibilidade em elementos-chave:

### Atributos ARIA Implementados

| Atributo | Elemento | Justificativa de Uso |
| :--- | :--- | :--- |
| `role="region"` | Seção de vídeos | Identifica a área principal de conteúdo para navegação por landmarks |
| `aria-labelledby` | Seção de vídeos | Conecta a seção ao seu título descritivo para contexto |
| `role="complementary"` | Seção Shorts | Define conteúdo complementar distinto do principal |
| `aria-describedby` | Seção Shorts | Fornece descrição adicional sobre o tipo de conteúdo |
| `role="navigation"` | Sidebar | Reforça a semântica de navegação para tecnologias assistivas |
| `aria-label` | Sidebar | Fornece rótulo descritivo para a área de navegação |

### Explicações Detalhadas dos Atributos ARIA

#### role="region" + aria-labelledby
Utilizado na seção principal de vídeos para criar um landmark identificado por leitores de tela. O `aria-labelledby` conecta a seção ao título "Vídeos recomendados" (oculto visualmente com `.desc-only`), permitindo que usuários de tecnologias assistivas compreendam rapidamente o propósito da área. Isso melhora significativamente a navegação por landmarks, uma funcionalidade essencial para usuários de leitores de tela.

#### role="complementary" + aria-describedby
Aplicado na seção de Shorts para identificar este conteúdo como complementar ao principal. O `aria-describedby` referencia uma descrição oculta que explica o que são Shorts, fornecendo contexto adicional para usuários que podem não estar familiarizados com este formato de vídeo. Esta combinação garante que a hierarquia de conteúdo seja clara para tecnologias assistivas.

#### role="navigation" + aria-label
Implementado na sidebar para reforçar sua função de navegação, mesmo já sendo um elemento `<aside>` com `<nav>` interno. O `aria-label` fornece um rótulo claro "Menu de navegação principal", eliminando qualquer ambiguidade sobre a função desta área. Isso é especialmente útil quando há múltiplas áreas de navegação na página, permitindo distinção clara entre elas.