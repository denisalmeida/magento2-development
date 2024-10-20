# Desenvolvimento Magento 2

## Visão geral

Este repositório tem o objetivo de mostrar minhas habilidades no desenvolvimento e customização de temas, módulos e componentes.

## Instalação

Para configurar em ambiente local, siga estas etapas:

1. **Clone o repositório:**
   ```bash
   git clone git@github.com:denisalmeida/magento2-development.git
   cd magento2-development.git
   ```

2. **Instale as dependências:**
   ```bash
   composer install
   ```

3. **Configuração:**
- Configure sua instância do Magento de acordo com as diretrizes de instalação do Magento.
- Aplique as configurações necessárias do banco de dados e execute os comandos de configuração.

4. **Deploy Static Content:**
   ```bash
   bin/magento setup:static-content:deploy
   ```

5. **Habilitar módulos customizados:**
   ```bash
   bin/magento module:enable Vendor_Module
   ```

6. **Atualizar esquema de banco de dados:**
   ```bash
   bin/magento setup:upgrade
   ```

7. **Limpeza de cache:**
   ```bash
   bin/magento cache:flush
   ```

8. **Abra sua loja Magento em um navegador da web e verifique a configuração.**

## Estrutura de pastas

O projeto segue uma estrutura de pastas padrão do Magento 2:

- `app/code`: Módulos e extensões.
- `app/design`: Arquivos de temas.

# Authors

*   [Denis Almeida](https://denisalmeida.com)

## Licença

Este projeto está licenciado sob a [Open Software License (OSL) v. 3.0](LICENSE).

Sinta-se à vontade para entrar em contato conosco caso tenha alguma dúvida ou feedback!
