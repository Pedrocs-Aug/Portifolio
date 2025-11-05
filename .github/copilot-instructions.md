# Instruções para Agentes AI - Portfólio

Este documento fornece orientações essenciais para agentes AI trabalharem neste projeto de portfólio.

## Visão Geral do Projeto
Este é um projeto de portfólio pessoal com uma estrutura simples baseada em HTML. O projeto é focado em apresentar informações do desenvolvedor e seus projetos.

## Estrutura do Projeto
```
/
├── index.html      # Arquivo principal com a estrutura HTML
└── img/           # Diretório de imagens
    └── img1.jpg    # Imagem do perfil
```

## Componentes Principais

### 1. Seção Principal (`<main>`)
- Contém duas seções principais:
  - Seção de perfil com imagem e links sociais
  - Seção de projetos com lista de projetos

### 2. Navegação Social
- Localizada em `nav_buttons`
- Inclui botões para:
  - Instagram
  - GitHub
  - Facebook
  - LinkedIn
  - Download de CV

### 3. Seção de Projetos
- Localizada em `section_projects`
- Contém grade de 6 projetos
- Usa classe `btn` para estilização consistente

## Convenções de Nomenclatura
- Classes seguem o padrão `btn_nome-do-botao` para botões
- Seções são nomeadas com prefixo `section_`
- Navegação usa prefixo `nav_`

## Dicas para Desenvolvimento
1. Mantenha a consistência nas classes de botões usando o prefixo `btn_`
2. Imagens devem ser armazenadas no diretório `/img`
3. Mantenha a estrutura semântica HTML com `<section>`, `<nav>`, etc.

## Localização de Arquivos Importantes
- `index.html`: Contém toda a estrutura HTML do portfólio
- `img/img1.jpg`: Imagem principal do perfil