# Módulo de pagamento PayMee para Magento 2.x

## Descrição

O Módulo de integração PayMee para Magento 2.x oferece os principais bancos do Brasil para o seu ecommerce.

- 001 - Banco do Brasil S.A
- 033 - Santander Brasil S.A
- 077 - Banco Inter S.A
- 104 - Caixa Econômica Federal
- 212 - Banco Original S.A
- 237 - Banco Bradesco S.A
- 341 - Banco Itaú-Unibanco S.A

## Requisitos
- [PHP 5.4+](https://www.php.net)
- [Magento 2.x](https://magento.com/tech-resources/download)
- [cURL](https://www.php.net/manual/en/book.curl.php)

## Instalação via Git
> **Importante: faça o backup da sua loja antes da instalação.**

    $ mkdir -p ~/magento2xModules/PayMee/Tagweb/Paymee
    $ git clone https://github.com/paymeebrasil/magento-2.x.git ~/magento2xModules/PayMee/Tagweb/Paymee
    $ mv ~/magento2xModules/PayMee/Tagweb /foo/bar/magento2/app/code
    $ cd /foo/bar/magento2
    $ #Execute os comandos
    $ php bin/magento setup:upgrade
    $ php bin/magento setup:static-content:deploy
    $ chmod -R 777 var/cache/*

Agora, acesse seu painel administrativo e configure suas credencias seguindo o caminho: STORES > CONFIGURATION > SALES > PAYMENT METHODS > PayMee


## Demo
[http://magento2.paymee.com.br](http://magento2.paymee.com.br)

## API Reference
https://documenter.getpostman.com/view/3199663/RWM6zDGc?version=latest
