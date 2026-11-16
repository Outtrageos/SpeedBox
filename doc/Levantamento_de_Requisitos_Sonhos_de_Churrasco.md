git# **Levantamento de Requisitos — Sonhos de Churrasco**

DOCUMENTAÇÃO DE REQUISITOS · PROJETO WEB INSTITUCIONAL

## **1. Descrição geral do sistema**

O sistema consiste no desenvolvimento de um site institucional para o restaurante **Sonhos de Churrasco**, com o propósito de apresentar a empresa, divulgar seus produtos e facilitar o contato entre o estabelecimento e seus clientes.

O site deverá possuir uma interface moderna, intuitiva e responsiva, permitindo que os visitantes conheçam o cardápio, consultem informações sobre entregas, acompanhem eventos e registrem avaliações sobre os serviços prestados.

A plataforma também deverá oferecer uma área administrativa para que os responsáveis pelo restaurante possam atualizar informações, produtos, preços e eventos publicados.

## **2. Objetivo principal**

Desenvolver um site que fortaleça a presença digital do restaurante Sonhos de Churrasco, facilitando a divulgação de seus serviços e melhorando a comunicação com os clientes.

O sistema deverá permitir que os visitantes consultem as opções de almoço e jantinhas com carne assada, solicitem informações sobre entregas, visualizem eventos e compartilhem suas experiências por meio de avaliações.

## **3. Público-alvo**

O público-alvo principal será composto por famílias que procuram refeições de qualidade, praticidade e opções de alimentação para diferentes ocasiões.

O site também deverá atender:

- Pessoas interessadas em solicitar refeições por entrega.
- Clientes que desejam conhecer o cardápio e os preços.
- Famílias interessadas em eventos e serviços oferecidos pelo restaurante.
- Clientes que desejam avaliar os produtos e o atendimento.

A interface deverá ser simples e acessível, facilitando a utilização por pessoas com diferentes níveis de familiaridade com a tecnologia.

## **4. Requisitos funcionais (RF)**

Os requisitos funcionais descrevem as ações e funcionalidades que o sistema deverá oferecer aos usuários.

| Identificação | Descrição                                                                                                                                                       |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF01          | O sistema deverá apresentar uma página inicial com informações sobre o restaurante, imagens e destaques.                                                        |
| RF02          | O sistema deverá disponibilizar uma página de apresentação do restaurante, contendo sua história e informações gerais.                                          |
| RF03          | O sistema deverá apresentar o cardápio com as opções de almoço e jantinhas com carne assada.                                                                    |
| RF04          | O sistema deverá permitir a visualização de informações dos produtos, incluindo nome, descrição, imagem e preço, quando disponíveis.                            |
| RF05          | O sistema deverá apresentar informações sobre o serviço de entrega, incluindo áreas atendidas, horários e formas de contato, conforme definição do restaurante. |
| RF06          | O sistema deverá oferecer uma opção para que os clientes entrem em contato e solicitem pedidos.                                                                 |
| RF07          | O sistema deverá disponibilizar uma seção para divulgação de eventos realizados ou promovidos pelo restaurante.                                                 |
| RF08          | O sistema deverá apresentar informações detalhadas dos eventos, como descrição, data, horário e imagens, quando aplicáveis.                                     |
| RF09          | O sistema deverá permitir que os clientes enviem avaliações sobre os produtos e serviços do restaurante.                                                        |
| RF10          | O sistema deverá disponibilizar uma seção para exibição das avaliações publicadas.                                                                              |
| RF11          | O sistema deverá apresentar informações de contato, localização e redes sociais do estabelecimento.                                                             |
| RF12          | O sistema deverá permitir que administradores cadastrem, editem e removam produtos do cardápio.                                                                 |
| RF13          | O sistema deverá permitir que administradores atualizem preços, descrições e imagens dos produtos.                                                              |
| RF14          | O sistema deverá permitir que administradores cadastrem, editem e removam informações de eventos.                                                               |
| RF15          | O sistema deverá permitir que administradores gerenciem as avaliações recebidas, incluindo sua aprovação antes da publicação.                                   |

## **5. Requisitos não funcionais (RNF)**

Os requisitos não funcionais estabelecem características de qualidade, desempenho, segurança e funcionamento do sistema.

| Identificação | Descrição                                                                                                                         |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| RNF01         | O site deverá possuir design responsivo, adaptando-se a computadores, tablets e smartphones.                                      |
| RNF02         | A interface deverá apresentar navegação simples, organizada e intuitiva.                                                          |
| RNF03         | O sistema deverá apresentar bom desempenho, evitando carregamentos desnecessariamente demorados.                                  |
| RNF04         | As imagens deverão ser otimizadas para reduzir o tempo de carregamento das páginas.                                               |
| RNF05         | O site deverá funcionar nos principais navegadores, como Google Chrome, Microsoft Edge, Firefox e Safari.                         |
| RNF06         | O sistema deverá utilizar conexão segura por HTTPS.                                                                               |
| RNF07         | O acesso à área administrativa deverá ser protegido por autenticação.                                                             |
| RNF08         | O sistema deverá proteger os dados pessoais dos usuários, respeitando a Lei Geral de Proteção de Dados (LGPD).                    |
| RNF09         | A identidade visual do restaurante deverá ser aplicada de maneira consistente em todas as páginas.                                |
| RNF10         | O sistema deverá possuir estrutura organizada, facilitando futuras atualizações e manutenções.                                    |
| RNF11         | As páginas deverão seguir boas práticas de acessibilidade, incluindo textos legíveis, contraste adequado e navegação por teclado. |
| RNF12         | O site deverá utilizar uma estrutura adequada para mecanismos de busca, facilitando sua localização na internet.                  |

