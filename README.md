# Projeto Integrador - UniBus

Landing page institucional focada em suporte e transporte universitario, desenvolvida em HTML e CSS puros.

## Visao Geral

O UniBus foi pensado para centralizar informacoes de mobilidade academica, com foco em:

- apoio ao estudante
- organizacao de trajetos e caronas
- visualizacao de pontos de transporte

O projeto utiliza tema claro/escuro (CSS-only), layout responsivo e secoes informativas para orientar o usuario de forma rapida.

## Funcionalidades Implementadas

- Hero section com chamada principal e botoes de acao
- Secao Sobre com cards de beneficios da plataforma
- Secao Transportes com:
	- mapa incorporado (OpenStreetMap)
	- campo de busca visual
	- pins de cidades/terminais de referencia
	- status em tempo real com indicadores por cor
- Secao Servicos com grid de recursos da plataforma
- Secao Ajuda com contatos e formulario de email
- Pagina de manutencao para links ainda nao implementados
- Rodape institucional com links legais e paginas auxiliares

## Tecnologias

- HTML5
- CSS3
- Google Fonts (Inter + Material Symbols)
- OpenStreetMap Embed

## Estrutura Principal

```text
index.html
README.md
app/
	pages/
		em-manutencao.html
		acessibilidade.html
		politica-de-cookies.html
		politica-de-privacidade.html
		status-do-sistema.html
		termos-de-uso.html
	style/
		style.css
```

## Design e Responsividade

- Abordagem mobile-first
- Breakpoints principais para tablet e desktop
- Componentes com layout flex/grid
- Adaptacao visual para modo claro e modo escuro

## Tema Claro/Escuro

O alternador de tema funciona sem JavaScript, utilizando checkbox e variaveis CSS para trocar cores globais e componentes.

## Como Executar

1. Clone ou baixe o projeto.
2. Abra a pasta no VS Code.
3. Execute o arquivo `index.html` no navegador (ou com extensao de Live Server).

## Paginas de Apoio

Links nao finalizados podem apontar para a pagina de manutencao:

- `app/pages/em-manutencao.html`

Assim, o usuario sempre recebe uma resposta visual consistente, mesmo quando a funcionalidade ainda esta em desenvolvimento.