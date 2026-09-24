# Campeonato Gamer

## Situação-problema

Nossa turma vai organizar partidas de jogos. Queremos registrar **jogo**, **time A**, **time B**, **placar** e **status**. Uma partida começa `agenda` com placar `0 X 0`. Depois podemos atualizar para `finalizada`.

Ao final, a API terá estas rotas:
| Método | Rota | O que faz |
| ---   | ---   |   --- |
| GET   | `/`   | Confirma que API está funcionando |
| GET   | `/partidas`   | Lista e filtrar partidas  |
| GET   | `/partidas:id`  | Buscar uma partida  | 
| POUST | `/partidas `|   Cadastrar uma partida   |
| PUT   | ` /partidas`   | Altera uma partida e o placar |
| DELETE | `partidas`  | Exclui uma partida

## Etapa 1 - Criar o projeto

No terminal, digite **uma linha por vez**;

```bash
    mkdir CampeonatoGamer
    cd CampeonatoGamer
    npm init -y
    npm install express cors
    code .
```"# CampeonatoGamer" 
"# CampeonatoGamer" 
"# CampeonatoGamer" 