## **6. Regras de negócio (RN)**

As regras de negócio estabelecem condições que deverão ser respeitadas durante a utilização e administração do sistema.

**RN01 — Atualização do cardápio:** somente usuários autorizados poderão cadastrar, modificar ou remover produtos.

**RN02 — Preços:** os valores apresentados no site deverão corresponder aos preços informados e atualizados pelo restaurante.

**RN03 — Disponibilidade:** produtos indisponíveis deverão ser identificados ou temporariamente retirados da exibição como disponíveis.

**RN04 — Entregas:** os pedidos deverão respeitar as regiões atendidas, os horários e as condições estabelecidas pelo restaurante.

**RN05 — Avaliações:** os clientes poderão enviar avaliações, mas sua publicação poderá depender da aprovação de um administrador.

**RN06 — Eventos:** informações de eventos deverão apresentar datas e horários corretos, sendo atualizadas ou removidas após sua realização.

**RN07 — Administração:** somente usuários autenticados e autorizados poderão acessar as funcionalidades administrativas.

**RN08 — Informações oficiais:** endereço, telefone, horários e demais informações institucionais deverão ser mantidos atualizados.

## **7. Funcionalidades prioritárias**

As funcionalidades prioritárias correspondem aos recursos essenciais para colocar o site em funcionamento e atender aos principais objetivos do restaurante.

Prioridade alta

| Funcionalidade         | Justificativa                                                |
| ---------------------- | ------------------------------------------------------------ |
| Página inicial         | Apresentar o restaurante e seus principais serviços.         |
| Cardápio digital       | Permitir que os clientes conheçam as refeições disponíveis.  |
| Informações de entrega | Facilitar o acesso às informações sobre pedidos.             |
| Contato e pedidos      | Aproximar clientes e restaurante.                            |
| Divulgação de eventos  | Informar os clientes sobre as atividades do estabelecimento. |
| Layout responsivo      | Garantir acesso adequado pelo celular e computador.          |
| Área administrativa    | Permitir a atualização das informações do site.              |

**Segunda prioridade:**

- Sistema de avaliações dos clientes.
- Galeria de imagens dos produtos e do restaurante.
- Integração com redes sociais.
- Exibição de comentários e experiências dos consumidores.

## **8. Funcionalidades que podem ser implementadas futuramente**

Após a implementação das funcionalidades principais, o sistema poderá receber novos recursos para ampliar sua capacidade e melhorar a experiência dos usuários.

| Identificação | Funcionalidade futura      | Descrição                                                                       |
| ------------- | -------------------------- | ------------------------------------------------------------------------------- |
| RF16          | Sistema de pedidos online  | Permitir que os clientes montem seus pedidos diretamente no site.               |
| RF17          | Carrinho de compras        | Possibilitar a seleção de diferentes produtos antes de finalizar o pedido.      |
| RF18          | Pagamento online           | Integrar métodos de pagamento digitais.                                         |
| RF19          | Acompanhamento de pedidos  | Permitir que o cliente acompanhe o andamento da entrega.                        |
| RF20          | Cadastro de clientes       | Criar contas para armazenar informações e facilitar pedidos futuros.            |
| RF21          | Programa de fidelidade     | Oferecer benefícios para clientes frequentes.                                   |
| RF22          | Notificações               | Enviar avisos sobre promoções, eventos e novidades.                             |
| RF23          | Relatórios administrativos | Apresentar dados sobre pedidos, avaliações e produtos mais procurados.          |
| RF24          | Reservas online            | Permitir que clientes solicitem reservas para eventos ou refeições presenciais. |
| RF25          | Promoções e cupons         | Disponibilizar ofertas especiais e códigos promocionais.                        |

## **Considerações finais**

O levantamento de requisitos estabelece a estrutura inicial do site institucional do restaurante Sonhos de Churrasco.

A proposta prioriza a apresentação do cardápio, a divulgação de eventos, as informações de entrega e a comunicação com os clientes. Também prevê uma estrutura administrativa que permita manter o conteúdo atualizado sem exigir alterações constantes no desenvolvimento do site.

A implementação poderá ocorrer em etapas, começando pelas funcionalidades essenciais e posteriormente incorporando recursos mais avançados, como pedidos online, pagamentos digitais e acompanhamento de entregas.

**Observação para a próxima etapa:** ainda será necessário definir se os pedidos serão realizados inicialmente pelo WhatsApp ou por um sistema próprio, além das formas de pagamento, regiões de entrega e critérios de avaliação. Essas decisões ajudarão a transformar os requisitos em especificações definitivas para o desenvolvimento.