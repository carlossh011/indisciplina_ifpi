# 1.Escopo do Projeto
O sistema tem como objetivo acelerar e organizar o fluxo disciplinar, permitindo que advertências sejam registradas rapidamente pelos professores e comunicadas aos pais de forma automática, reduzindo atrasos, papelada e problemas de comunicação.
# 2. Problema
O processo de registro e comunicação das advertências é lento, manual e burocrático.
## 2.1 Instrução do Problema
| O problema é | O processo de registro e comunicação das advertências é lento, manual e pouco eficiente. |
|--------------|-------------------------------------------------------------------------------------------|
| O que afeta  | Afeta professores, coordenação, direção e principalmente os pais, que recebem as informações com atraso. |
| O impacto do problema é | Pais ficam desinformados, advertências chegam atrasadas, professores acumulam papelada e o controle disciplinar perde eficácia. |
| Uma solução seria | Desenvolver um sistema onde professores possam registrar advertências diretamente e os pais recebam notificações automáticas. |
## 2.2 Problemas a serem resolvidos
| Problema | Descrição |
|----------|-----------|
| Atraso no registro das advertências | O processo exige anotações manuais, registro posterior e validações demoradas. |
| Professores sem acesso ao sistema | Os docentes não conseguem registrar advertências diretamente no SUAP. |
| Falta de notificação aos pais | Pais ficam sabendo tarde demais ou dependem do aluno entregar o documento em casa. |
| Advertências antigas perdem o efeito | Como chegam com atraso, a ação disciplinar perde impacto. |
| Processo burocrático | Envolve papelada, deslocamento e etapas manuais que atrasam tudo. |
# 3. Descrição da Parte Interessada e do Usuário
Professores  
Responsáveis por aplicar advertências quando necessário. Sofrem com o processo manual e burocrático, e não possuem acesso direto para registrar advertências no sistema.

Coordenação 
Recebe as advertências dos professores, confere e encaminha para a direção. É um setor impactado pelo acúmulo e atraso de documentos.

Direção  
Responsável por validar e registrar oficialmente a advertência. Precisa de um processo mais ágil e organizado.

Pais e Responsáveis  
São os mais prejudicados pela demora na comunicação. Muitas vezes só ficam sabendo semanas depois do ocorrido ou dependem do aluno entregar o documento em casa.

Alunos  
Recebem a advertência, mas às vezes não entregam o documento aos pais. Um sistema mais claro e rápido ajuda na responsabilidade e acompanhamento da conduta.
## 3.1 Resumo das Partes Interessadas
| Parte Interessada                 | Descrição                                                                     | Função / Interesse no Sistema                                       |
| --------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Professores**                   | Responsáveis por registrar advertências e acompanhar a disciplina dos alunos. | Registrar advertências de forma rápida e acompanhar o status delas. |
| **Coordenação**                   | Setor que valida advertências e controla o fluxo disciplinar.                 | Validar, rejeitar ou encaminhar advertências ao setor pedagógico.   |
| **Direção**                       | Responsável pela homologação das advertências e decisões finais.              | Homologar advertências, gerar relatórios e administrar o sistema.   |
| **Setor Pedagógico (ETEP)**       | Realiza acompanhamento pedagógico de alunos reincidentes.                     | Registrar intervenções, observações e reuniões pedagógicas.         |
| **Pais e Responsáveis**           | Devem ser informados rapidamente sobre ocorrências disciplinares.             | Receber notificações e acompanhar o histórico disciplinar do aluno. |
| **Alunos**                        | Registrados no sistema e afetados pelas advertências.                         | Visualizar suas advertências e histórico disciplinar.               |
| **Time de Desenvolvimento / APS** | Responsáveis pelo desenvolvimento do sistema.                                 | Criar, documentar e manter o sistema, garantindo suas funções.      |

## 3.2 Resumo dos Usuarios
| Usuário                 | Descrição / Acesso                                                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Professor**           | Pode registrar e editar advertências antes da validação; anexar evidências; consultar histórico por aluno ou turma. |
| **Coordenação**         | Valida, rejeita ou encaminha advertências; gera relatórios; solicita reuniões com responsáveis.                     |
| **Direção**             | Homologa advertências; gerencia usuários e categorias; acessa relatórios completos.                                 |
| **Pais e Responsáveis** | Recebem notificações automáticas e podem consultar o histórico disciplinar do aluno.                                |
| **Alunos**              | Podem visualizar suas próprias advertências e intervenções pedagógicas.                                             |



