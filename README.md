# YouTube Semantic Layout

## Descrição do Projeto

Este projeto é um clone educacional do YouTube desenvolvido com foco em HTML5 semântico e acessibilidade. O objetivo é demonstrar o uso correto das tags semânticas do HTML5 para criar uma estrutura de documento bem organizada, acessível e otimizada para SEO.

## Verificação dos Requisitos da Atividade

### ✅ Tags Semânticas Obrigatórias Implementadas

- ✅ **`<!DOCTYPE html>` e `html lang="pt-br"`**: Presentes em ambas as páginas
- ✅ **`header`**: Cabeçalho com navegação em ambas as páginas
- ✅ **`nav`**: Múltiplas navegações com listas de links
- ✅ **`main`**: Conteúdo principal em ambas as páginas
- ✅ **`section`**: Múltiplas seções organizando conteúdo
- ✅ **`article`**: Vídeos, posts e playlists como conteúdo independente
- ✅ **`aside`**: Barra lateral no index.html e seção complementar no channel.html
- ✅ **`footer`**: Rodapé com informações do site
- ✅ **`h1` a `h3`**: Hierarquia correta de cabeçalhos
- ✅ **`p`, `strong`, `em`**: Parágrafos e ênfases semânticas
- ✅ **`figure` e `figcaption`**: Agrupamento de imagens com legendas
- ✅ **`img` com alt`**: Textos alternativos descritivos
- ✅ **`time` com datetime`**: Datas e durações com formato legível por máquina
- ✅ **`address`**: Informações de contato do criador
- ✅ **`table`, `caption`, `thead`, `tbody`, `tfoot`**: Tabela de estatísticas completa
- ✅ **`details` e `summary`**: Descrição expansível do canal
- ✅ **`mark`**: Destaque de hashtags e crescimento
- ✅ **`abbr` com title`**: Abreviações HTML, CSS, ARIA
- ✅ **`form` com `fieldset` e `legend`**: Formulário de contato acessível
- ✅ **`dialog`**: Modal demonstrativo com botão de abertura

### ✅ Atributos ARIA Implementados (Bônus Técnico)

- ✅ **`role`**: banner, main, complementary, search, article, tablist, tab, tabpanel
- ✅ **`aria-label`**: Descrições acessíveis para botões e navegações
- ✅ **`aria-describedby`**: Conecta campos de formulário com descrições auxiliares
- ✅ **`aria-labelledby`**: Associa painéis com suas abas correspondentes
- ✅ **`aria-selected`**: Estado de abas ativas/inativas
- ✅ **`aria-controls`**: Relaciona controles com conteúdo controlado

### ✅ Estrutura de Arquivos Completa

- ✅ **index.html**: Página principal funcional
- ✅ **templates/channel.html**: Página do canal
- ✅ **assets/css/style.css**: Estilos da página principal
- ✅ **assets/css/channel.css**: Estilos da página do canal
- ✅ **assets/img/imagem_azul.png**: Imagem utilizada em figure
- ✅ **README.md**: Este arquivo com explicações detalhadas
- ✅ **atividade.md**: Requisitos originais da atividade

## Tags Semânticas Utilizadas

### Estrutura Básica
- **`<!DOCTYPE html>`**: Define o documento como HTML5, garantindo renderização adequada pelos navegadores modernos.
- **`html lang="pt-br"`**: Especifica o idioma do documento, melhorando acessibilidade para leitores de tela e SEO.

### Elementos Estruturais
- **`header`**: Define o cabeçalho da página contendo navegação e marca. Melhora acessibilidade fornecendo marco de navegação para leitores de tela.
- **`nav`**: Agrupa links de navegação, facilitando identificação por tecnologias assistivas e melhorando estrutura semântica.
- **`main`**: Contém o conteúdo principal da página, essencial para marcos de acessibilidade e identificação do conteúdo primário.
- **`section`**: Agrupa conteúdo relacionado tematicamente, melhorando estrutura do documento para SEO e organização lógica.
- **`article`**: Representa conteúdo independente e reutilizável (vídeos, posts), melhorando estrutura SEO e significado semântico.
- **`aside`**: Define conteúdo complementar na barra lateral, separando claramente conteúdo principal da navegação auxiliar.
- **`footer`**: Marca o rodapé da página com informações secundárias, completando a estrutura semântica do documento.

### Elementos de Conteúdo
- **`h1` a `h3`**: Hierarquia adequada de cabeçalhos para estrutura de conteúdo, essencial para acessibilidade e SEO.
- **`p`**: Parágrafos de texto com significado semântico claro.
- **`strong`**: Enfatiza importância de texto (ex: "Patrocinado"), melhor que `<b>` para acessibilidade.
- **`em`**: Enfatiza texto com ênfase (ex: nome do canal), semanticamente superior ao `<i>`.

### Elementos de Mídia e Dados
- **`figure` e `figcaption`**: Agrupa imagens com suas legendas, fornecendo contexto semântico e melhorando acessibilidade.
- **`img` com alt`**: Imagens com texto alternativo descritivo para acessibilidade e SEO.
- **`time` com datetime`**: Marca temporal com formato legível por máquina, melhorando SEO e acessibilidade.
- **`data`**: Representa dados com valor legível por máquina (visualizações, inscritos), otimizando para mecanismos de busca.

### Elementos de Informação
- **`address`**: Indica informações de contato do criador/canal, fornecendo contexto semântico adequado.
- **`abbr` com title`**: Abreviações com expansão completa (HTML, CSS, ARIA), melhorando compreensão e acessibilidade.
- **`mark`**: Destaca texto relevante (hashtags, crescimento), fornecendo ênfase visual e semântica.

