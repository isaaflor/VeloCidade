# VeloCidade — Portal de Anúncios de Veículos

Projeto da disciplina **Desenvolvimento Web 1** (UFU — Faculdade de Computação).

## Etapa 1 — UI/UX e Estrutura (Estática)

Esta entrega contém apenas **HTML e CSS** (sem framework, sem JavaScript funcional,
sem Bootstrap nas páginas públicas), conforme solicitado para a primeira etapa:

- Layout completo (cabeçalho, navegação, rodapé e conteúdo principal) em todas as páginas;
- Cards estáticos de veículos com dados de exemplo;
- Formulários sem envio real de dados (`onsubmit="return false;"`);
- Site responsivo (testado em telas de celular, tablet e desktop).

## Estrutura de arquivos

```
index.html                          → Página principal (pública)
veiculo.html                        → Detalhe do veículo + registro de interesse (pública)
login.html                          → Login (pública)
cadastro.html                       → Cadastro de anunciante (pública)
css/style.css                       → Estilo de todo o site (Flexbox/Grid, sem Bootstrap)
area-restrita/painel.html           → Painel principal da área restrita
area-restrita/novo-anuncio.html     → Criação de anúncio
area-restrita/meus-anuncios.html    → Listagem dos anúncios do usuário
area-restrita/anuncio-detalhe.html  → Detalhe de um anúncio (visão do anunciante)
area-restrita/interesses.html       → Mensagens de interesse recebidas
```

## Publicando no GitHub Pages

1. Crie um repositório no GitHub e envie todos os arquivos e pastas acima para a raiz do repositório
   (mantendo a pasta `css/` e `area-restrita/` como estão).
2. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`.
3. O GitHub vai gerar uma URL como `https://seu-usuario.github.io/nome-do-repo/`.
4. Acesse essa URL para conferir o site publicado.

## Observações

- As fotos dos veículos usam imagens de placeholder (picsum.photos) apenas para
  ilustrar o layout nesta etapa; substitua pelas fotos reais quando o back-end
  (Etapa 3) estiver implementado.
- Nas próximas etapas serão adicionados: validação de formulários com JavaScript
  (Etapa 2) e integração com PHP/MySQL via Ajax (Etapa 3), conforme o documento
  de instruções da disciplina.
- Lembre-se de validar as páginas em validator.w3.org e jigsaw.w3.org/css-validator
  antes da entrega final.
