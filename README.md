# OCR - Optical Character Recognition

Vamos utilizar o [Ai Vision Studio](https://portal.vision.cognitive.azure.com/gallery/featured) do Azure para extrair textos de imagens utilizando as ferramentas do próprio portal. Para isso separei 3 inputs para fazermos os testes: um exemplo de cupom fiscal e uma imagem com uma mensagem de bom dia.

![001](https://uploaddeimagens.com.br/images/004/744/849/original/001.jpg?1708542196)

Essa é a página inicial do Vision Studio.

## Azure AI Vision Studio

Para podermos utilizar os serviços do Vision Studio é necessário ter criado um recurso do [Azure AI Services](https://portal.azure.com/#home) anteriormente.

Dentro do Vision Studio clique em **View all resources** e defina o recurso criado como padrão.

![002](https://uploaddeimagens.com.br/images/004/744/872/original/002.jpg?1708542400)

Caso o recurso não apareça como na imagem, é só clicar em [+ Create a new resource] conforme na imagem acima e defini-lo como default.

## Optical character recognition

De volta à página inicial do Vision Studio vamos selecionar a opção **Optical character recognition** e depois o serviço **Extract text from images** conforme abaixo.

![003](https://uploaddeimagens.com.br/images/004/744/896/original/003.jpg?1708542865)

Dentro do serviço de OCR clique em Browse for a file para encontrar a imagem desejada em seu computador, confirme e aguarde o resultado em Detected attributes.

![azure4](https://uploaddeimagens.com.br/images/004/740/431/original/04.jpg?1708004628)

Repita o processo quantas vezes desejar. Teste com outros tipos de imagens, imagens contendo escritas a mão, notas fiscais, etc.

![azure5](https://uploaddeimagens.com.br/images/004/744/947/original/output2.jpg?1708543821)

Veja que ele consegue identificar até mesmo pequenos textos que não necessariamente têm relação com a mensagem principal.

## Conclusão

O serviço de OCR da Azure Vision Studio tem um potencial incrível para diversas aplicações, seja importar fotos de notas fiscais para o sistema, ou até mesmo extrair o conteúdo de documentos digitalizados, podendo assim resumir as principais informações. Mas uma coisa ainda mais incrível é a inclusão que essa ferramenta pode gerar. Imagine extrair textos de imagens aliado com a ferramenta de transformar texto em áudio. Uma pessoa com limitações visuais poderia ter um maior proveito das tecnologias com essas ferramentas de acessibilidade.
