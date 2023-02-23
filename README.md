# RealtimeConfig
  Realtime basico, apenas realtime configurado, sem scripts, sem sass, projeto de base suporta php >= 7 && < 8, versão laravel 8

## :computer: Tecnologias Utilizadas
~~~ BackEnd
* PHP 7.4.9
* LARAVEL 8
* NODE 16.14.2
~~~

~~~Banco
* MySql 5.7
~~~
## Inicialização
1. Certifique-se de ter instalado na sua máquina o php >= 7 <= 8 
2. Certifique-se de estar usando a versão do node indicada no projeto
3. Tem um executavel na raiz do projeto 'node-v16.14.2-x64-LTS.msi'
4. Não faça o clone, baixe o arquivo .zip -> **NÃO MODIFICAR PROJETO BASE**
5. Crie um projeto git apenas com readme.md
6. Clone o projeto e extraia o arquivo no projeto clonado
7. Duplique o arquivo `.env.example` e retire o `.example`
8. Configure as variaveis de conexao com o banco de dados que você deseja usar
9. Execute `composer install`
10. Execute `php artisan key:generate`
11. Execute `php artisan migrate`
12. Execute `npm install` && `npm run dev`
13. Execute `php artisan serve` ou `php artisan serve --host='0.0.0.0'`
13. Abra um nova guia no seu cmd
14. Execute `php artisan websockets:serve` 

## Implementações Futuras
 :construction:  Não possui é apenas um projeto base pré-configurado para realtime

