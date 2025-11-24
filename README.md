# 1.Escopo do Projeto
O sistema tem como objetivo acelerar e organizar o fluxo disciplinar, permitindo que advertências sejam registradas rapidamente pelos professores e comunicadas aos pais de forma automática, reduzindo atrasos, papelada e problemas de comunicação.
# 2. Problema
O atual processo de registro de advertencias é lento, manual e burocrático, resultando am atrasos que prejudicam a eficácia da disciplina e a comunicação com os pais ou responsáveis.
## 2.1 Instrução do Problema
| O problema é | O processo de registro e comunicação das advertências é lento, manual e pouco eficiente. |
|--------------|-------------------------------------------------------------------------------------------|
| O que afeta  | Afeta professores, coordenação, direção e principalmente os pais, que recebem as informações com atraso. |
| O impacto do problema é | Pais ficam desinformados, advertências chegam atrasadas, professores acumulam papelada e o controle disciplinar perde eficácia. |
| Uma solução seria | Desenvolver um sistema digital onde professores possam registrar advertências diretamente e os pais recebam notificações automáticas após a holomogação. |
## 2.2 Problemas a serem resolvidos
| Problema | Descrição |
|----------|-----------|
| Atraso no registro das advertências | O processo exige anotações manuais,deslocamento e validações demoradas. |
| Professores sem acesso ao sistema | Atualmente docentes não conseguem registrar advertências diretamente no SUAP. |
| Falta de notificação aos pais | Pais ficam sabendo tarde demais ou dependem do aluno entregar o documento em casa. |
| Advertências antigas perdem o efeito | Como chegam com atraso, a ação disciplinar perde impacto. |
| Processo burocrático | Excesso de papelada, deslocamento, etapas manuaise fluxos lentos . |
# 3. Descrição da Parte Interessada e do Usuário
Professores  
Registram advertências e acompanham o comportamento dos alunos. É o grupo mais impactado pela burocracia atual.

Coordenação 
Valida advertências, acompanha reincidências e controla o fluxo disciplinar.

Direção  
Homologa advertências e decide ações disciplinares. Necessita de agilidade e organização.

Pais e Responsáveis  
Precisam receber as advertências rapidamente para acompanhar a conduta do aluno.

Alunos  
Têm sua conduta registrada e precisam de clareza sobre suas advertências.

Time de Desenvolvimento
Responsável pela implementação e manutenção do sistema.

## 3.1 Resumo das Partes Interessadas
| Parte Interessada                 | Descrição                                                                     | Função / Interesse no Sistema                                       |
| --------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **Professores**                   | Aplicam e registram advertências. | Registrar e acompanhar status |
| **Coordenação**                   | Valida e gerencia fluxo disciplinar	                 | Validar, rejeitar ou encaminhar advertências ao setor pedagógico.   |
| **Direção**                       | Responsável pela homologação das advertências e decisões finais.              | Homologar advertências, gerar relatórios e administrar o sistema.   |
| **Pais e Responsáveis**           | Devem ser informados rapidamente sobre ocorrências disciplinares.             | Receber notificações e acompanhar o histórico disciplinar do aluno. |
| **Alunos**                        | Registrados no sistema e afetados pelas advertências.                         | Visualizar suas advertências e histórico disciplinar.               |
| **Time de Desenvolvimento** | Responsáveis pelo desenvolvimento do sistema.                                 | Criar, documentar e manter o sistema, garantindo suas funções.      |

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
| Recurso | Descrição |
|--------|-----------|
| Registrar advertências | Permite registrar advertências rapidamente. |
| Encaminhamento automático | Envia automaticamente cada advertência para coordenação/direção. |
| Notificações aos responsáveis | Envia alertas automáticos aos pais/responsáveis. |
| Histórico disciplinar | Mantém o histórico de advertências por aluno. |
| Consulta filtrada | Permite consultar por data, tipo, aluno, turma e usuário. |
| Relatórios | Gera relatórios mensais, por turma ou por tipo de ocorrência. |
| Controle de permissões | Controla o acesso conforme o nível do usuário. |

# 6. Casos de Uso
– Registrar Advertência

– Validar Advertência

– Homologar Advertência