# 4. Visão Geral do Produto
## 4.1 Perspectiva do Produto
O produto será um sistema digital integrado ao fluxo escolar, permitindo que professores registrem advertências diretamente e que pais sejam notificados automaticamente.
## 4.2 Resumo dos Recursos
- registro rápido de advertências pelos professores.
- Encaminhamento automático para coordenação e direção.
- Notificação instantânea aos pais.
- Histórico organizado por aluno.
- Redução de papelada e burocracia.
- Acesso controlado para cada nível (professor, coordenação, direção).
# 5. Recursos do Produto(Funcionalidades)
- Registrar advertências rapidamente.
-	Encaminhar automaticamente para coordenação/direção.
-	Enviar notificações automáticas aos pais.
-	Manter histórico disciplinar por aluno.
-	Permitir consulta por data, tipo e usuário.
-	Gerar relatórios mensais e por turma.
-	Controlar permissões de acesso.

# 6. Casos de Uso
– Registrar Advertência

– Validar Advertência

– Homologar Advertência

– Notificar Responsáveis

– Consultar Histórico

 – Gerar Relatórios
## 6.1 Diagrama de Casos de Uso


## 6.2 Fluxo de Casos de Usos
- Registrar Advertência

Ator Principal: Professor
Objetivo: Registrar uma advertência de forma rápida.

Fluxo Principal (Sucesso)

O professor acessa o sistema.

Seleciona a opção “Registrar Advertência”.

Escolhe o aluno.

Informa o tipo da advertência.

Descreve o ocorrido.

(Opcional) Anexa evidências.

Envia para validação da coordenação.

O sistema confirma o envio.

- Validar Advertência

Ator Principal: Coordenação
Objetivo: Conferir e validar registros feitos pelos professores.

Fluxo Principal

A coordenação acessa advertências pendentes.

Seleciona uma advertência.

Analisa as informações.

Clica em “Validar”.

Sistema atualiza o status para “Validada”.

- Homologar Advertência

Ator Principal: Direção
Objetivo: Tornar oficial uma advertência validada.

Fluxo Principal

Direção visualiza advertências validadas.

Seleciona uma advertência.

Analisa a descrição e histórico do aluno.

Clica em “Homologar”

- Notificar Responsáveis

Ator Principal: Sistema
Objetivo: Comunicar pais e responsáveis automaticamente.

Fluxo Principal

Quando uma advertência é homologada, o sistema identifica o responsável do aluno.

Sistema gera mensagem automática (WhatsApp, SMS ou e-mail).

Envia a notificação ao responsável.

Sistema registra que a notificação foi enviada.

Sistema registra a homologação e armazena no histórico final.
- Consultar Histórico

Atores: Professor, Coordenação, Direção, Pais, Aluno
Objetivo: Ver advertências passadas.

Fluxo Principal

Usuário acessa “Histórico”.

Pesquisa por aluno, turma ou data.

Sistema exibe:

tipo

data

descrição

status (validada, homologada, rejeitada)

Usuário analisa os registros
- Gerar Relatórios

Atores: Coordenação e Direção
Objetivo: Emitir relatórios para gestão disciplinar

Fluxo Principal

Usuário acessa Relatórios

Seleciona filtros (turma, período, tipo).

Sistema processa os dados.

Exibe relatório na tela.

(Opcional) Usuário exporta como PDf.
# 7. Restrições
## 7.1 Restrições de Design
- Interface deve ser simples e fácil para uso rápido em sala de aula.
- Deve funcionar bem em computadores e celulares
- Uso de linguagem clara para pais e professores
## 7.2 Restrições de Segurança
- Apenas usuários autorizados podem acessar advertencias
- Notificações devem ser enviadas de forma segura.
## 7.3 Restrições de Metodologia (Processos e Ferramentas)
- Deve integrar com ferramentas ja utilizadas pela escola, se possível.
- Registro deve ser auditável (mostrar quem fez, quando fez)
- Sistema deve estar disponível mesmo com internet limitada.