### Elementos de Dados Estruturados
- **`table`, `caption`, `thead`, `tbody`, `tfoot`**: Estrutura tabular para estatísticas do canal, melhorando acessibilidade e organização de dados.

### Elementos Interativos
- **`details` e `summary`**: Conteúdo expansível para descrição do canal, melhorando experiência do usuário e organização.
- **`form` com `fieldset` e `legend`**: Formulário de contato com agrupamento semântico de campos, essencial para acessibilidade.
- **`dialog`**: Modal semântico para informações adicionais, fornecendo comportamento acessível para conteúdo sobreposto.

### Elemento de Busca
- **`search`**: Elemento semântico específico para funcionalidade de busca, melhorando identificação por tecnologias assistivas.

## Atributos ARIA Utilizados

### `role`
- **`role="banner"`**: Identifica o cabeçalho principal da página.
- **`role="main"`**: Marca o conteúdo principal para navegação por leitores de tela.
- **`role="complementary"`**: Identifica conteúdo da barra lateral como suplementar.
- **`role="search"`**: Especifica área de busca para tecnologias assistivas.
- **`role="tablist"`**: Define lista de abas para navegação por painéis.
- **`role="tab"`**: Identifica botões individuais de aba.
- **`role="tabpanel"`**: Marca painéis de conteúdo controlados pelas abas.

### `aria-label`
- **`aria-label="Menu principal"`**: Fornece descrição acessível para navegação.
- **`aria-label="Pesquisar vídeos"`**: Descreve função do campo de busca.
- **`aria-label="Abrir menu da conta"`**: Explica ação do botão de perfil.

### `aria-describedby`
- **`aria-describedby="name-help"`**: Conecta campos de formulário com suas descrições auxiliares, melhorando compreensão para usuários de leitores de tela.

### `aria-labelledby` e `aria-controls`
- **`aria-labelledby="videos-tab"`**: Associa painéis com suas abas correspondentes.
- **`aria-controls="videos-panel"`**: Indica qual conteúdo é controlado por cada aba.

## Benefícios Implementados

### Acessibilidade
- Estrutura semântica clara para navegação por leitores de tela
- Atributos ARIA adequados para elementos interativos
- Hierarquia de cabeçalhos consistente
- Textos alternativos descritivos para imagens
- Formulários com rotulagem adequada
- Sistema de abas acessível com ARIA

### SEO
- Estrutura HTML5 semântica reconhecida por mecanismos de busca
- Meta tags adequadas (description, author)
- Dados estruturados com elementos `time` e `data`
- Hierarquia de conteúdo clara com cabeçalhos
- Texto alternativo otimizado para imagens

### Manutenibilidade
- Código bem organizado e comentado
- Separação clara entre estrutura, apresentação e comportamento
- Uso de elementos semânticos apropriados reduz necessidade de classes CSS
- Estrutura lógica facilita futuras modificações

## Estrutura de Arquivos

```
youtube-semantic-layout/
├── index.html              # Página principal
├── templates/
│   └── channel.html        # Página do canal
├── assets/
│   ├── css/
│   │   ├── style.css      # Estilos da página principal
│   │   └── channel.css    # Estilos da página do canal
│   └── img/
│       └── imagem_azul.png # Imagem de exemplo
├── README.md              # Este arquivo
└── atividade.md          # Requisitos da atividade
```

## Como Visualizar

1. Abra o arquivo `index.html` em um navegador web moderno
2. Navegue para a página do canal clicando no avatar do perfil
3. Explore as diferentes seções e funcionalidades implementadas
4. Use ferramentas de desenvolvedor para inspecionar a estrutura semântica
5. Teste com leitores de tela para verificar acessibilidade

## Tecnologias Utilizadas

- HTML5 semântico
- CSS3 para estilização
- Google Fonts (Material Icons e Poppins)
- Atributos ARIA para acessibilidade aprimorada

## Conclusão

Todos os requisitos da atividade foram implementados com sucesso. O projeto demonstra o uso adequado de todas as tags semânticas obrigatórias, implementa atributos ARIA para acessibilidade aprimorada, e mantém uma estrutura de código bem organizada com comentários explicativos.