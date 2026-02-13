Sistema de Portaria - TechZone

Sobre o Projeto

Este projeto simula um sistema de controle de acesso (portaria) desenvolvido com HTML e JavaScript.

O sistema verifica:

✅ Se o usuário está na lista de autorizados

⏰ Se o acesso está dentro do horário permitido

❌ Caso contrário, exibe mensagem de acesso negado

A resposta é exibida através de alert().

Funcionalidades

Entrada de nome
Entrada de horário
Verificação de usuário autorizado
Validação de horário (antes das 22h)
Mensagens de acesso permitido ou negado

🧠 Lógica Aplicada

O sistema segue as seguintes regras:

Verifica se o nome digitado está dentro do array autorizados

Se estiver:

Permite acesso se o horário for menor que 22

Nega acesso se for 22h ou mais

Se o nome não estiver na lista:

Acesso negado (usuário não cadastrado)

Tecnologias Utilizadas

HTML

JavaScript
