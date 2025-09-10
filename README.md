# Projeto Design

[link para o video base](https://youtu.be/0pKBT0tj7Ik?si=PnS3uilrs4r7ysDg)

<p>Projeto em html e css com inovações de design e estilo e algumas lições aprendidas</p>

## lições aprendidas

- scroll-behavior: util para efeitos de menu ancora, onde o movimento gerado ocorre de maneira mais suave
- mix-blend-mode color dodge: um modelo de cor de texto que mixa com o fundo, gerando um efeito sutil combinado com o background
- display flex em tags genericas: se o conteúdo do site tem várias seções com display flexivel, aplicar display flex em uma tag section economiza codigo, deixando para cada uma apenas o código extra necessário de configurações adicionais de alinhamento
- opacidade em texto: usar opacity 0,5 em uma tag p por exemplo, faz com que todos os textos tenham cores menos vivas sem ter que alterar cores diretamente.
- porcentagem em larguras e tamanhos: usar vh, vw e % em larguras e tamanhos ajuda a responsividade do site, criando tamanhos mais dinamicos
- backdrop-filter blur: usando a função blur em backdrop-filter cria seções e cards semi-transparentes, com efeito de blur aplicado
- gap: uso de gap em seções flex pode substituir o uso de margin em elementos filhos
- webkit-box: uso de -webkit-box, line-clamp e box-orient para display em paragrafos e adicionando um limite de linhas é uma solução mais moderna para limitar texto em paragrafos com mais de uma linha, aplicando ainda text-overflow elipsis automaticamente
- uso de seções de transição before e after: aplicando seções before e after com conteudo nulo porém tamanho consideravel e cor de fundo em gradiente conseguimos criar transições de backgrounds suaves, tendo porém que aplicar aos elementos das seções um z-index para camadas acima
- filtro saturate em imagens: aplicando a pseudo-função saturate em um filter de img, conseguimos deixar imagens em preto e branco facilmente
