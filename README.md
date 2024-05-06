# App

GymPass style app.

## RFs (Requisitos funcionais)

- [ ] Deve ser possivel se cadastrar;
- [ ] Deve ser possivel se autenticar;
- [ ] Deve ser possivel obter o perfil de um usuário logado;
- [ ] Deve ser possivel obter o número de check-ins realizados pelo usuário logado
- [ ] Deve ser possivel o usuario obter seu historico de check-in 
- [ ] Deve ser possivel o usuario buscar academias próximas
- [ ] Deve ser possivel o usuario buscasr academias pelo nome;
- [ ] Deve ser possivel o usuario realizar check-in em uma academia
- [ ] Deve ser possivel validar o check-in de um usuario;
- [ ] Deve ser possivel cadastrar uma academia


## RNs (Regras de negócio)

- [ ]O usuario não deve poder se cadastrar com um e-mail duplicado
- [ ] O usuario não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuario não pode fazer check-in se não tiver perto (100m) da academia
- [ ] O check-in só pode ser validado ate 20 minutos após criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] A academia só pode cadastrada por administradores


## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário precisa estar criptogradafa
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página.
- [ ] O usuário deve ser identificado por um JWT(Json Web Token)
