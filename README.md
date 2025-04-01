# Desafio 01: Landing Page com HTML e CSS

Bem-vindo(a) ao primeiro desafio da Trilha de CSS da DIO! Neste desafio, você irá construir sua primeira Landing Page utilizando HTML e CSS, colocando em prática os fundamentos de estilização, propriedades básicas e unidades de medidas relativas e absolutas.

[Clique aqui](https://micheleambrosio.github.io/dio-trilha-css-desafio-01/) para acessar o resultado final da Landing Page do desafio.

![image](https://user-images.githubusercontent.com/55519539/183538055-6cce606c-7d1d-4d15-a4be-ffeb5b37c956.png)

Para participar, basta fazer um **fork** do repositório para o seu GitHub e iniciar as modificações no projeto. Dentro da pasta *main*, você encontrará as imagens e o arquivo HTML com toda a estrutura básica da página. Sua tarefa é conectar o HTML às folhas de estilo para que a estilização funcione corretamente.

[Link do Figma](https://www.figma.com/file/3PiokoJj9IhGDnNiWAJbz7/DIO---Desafio-01?node-id=2%3A6) contém o protótipo do desafio, servindo como base para o layout e estilo.

*Observação:* Para aplicar textos com efeito gradiente, utilize a propriedade CSS background-clip e, para alguns navegadores, acrescente -webkit-background-clip: text.

Caso tenha alguma dúvida ou queira comparar seu resultado com o final, o site está disponível na branch *final*, que pode ser acessada com:
```
git checkout final
```

## Modificações no index.html

Foram adicionadas as regras CSS diretamente dentro da tag <style> do arquivo HTML, proporcionando a estilização completa da página. As principais alterações implementadas foram:

- Estilos globais aplicados ao body, definindo fonte, margens, padding, line-height e background.
- Personalização do header (classe banner), com fundo claro, padding, alinhamento central e estilo diferenciado para título, parágrafo e botão.
- Criação de uma seção de conteúdo (main) estruturada para listar os módulos do curso, aplicando flexbox na lista de módulos e estilizando cada item individualmente.
- Definição de uma seção de destaque (#transform-world) com fundo colorido, texto centralizado e tamanho de fonte aumentado.
- Estilização da seção de desafios profissionais (#professional-challenges), incluindo regras para cabeçalho, ajustes em imagens (tamanho e responsividade) e formatação dos parágrafos.
- Formatação do footer com fundo escuro, texto claro, e links com destaque e imagem da marca devidamente configurada.

Essas modificações garantem uma boa responsividade e uma aparência consistente em toda a página.
