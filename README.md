MiAuspedagem

Sistema web para reserva e gerenciamento de hospedagens para cães e gatos. O projeto conta com uma interface para tutores realizarem solicitações de reserva e um painel exclusivo para o proprietário gerenciar os agendamentos.

Funcionalidades

Área do Cliente

Calendário Interativo: 
Permite ao tutor visualizar os dias disponíveis e selecionar múltiplas datas desejadas.
Busca Automática de Endereço (ViaCEP): 
Ao inserir o CEP, os dados do logradouro, bairro, cidade e estado são preenchidos automaticamente.
Formulário Completo: 
Coleta detalhada dos dados do tutor e especificações do pet (raça, peso, necessidades especiais).
Modal Informativo: 
Instruções claras de funcionamento para o usuário antes do envio da solicitação.

Área do Proprietário 

Painel Administrativo: 
Acesso protegido por senha para gestão dos agendamentos.
Ação Rápida via WhatsApp: 
Integração direta que gera uma mensagem personalizada no WhatsApp do tutor para confirmar os detalhes da reserva.
Status e Gestão de Agendamentos: 
Marque solicitações como pendentes/confirmadas ou exclua cadastros finalizados.
Persistência Local: 
Salva o estado e os dados das solicitações diretamente no navegador via localStorage.

Tecnologias Utilizadas

HTML5: 
Estruturação semântica da aplicação.
CSS3: 
Estilização responsiva personalizada com tipografia integrada.
JavaScript: 
Manipulação de DOM, gerenciamento do calendário, integração com APIs e controle de fluxo do sistema.
API ViaCEP: 
Consulta automatizada de CEP para autopreenchimento de endereço.

Estrutura de Arquivos

index.html    Estrutura principal da página (cliente e admin).
style.css     Estilização completa do layout, modal e calendário.
script.js     Lógica do sistema, calendário e gerenciamento de reservas.
doggy.jpeg    Imagem principal de interação da tela inicial.




