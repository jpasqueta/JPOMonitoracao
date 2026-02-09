Memorial Descritivo do Projeto: JPONuclear

Desenvolvedora: Jéssica Pasqueta de Oliveira Data: 2022 Categoria: Software de Gestão de Radioproteção em Medicina Nuclear

Introdução
O JPONuclear é uma aplicação web progressiva (PWA) desenvolvida para otimizar o registro e a rastreabilidade das monitorações diárias de radiação. O foco do sistema é garantir que as normas de radioproteção sejam cumpridas de forma ágil e digital, substituindo planilhas de papel suscetíveis a erros e perdas.

Funcionalidades Principais
Monitoração de Áreas: Registro de taxas de exposição (
μ
S
v
/
h
 ou 
m
R
/
h
) em áreas críticas como Sala de Manipulação, Sala de Rejeitos e Banheiros de Pacientes.

Monitoração de IOE (Extremidades): Controle específico para Indivíduos Ocupacionalmente Expostos, focado em extremidades (mãos e pés).

Histórico em Tempo Real: Banco de dados em nuvem que permite a visualização imediata de registros anteriores.

Exportação de Dados: Geração de arquivos CSV para auditorias e relatórios mensais.

Tecnologias Utilizadas
Frontend: React.js com Tailwind CSS para interface responsiva.

Backend/Banco de Dados: Firebase Firestore (NoSQL) para armazenamento em tempo real.

Autenticação: Firebase Auth para segurança de acesso.

Ícones: Lucide React.

Arquitetura do Código
O código foi estruturado seguindo os princípios de Componentização e Hooks do React, garantindo uma manutenção simplificada e alta performance em dispositivos móveis. A comunicação com o banco de dados é feita de forma assíncrona com tratamento de erros e retentativa automática.
