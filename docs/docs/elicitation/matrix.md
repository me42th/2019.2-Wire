<!DOCTYPE html>
<html>
<head>
<style>
    div.polaroid {
    width: 1100px;
    height: 400px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    text-align: center;
    }
    div.container {
    padding: 10px;
    }
</style>
</head>
<body>

<!DOCTYPE html>
<html>
<head>
<style src='docs/docs/assets/css/table.css'>
table {
  width: 100%;
}
</style>
<link rel="stylesheet" href="docs/assets/css/table.css">
</head>
</html> 

# Matriz de Relação

## Requisitos Funcionais

| ID | Descrição | 5W2H |  Introspecção  | Questionário |  Storytelling | Entrevista | Brainstorming|
| ----- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| RF01 | Enviar mensagem                                | X | X | X | X | X |
| RF02 | Definir quanto tempo a mensagem fica visível   |  | X |  |  |   |    |
| RF03 | Apagar mensagem                                |  |  | X |  |   |    |
| RF04 | Responder mensagem                             |  |  | X |  |   | X  |
| RF05 | Encaminhar mensagem                            |  |  |  |  |   |  X  |
| RF06 | Editar mensagem                                |  |  | X |  |   |    |
| RF07 | Enviar áudio                                   | X | X | X |  |   |   |
| RF08 | Apagar áudio                                   |  |  | x |  |   | X |
| RF09 | Selecionar mensagens                           |  |  |  |  |   | X |
| RF10 | Dar play e pause no áudio                      |  |  |  |  |   | X |
| RF11 | Escolher ponto de tempo do áudio               |  |  |  |  |   | X |
| RF12 | Enviar imagem e vídeo                          | X | X | X | X |  |  |
| RF13 | Editar imagem                                  |  |  |  |  |   | X |
| RF14 | Enviar arquivo                                 | X | X | X | X | X | |
| RF15 | Download de arquivos                           |  |  |  |  |   | X  |
| RF16 | Abrir arquivo dentro do aplicativo             |  |  |  |  |   | X |
| RF17 | Chamada de vídeo                               | X | X | X | X | X |   |
| RF18 | Adicionar pessoas à chamada de vídeo           |  |  |  |  |   |  X  |
| RF19 | Entrar em chamada de vídeo já existente        |  |  |  |  |   |  X  |
| RF20 | Ligar e desligar câmera                        |  |  |  |  |   |  X  |
| RF21 | Fazer ligação de áudio                         | X | X | X | X |  X  | |
| RF22 | Ligar e desligar microfone                     |  |  |  |  |   | X |
| RF23 | Sair da chamada                                |  |  |  |  |   |  X  |
| RF24 | Criar grupo                                    | X | X | X | X |  X |    |
| RF25 | Adicionar pessoas no grupo                     | X | X | X | X |   | |
| RF26 | Remover pessoas do grupo                       |  | X | X |  |   |   |
| RF27 | Definir permissões de cada membro do grupo     |  | X |  |  |   | X |
| RF28 | Responder mensagem recebida no grupo no privado|  |  |  |  |   |  X  |
| RF29 | Fixar mensagens                                |  | X |  |  |   |  X  |
| RF30 | Mensagem de alerta                             |  | X |  |  |   | |
| RF31 | Silenciar grupo                                |  |  |  |  |   |  X  |
| RF32 | Criar canal de transmissão de mensagens        |  |  |  |  |   |  X  |
| RF33 | Criar Guest Room                               |  |  |  |  |   |  X  |
| RF34 | Adicionar contatos                             |  | X | X | X |   | |
| RF35 | Editar dados do contato                        |  |  |  |  |   |  X  |
| RF36 | Bloquear usuário                               |  |  |  |  |   |  X |
| RF37 | Criar time                                     | X |  |  |  |   | X |
| RF38 | Adicionar usuários ao seu time                 | X |  |  |  |   | X |
| RF39 | Cadastrar usuário pelo número                  |  | X |  | X |   |  |
| RF40 | Cadastrar usuário pelo e-mail                  |  | X |  | X |   |  |
| RF41 | Definir nome do usuário                        |  | X | X |  |   |    |
| RF42 | Editar perfil                                  |  | X |  |  |   |  |
| RF43 | Alterar opção de fazer download automático     |  |  |  |  |   | X |
| RF44 | Mudar senha                                    |  |  |  |  |   |  X  |
| RF45 | Fazer Backup                                   |  | X |  |  |  X  |   |
| RF46 | Deletar conta                                  |  | X | X |  |   |  |

## Requisitos Não Funcionais

| ID | Descrição |  5W2H |  Introspecção  | Questionário |  Storytelling | Entrevista | Brainstorming |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RNF01 | Criptografia de ponta-a-ponta.                                    | X |  | X | X | X |  |
| RNF02 | Cadastro, configuração e utilização de até 8 contas simultâneas   |  | X | X | X |  | X |
| RNF03 | Disponível em multiplataformas independentes                      | X |  | X | X | X |  |
| RNF04 | Alterar foto de fundo                                             |  | X |  |  |  | X |
| RNF05 | Alterar fonte do texto                                            |  | X |  |  |  | X |
| RNF06 | Modo noturno                                                      |  | X |  |  |  | X |
| RNF07 | Proteção de  dados do usuário                                     | X | X | X | X | X |  |
| RNF08 | Disponibilidade self-hosted e cloud manager                       |  |  |  |  | X | X |
| RNF09 | Multilinguagem                                                    |  |  |  |  |  | X |
| RNF10 | Possibilidade de acoplar serviços externos                        |  |  |  |  |  | X |
| RNF11 | Compatibilidade com outros formatos de mensagem (Markdown, GIFS, etc) |  |  |  |  |  | X |
| RNF12 | Check de visualização de mensagem                                 |  |  | X |  |  | X |
| RNF13 | Visto por último                                                  |  |  | X |  |  | X |
| RNF14 | Aviso de mensagem não enviada                                     |  |  |  |  |  | X |
