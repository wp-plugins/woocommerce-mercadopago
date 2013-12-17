=== WooCommerce MercadoPago ===
Contributors: claudiosanches
Donate link: http://claudiosmweb.com/doacoes/
Tags: woocommerce, mercadopago, payment
Requires at least: 3.5
Tested up to: 3.8
Stable tag: 1.8.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds MercadoPago gateway to the WooCommerce plugin

== Description ==

### Add MercadoPago gateway to WooCommerce ###

This plugin adds MercadoPago gateway to WooCommerce.

Please notice that WooCommerce must be installed and active.

= Contribute =

You can contribute to the source code in our [GitHub](https://github.com/claudiosmweb/woocommerce-mercadopago) page.

### Descrição em Português: ###

Adicione o MercadoPago como método de pagamento em sua loja WooCommerce.

[MercadoPago](https://www.mercadopago.com/) é um método de pagamento desenvolvido pelo Mercado Livre.

O plugin WooCommerce MercadoPago foi desenvolvido sem nenhum incentivo do MercadoPago ou Mercado Livre. Nenhum dos desenvolvedores deste plugin possuem vínculos com estas duas empresas.

Este plugin foi feito baseado na [documentação oficial do MercadoPago](http://developers.mercadopago.com/).

= Compatibilidade =

Compatível com as versões 2.0.x e 2.1.x do WooCommerce.

= Instalação: =

Confira o nosso guia de instalação e configuração do WooCommerce MercadoPago na aba [Installation](http://wordpress.org/extend/plugins/woocommerce-mercadopago/installation/).

= Dúvidas? =

Você pode esclarecer suas dúvidas usando:

* A nossa sessão de [FAQ](http://wordpress.org/extend/plugins/woocommerce-mercadopago/faq/).
* Criando um tópico no [fórum de ajuda do WordPress](http://wordpress.org/support/plugin/woocommerce-mercadopago) (apenas em inglês).
* Ou entre em contato com os desenvolvedores do plugin em nossa [página](http://claudiosmweb.com/plugins/mercadopago-para-woocommerce/).

= Coloborar =

Você pode contribuir com código-fonte em nossa página no [GitHub](https://github.com/claudiosmweb/woocommerce-mercadopago).

### Translators ###

* es_ES by [Marcelo Pedra](http://profiles.wordpress.org/kent-brockman)
* es_AR by [Gustavo Coronel](http://profiles.wordpress.org/gcoronel/)

== Installation ==

* Upload plugin files to your plugins folder, or install using WordPress built-in Add New Plugin installer;
* Activate the plugin;
* Navigate to WooCommerce -> Settings -> Payment Gateways, choose MercadoPago and fill in your MercadoPago Client_id and Client_secret.

### Instalação e configuração em Português: ###

= Instalação do plugin: =

* Envie os arquivos do plugin para a pasta wp-content/plugins ou usando o instalador de plugins do WordPress.
* Ative o plugin.

= Requerimentos: =

É necessário possuir uma conta no [MercadoPago](https://www.mercadopago.com/) e instalar a última versão do [WooCommerce](http://wordpress.org/extend/plugins/woocommerce/).

= Configurações no MercadoPago: =

No MercadoPago você precisa validar sua conta e conseguir o seu Client_id e Client_secret.

Você pode acessar as suas informações de Client_id e Client_secret em:

* [MercadoPago da Argentina](https://www.mercadopago.com/mla/herramientas/aplicaciones)
* [MercadoPago do Brasil](https://www.mercadopago.com/mlb/ferramentas/aplicacoes)
* [MercadoPago do México](https://www.mercadopago.com/mlm/herramientas/aplicaciones)
* [MercadoPago da Venezuela](https://www.mercadopago.com/mlv/herramientas/aplicaciones)

É necessário também configurar a página de retorno, para isso é necessário acessar:

* [MercadoPago da Argentina](https://www.mercadopago.com/mla/herramientas/notificaciones)
* [MercadoPago do Brasil](https://www.mercadopago.com/mlb/ferramentas/notificacoes)
* [MercadoPago do México](https://www.mercadopago.com/mlm/herramientas/notificaciones)
* [MercadoPago da Venezuela](https://www.mercadopago.com/mlv/herramientas/notificaciones)

Deve ser configurada a sua página de retorno como por exemplo:

	http://seusite.com/?wc-api=WC_MercadoPago_Gateway

= Configurações do Plugin: =

Com o plugin instalado acesse o admin do WordPress e entre em "WooCommerce" > "Configurações" > "Portais de pagamento"  > "MercadoPago".

Habilite o MercadoPago, adicione o seu e-mail, Client_id e Client_secret.

Pronto, sua loja já pode receber pagamentos pelo MercadoPago.

= Configurações no WooCommerce =

No WooCommerce 2.0 ou superior existe uma opção para cancelar a compra e liberar o estoque depois de alguns minutos.

Esta opção não funciona muito bem com o MercadoPago, pois pagamentos por boleto bancário pode demorar até 48 horas para serem validados.

Para corrigir isso é necessário ir em "WooCommerce" > "Configurações" > "Inventário" e limpar (deixe em branco) o valor da opção **Manter Estoque (minutos)**.

== Frequently Asked Questions ==

= What is the plugin license? =

* This plugin is released under a GPL license.

= What is needed to use this plugin? =

* WooCommerce version 2.0 or latter installed and active.
* Only one account on [MercadoPago](https://www.mercadopago.com/ "MercadoPago").
* Get the information of Client_id and Client_secret from MercadoPago.
* Set page of automatic return data.

= Currencies accepted =

The plugin works with ARS and BRL.

Add ARS with [WooCommerce ARS Currency](http://wordpress.org/extend/plugins/woocommerce-ars-currency/) plugin.

### FAQ em Português: ###

= Qual é a licença do plugin? =

Este plugin esta licenciado como GPL.

= O que eu preciso para utilizar este plugin? =

* Ter instalado o plugin WooCommerce 2.0 ou superior.
* Possuir uma conta no MercadoPago.
* Pegar as informações de Client_id e Client_secret.
* Configurar a página de retorno automático de dados.

= Moedas aceitas =

Este plugin funciona com ARS (Peso Argentino) e BRL (Real Brasileiro).

Adicione a moeda ARS usando o plugin [WooCommerce ARS Currency](http://wordpress.org/extend/plugins/woocommerce-ars-currency/).

= Como funciona o MercadoPago? =

* Saiba mais em "[O que é o MercadoPago e como funciona?](http://guia.mercadolivre.com.br/mercadopago-como-funciona-6983-VGP)".

= Quais são os meios de pagamento que o plugin aceita? =

São aceitos todos os meios de pagamentos que o MercadoPago disponibiliza.
Entretanto você precisa ativa-los na sua conta no MercadoPago.

Consulte os meios de pagamento em "[Meios de pagamento e parcelamento](https://www.mercadopago.com/mlb/ml.faqs.framework.main.FaqsController?pageId=FAQ&faqId=2991&categId=How&type=FAQ)".

= Quais são as moedas que o plugin aceita? =

No momento é aceito **ARL** (Argentine peso ley) e **BRL** (Real Brasileiro).

= Quais são as taxas de transações que o MercadoPago cobra? =

Consulte a página "[Taxas do Mercado Pago](http://guia.mercadolivre.com.br/taxas-mercado-pago-12593-VGP)".

= Como que plugin faz integração com MercadoPago? =

Fazemos a integração baseada na documentação oficial do MercadoPago que pode ser encontrada em "[MercadoPago Developers](http://developers.mercadopago.com/)"

= A compra é cancelada após alguns minutos, mesmo com o pedido sendo pago, como resolvo isso? =

Para resolver este problema vá até "WooCommerce" > "Configurações" > "Inventário" e limpe (deixe em branco) o valor da opção **Manter Estoque (minutos)**.

= Mais dúvidas relacionadas ao funcionamento do plugin? =

Entre em contato [clicando aqui](http://claudiosmweb.com/plugins/mercadopago-para-woocommerce/).

== Screenshots ==

1. Settings page.
2. Checkout page.

== Changelog ==

= 1.8.1 - 17/12/2013 =

* Corrigido os parametros da conexão (cURL) que podiam gerar erro (`SSL connection timeout`) em alguns servidores.

= 1.8.0 - 04/12/2013 =

* Corrigido padrões de código.
* Removida compatibilidade com versões 1.6.x ou inferiores do WooCommerce.
* Adicionada compatibilidade com WooCommerce 2.1 ou superior.

= 1.7.0 - 03/11/2013 =

* Corrigido o textdomain para suportar o padrão do WordPress 3.7.
* Corrigida verificação que testa se o plugin esta pronto para funcionar ou não (créditos para daigo75).
* Adicionada compatibilidade com o plugin Currency Switcher for WooCommerce (créditos para daigo75).

= 1.6.0 - 26/07/2013 =

* Melhoria nas mensagens de status do pedido.
* Melhoria no código do plugin.

= 1.5.0 - 26/07/2013 =

* Adicionada tradução para es_ES por [Marcelo Pedra](http://profiles.wordpress.org/kent-brockman)
* Adicionado o filtro `woocommerce_mercadopago_icon` para a modificação do ícone durante o checkout.
* Adicionado parâmetro $order no filtro `woocommerce_mercadopago_args`.
* Melhorias no código.

= 1.4.0 - 17/07/2013 =

* Melhoria no código.
* Adicionada opção para pagamento direto ou por janela modal.
* Adicionada opção de sandbox.
* Adicionada compatibilidade com o WooCommerce 2.1 ou superior.
* Atualização das traduções em pt_BR e es_AR.

= 1.3.0 - 07/04/2013 =

* Correção do retorno automático de dados na versão 2.0.0 ou superior do WooCommerce.
* Atualização das traduções em pt_BR e es_AR.

= 1.2.3 - 11/03/2013 =

* Adicionada compatibilidade com as moedas: `MXN`, `USD` e `VEF`.

= 1.2.2 - 06/03/2013 =

* Corrigida a compatibilidade com WooCommerce 2.0.0 ou mais recente.

= 1.2.1 - 08/02/2013 =

* Corrigido o hook responsavel por salvar as opções para a versão 2.0 RC do WooCommerce.

= 1.2.0 - 01/12/2012 =

* Adicionada tradução para es_AR por [Gustavo Coronel](http://profiles.wordpress.org/gcoronel/)

= 1.1.1 - 30/11/2012 =

* Correção dos logs de erro.

= 1.1.0 - 30/11/2012 =

* Adicionada opção para logs de erro.

= 1.0.0 =

* Versão Inicial.

== Upgrade Notice ==

= 1.8.1 =

* Corrigido os parametros da conexão (cURL) que podiam gerar erro (`SSL connection timeout`) em alguns servidores.

== License ==

WooCommerce MercadoPago is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published
by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

WooCommerce MercadoPago is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with WooCommerce MercadoPago. If not, see <http://www.gnu.org/licenses/>.
