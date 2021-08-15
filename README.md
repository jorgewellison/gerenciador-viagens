Este é um repositório para aprender um pouco mais sobre APIs REST.

Nele existem vários problemas e más práticas para serem utilizadas como exemplo do que não fazer.

No repositório foram criados testes automatizados utilizando JUnit e Rest Assured.

Comandos úteis:

mvn spring-boot:run

mb --configfile ../tempoAPI.ejs

mvn surefire:test

allure serve ..\GerenciadorViagens\gerenciador-viagens\target\surefire-reports/
