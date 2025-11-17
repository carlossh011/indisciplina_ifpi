# 1.Escopo do Projeto
O problema consiste na demora das advertências infratórias, que se acumulam, demoram a ser registradas e a ser recebidas pelos pais. Em alguns casos, os alunos não entregam as advertências aos pais, e, assim, eles não ficam informados sobre elas.
# 2. Problema
O processo de registro e comunicação das advertências.
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
| Nome                | Descrição                                            | Função                                                                 |
|---------------------|------------------------------------------------------|------------------------------------------------------------------------|
| Time de Gerenciamento | Grupo de alunos de APS do IFPI-Campus Angical       | Gerenciamento de projeto e dos membros do time de desenvolvimento, assim como contato com o cliente para definição de requisitos. |
## 3.2 Resumo dos Usuarios
| Nome   | Descrição                                   |
|--------|---------------------------------------------|
| Alunos | Ter acesso às INFRAÇÕES DISCIPLINARES.     |


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
Registro de advertências
- Professores podem registrar advertencias diretamente pelo sistema

Fluxo automatizado
- Advertências são enviadas automaticamente a coordenação e direção para validação.

Notificações aos pais
- Envio de sms, e-mail ou notificação via aplicativo(whatswapp ou outro) para os responsaveis

Histórico disciplinar
- ficha do aluno com todas as advertências registradas, organizadas por data e tipo.

Painel de acompanhamento
- Coordenação e direção podem visualizar o andamento das advertências.

Relatorios
- Geração de relatorios mensais ou por turma.

Controle de permissões
- Cada usuario acessa apenas suas funções (professor, coordenação, direção, pais).

# 6. Casos de Uso

## 6.1 Diagrama de Casos de Uso

## 6.2 Fluxo de Casos de Usos

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
