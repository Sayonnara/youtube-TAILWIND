📝 Descrição Técnica do Projeto: Clone do YouTube com Tailwind CSS

📌 Resumo do Projeto
Este projeto é um clone visual do YouTube, desenvolvido com foco em HTML, JavaScript e Tailwind CSS.

Ele simula a interface principal da plataforma com menu lateral fixo, barra de pesquisa funcional, layout responsivo e uma galeria dinâmica de vídeos gerados por JavaScript.

🔧 Tecnologias Utilizadas
Tecnologia	Finalidade
HTML5	Estrutura semântica da página
Tailwind CSS	Estilização com classes utilitárias
JavaScript	Geração dinâmica dos cards de vídeo
Remix Icon	Ícones modernos para navegação e botões
Picsum Photos	API para geração de imagens aleatórias

📐 Arquitetura e Componentes

Header 
Barra fixa no topo da tela contendo:

Botão de menu lateral;

Logo do YouTube com marca “BR”;

Campo de busca com botão de pesquisa e microfone;

Ações de usuário (vídeo, notificação, perfil).

Sidebar 

Menu lateral fixo com:

Navegação principal (Início, Explorar, Inscrições, Histórico);

Canais inscritos (com ícones coloridos personalizados);

Responsivo com rolagem vertical se necessário.

Main

Área de conteúdo principal:

Barra de filtros (Tudo, Músicas, Podcast, etc);

Galeria de vídeos em grid com até 4 colunas.

Cards de Vídeo (gerados via JavaScript)
Renderizados dinamicamente a partir de um array de objetos contendo:

Título;

Canal;

Visualizações;

Tempo;

Duração;

Imagem aleatória.

💡 Funcionalidades Implementadas

Layout 100% responsivo com Tailwind grid e breakpoints;

Menu lateral e header fixos ao rolar a página;

Geração automática de vídeos simulados;

Utilização de ícones da Remix Icon;

Estilo limpo e moderno, inspirado na interface real do YouTube.

🔄 Melhorias Futuras (To-Do List)

Adicionar reprodução de vídeo embutida;

Implementar modo escuro com toggle;

Usar API real de vídeos (ex: YouTube API);

Filtro funcional por categoria;

Página de detalhes do vídeo (com player e comentários);

Componente reutilizável para cards.

🗂️ Organização do Código

index.html: Estrutura principal do site.

Script embutido no final da página com o array de vídeos e renderização DOM.

Uso exclusivo de CDN para Tailwind e RemixIcon, sem necessidade de instalação local.

![youtube](https://github.com/user-attachments/assets/3ca1de5e-bb46-447b-b6de-3ad28db9966a)
