# Banco de Dados

# Eventos e Interações

Status dos eventos → campo para saber se está ativo, cancelado, concluido.

alter table eventos add status enum('ativo','cancelado','concluido') default 'ativo';


Categorias / tipos de eventos → visitas, oficinas, atividades culturais, etc.

Feedback/Avaliações → voluntários e asilos podem avaliar os eventos:

# Tabela Mensagens / Fórum → comunicação entre voluntários e asilos.

O que falta para profissionalizar o banco é segurança (tokens, auditoria), normalização (endereços, tipos de usuários), riqueza de relacionamento (avaliações, mensagens, status) e performance (índices).