– Notificar Responsáveis

– Consultar Histórico

 – Gerar Relatórios
## 6.1 Diagrama de Casos de Uso
<img width="950" height="601" alt="Diagramaindisciplina drawio" src="https://github.com/user-attachments/assets/5653e618-ca38-484c-ab3c-9a9522bb895a" />


## 6.2 Fluxo de Casos de Usos
1. Registrar Advertência

Ator Principal: Professor
Atores Secundários: Sistema

Fluxo Básico

1. O caso de uso inicia quando o Professor seleciona a opção Registrar Advertência.


2. O sistema exibe o formulário de registro.


3. O Professor informa os dados obrigatórios (aluno, motivo, descrição, data).


4. O Professor confirma o envio.


5. O sistema valida as informações.


6. O sistema salva a advertência como “Pendente de Validação”.


7. O sistema exibe uma mensagem de sucesso.


8. O caso de uso é encerrado.



Fluxos Alternativos

 — Dados incompletos: o sistema alerta o professor e solicita correção.

 — Erro no servidor: o sistema informa a falha e não registra a advertência.



---

2. Validar Advertência

Ator Principal: Coordenador
Atores Secundários: Sistema

Fluxo Básico

1. O Coordenador acessa a lista de advertências pendentes.


2. O sistema exibe todas as advertências aguardando validação.


3. O Coordenador seleciona uma advertência.


4. O sistema exibe os detalhes.


5. O Coordenador escolhe Validar ou Rejeitar.


6. O sistema atualiza o status da advertência.


7. O sistema registra data e usuário que realizou a validação.


8. O fluxo termina.



Fluxos Alternativos

 — Advertência rejeitada: o sistema marca como "Rejeitada" e solicita motivo ao Coordenador.

 — Advertência já validada: o sistema impede alterações e notifica o ator.



---

3. Homologar Advertência

Ator Principal: Administrador
Atores Secundários: Sistema

Fluxo Básico

1. O Administrador acessa advertências já validadas.


2. O sistema apresenta a lista.


3. O Administrador seleciona uma advertência.


4. O sistema exibe detalhes.


5. O Administrador confirma a homologação.


6. O sistema atualiza o status para “Homologada”.


7. O sistema registra data e usuário responsável.


8. O caso de uso termina.



Fluxos Alternativos

 — Administrador rejeita a homologação: sistema marca como "Homologação Negada" e solicita justificativa.

 — Advertência já homologada: o sistema avisa e não permite nova operação.



---

4. Notificar Responsáveis

Ator Principal: Sistema
Atores Secundários: Administrador / Coordenador (apenas visualização)

Fluxo Básico

1. A homologação da advertência dispara o processo.


2. O sistema identifica os responsáveis cadastrados do aluno.


3. O sistema envia notificação automática (e-mail, SMS ou portal).


4. O sistema registra a data da notificação.


5. O fluxo termina.



Fluxos Alternativos

 — Responsável sem contato cadastrado: sistema registra falha e informa ao Administrador.

 — Falha no envio: sistema tenta novamente e registra log do erro.



---

5. Consultar Histórico

Ator Principal: Professor / Coordenador / Administrador
Atores Secundários: Sistema

Fluxo Básico

1. O usuário acessa a opção Histórico de Advertências.


2. O sistema exibe filtros (aluno, data, status, curso).


3. O usuário seleciona os filtros desejados.


4. O sistema busca os registros.


5. O sistema exibe a lista e permite visualizar detalhes.


6. O caso de uso termina.



Fluxos Alternativos

 — Nenhum resultado encontrado: o sistema informa que não há registros.



---

6. Gerar Relatórios

Ator Principal: Administrador / Coordenador
Atores Secundários: Sistema

Fluxo Básico

1. O usuário acessa a opção Gerar Relatórios.


2. O sistema apresenta tipos de relatório (mensal, por aluno, por curso etc.).


3. O usuário escolhe o tipo e define filtros.


4. O sistema processa os dados.


5. O sistema gera o relatório em formato PDF ou visualização interna.


6. O caso de uso é encerrado.



Fluxos Alternativos

 — Falha na geração: o sistema informa erro e sugere tentar novamente.
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
