# POC-3---Media-Queries
Print da Impressão:
![image](https://github.com/user-attachments/assets/b4553b12-d02e-475b-8b24-91f419efa3d6)


Explicação Geral:
Media Queries são uma parte essencial do CSS responsivo, permitindo que você aplique estilos diferentes com base nas características do dispositivo, como largura da tela ou orientação.
Elas são usadas para criar sites que se adaptam a diferentes dispositivos (exemplo: smartphone, tablet e desktop), proporcionando uma boa experiência de usuário em qualquer tamanho de tela.

 Media Queries para diferentes larguras de dispositivos
Estas media queries foram definidas para ajustar o layout em diferentes dispositivos, como smartphones, tablets e desktops, baseando-se na largura da tela:

Para Smartphones (largura até 480px):

![image](https://github.com/user-attachments/assets/01f678ae-4a12-4a65-8b04-d5a6e4d6aa4b)

O que faz:
A largura máxima de 480px é usada para smartphones.
O menu muda para uma coluna vertical, o que é mais fácil de navegar em telas pequenas.
A galeria de imagens é ajustada para ter apenas uma coluna, o que faz com que cada imagem ocupe toda a largura disponível, o que é ideal para telas pequenas.
O padding do conteúdo também é reduzido para deixar o layout mais compacto e mais fácil de visualizar em uma tela pequena.

Para Desktops (largura mínima de 769px):

![image](https://github.com/user-attachments/assets/ca6d99be-90d9-47fa-9dcf-4b215df243d1)

O que faz:
Esta media query se aplica a dispositivos com telas largas, como desktops (largura acima de 769px).
A galeria de imagens é disposta em 4 colunas, aproveitando o espaço adicional para mostrar mais imagens lado a lado.
O conteúdo tem um padding maior (40px), tornando o layout mais espaçado e confortável para leitura em telas grandes.

Media Queries para diferentes orientações (portrait e landscape)
Para Modo Landscape (orientação horizontal):

![image](https://github.com/user-attachments/assets/ebb3ec96-9a35-4e80-9671-bf8cb12b9487)

O que faz:
Quando o dispositivo está em landscape (orientação horizontal), o código ajusta a altura das imagens na galeria para 200px.
Isso é útil para manter o layout mais equilibrado quando a tela é mais larga do que alta, como acontece ao segurar um tablet ou smartphone de lado.

Benefícios do uso das media queries:
Experiência de usuário aprimorada: O layout se adapta automaticamente ao tamanho e formato da tela, oferecendo uma navegação otimizada em diferentes dispositivos.
Eficiência no uso do espaço: Em smartphones, a galeria é exibida em uma coluna, em tablets em duas colunas e em desktops em quatro colunas. Isso garante que o conteúdo use o espaço disponível de forma eficaz.
Impressão otimizada: A versão para impressão do conteúdo exclui elementos desnecessários e ajusta o texto para uma leitura melhor no papel.


