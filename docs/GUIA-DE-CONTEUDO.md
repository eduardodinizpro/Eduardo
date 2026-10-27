# Guia de conteúdo

## Adicionar um projeto
1. Copie `templates/PROJETO.md` para a área correspondente em `portfolio/`.
2. Use um nome curto, sem espaços ou acentos: `nome-do-projeto.md`.
3. Preencha apenas fatos confirmados. Mantenha “[PREENCHER: ...]” nos campos pendentes.
4. Prepare as imagens para a web em `site/assets/images/`.
5. Atualize manualmente a seção “Trabalhos” de `site/index.html`.
6. Revise créditos, autorizações e links antes de enviar as mudanças.

## Imagens
Use nomes descritivos, como `nome-do-projeto-01.webp`. Redimensione para a resolução necessária; busque arquivos de poucas centenas de KB quando possível. Escreva texto alternativo que descreva o conteúdo. Ao inserir uma imagem abaixo da primeira tela, use `loading="lazy"` e dimensões explícitas.

## Vídeos
Prefira links para uma plataforma de exibição escolhida por você. `site/assets/videos/` destina-se apenas a prévias leves. Registre duração, função desempenhada, créditos e link na ficha do projeto. Não suba gravações brutas.

## Organização de produção
Guarde roteiros, autorizações, contratos e dados privados fora do repositório. Em `portfolio/producao-audiovisual/`, publique apenas sínteses aprovadas e créditos.

## Editar o site
O site usa HTML e CSS, sem dependências. Os caminhos dos recursos são relativos, permitindo servir a pasta `site/` como raiz em uma hospedagem estática. Mantenha `index.html` e `assets/` juntos. Abra `site/index.html` para conferir localmente.

Para adicionar contato, substitua a indicação pendente por um endereço confirmado; um link de e-mail pode usar `mailto:`. A base não contém formulário.

## Antes de publicar
Confira celular e computador, navegação pelo teclado, contraste, descrições de imagens, links e ortografia. Procure “[PREENCHER” e “A preencher” para localizar campos restantes.
