## Ferramentas que auxiliam na construção de aplicações web responsivas

- ATENÇÃO: para melhor aproveitamento, abra os links em nova aba (Botão direito do mouse > abrir link em nova guia )

<h4>💻 <a href="https://responsively.app/" target="_blank">Responsively</a> </h4>
<h4>💻 <a href="https://www.base64.com.br/tools/responsivetest//" target="_blank">Base64</a> </h4>
<h4>💻 <a href="https://www.websiteplanet.com/pt-br/webtools/responsive-checker/" target="_blank">Websiteplanet</a> </h4>





## Antes de tudo, você já conhece Chrome DevTools?
- além de muitas outras coisas, com o DevTools podemos simular uma janela de visualização e testar a responsividade de nosso layout. É simples: na tela do seu layout, dê um clique no botão direito do mouse e depois em inspecionar. Na aba que se abriu, na parte superior esquerda, clique no seguinte ícone: <img alt="Alternar barra de ferramentas do dispositivo" src="https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format" decoding="async" height="32" loading="lazy" sizes="(min-width: 30px) 30px, calc(100vw - 48px)" srcset="https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=30 30w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=34 34w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=39 39w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=44 44w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=51 51w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=58 58w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=60 60w" width="30">. Pronto. Nesta janela de visualização, você poderá testar seu layout em formatos fixos ou no formato livre (arrastando a janela nas direções horizontal e vertical. Aliás, o "formato livre" é um teste indispensável para evitarmos quebras de layout).

## E o Firefox Developer Edition?
- No Mozila, o processo é o mesmo. Basta inspecionar a página com o botão direito do mouse e ir para o modo de desing responsivo, cliando em:  <img alt="Alternar barra de ferramentas do dispositivo" src="https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format" decoding="async" height="32" loading="lazy" sizes="(min-width: 30px) 30px, calc(100vw - 48px)" srcset="https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=30 30w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=34 34w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=39 39w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=44 44w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=51 51w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=58 58w, https://wd.imgix.net/image/admin/9FiBHFCzfPgP8sy6LMx7.png?auto=format&amp;w=60 60w" width="30">.
- O Mozila faz uma inspeção mais precisa dos elementos da página. É muito bom!
- Não encontrei a opção de reduzir o tamanho da janela (como acontece no Chrome DevTools). Reduzindo o zoom da janela, podemos visualizar melhor resoluções maiores de, por exemplo, 1920 x 1080. No DevTools do Chrome isso é possível. No Mozila, parece que não temos ainda essa funcionalidade.

## Por que usar?
- O DevTolls do Chrome e do Mozila, embora úteis, não são, das ferramentas disponíveis, as mais produtivas quando precisamos verificar **como está o nosso layout numa variedade grande de telas**.
- Não é nada produtivo testar layouts tela por tela, tal como fazemos com os DevTools já conhecidos.
- produtividade: visualizar nosso layout em diversas resoluções, usando menos tempo para isso (O Responsively é o mais ideal para produtividade0

## Devo abandonar os DevTools?
- Não. Os DevTools e essas aplicações devem ser usadas conjuntamente.

## Qual a finalidade?
- Essas aplicações expõem o estado do nosso layout em tempo real nas diversas resoluções de telas. 

## É confiável?
- Os DevTools e essas aplicações oferecem relativa segurança. Precisamos considerar que são simulações aproximadas. Por exemplo, para sabermos com 100% de certeza como nosso layout se comporta na tela do Iphone12, somente com o Iphone 12 em mãos. Mas a falta de certeza faz parte do processo. O teste final sempre é do usuário. Ele é quem vai dizer se nosso layout quebra ou não. Gosto da ideia de que trabalhamos sempre com versões, nunca com sistemas finalizados. Na verdade, nossos testes não evitam transtornos, evitam maiores transtornos.
- Já ajustou o código e o navegador não reflete as mundanças? Cuidado com o cache! CTR + R e CTRL + F5, uma ou duas vezes, geralmente resolvem o problema.




