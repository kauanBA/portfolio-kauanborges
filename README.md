# Portfólio — Kauan Borges

Portfólio pessoal responsivo desenvolvido com HTML, CSS e JavaScript puro.

## Como visualizar

1. Extraia o arquivo ZIP.
2. Abra `index.html` no navegador.

Para executar por um servidor local (recomendado):

```bash
cd portfolio-kauan-borges
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Recursos

- Layout responsivo inspirado na referência enviada.
- Tema escuro: `#0b1320` (fundo predominante), `#1f2a44` (cartões e elementos secundários) e `#f2efe8` (tipografia).
- Tipografia Bricolage Grotesque e JetBrains Mono.
- Seletor de idioma PT / EN / ES, com preferência salva no navegador.
- Indicador de disponibilidade para oportunidades.
- Assistente: robô 3D com cabeça em formato de monitor (three.js), nas cores da paleta. Arraste para girar; clique para ele acenar e trocar a mensagem; duplo clique para virá-lo de frente.
- Foto de perfil vinculada ao avatar público do GitHub (`kauanBA`).
- Seções Sobre, Tecnologias, Projetos, Experiência, Formação e Contato.

## Observações

- O robô usa three.js carregado por CDN (cdnjs); sem internet aparece um 🤖 no lugar.
- A fonte e a foto de perfil são carregadas de serviços externos; é necessária conexão à internet para exibi-las. O site mantém fontes alternativas e iniciais de perfil como fallback.
- O assistente tem interações visuais e mensagens pré-definidas; ele não é um chatbot conectado a um modelo de IA.
- Os projetos estão descritos com base no currículo fornecido. O portfólio não inventa URLs individuais de repositórios que não foram informadas.
- Para substituir a foto de perfil por um arquivo local, troque o `src` da imagem `#profilePhoto` em `index.html` por um caminho como `assets/foto-perfil.jpg`.

- `assets/foto-perfil.jpg` já está incluída; para usá-la no lugar do avatar do GitHub, troque o `src` de `#profilePhoto` por `assets/foto-perfil.jpg`.
