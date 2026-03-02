# Mapa KISS de Entradas e Saídas

## Entradas

- **Botões Físicos Centrais**: Botões utilizados para controle de operações. Ex: Botão de Início e Botão de Parada.
- **E-STOP**: Botão de parada de emergência. Gere um sinal de emergência que interrompe todas as operações.
- **Alavanca de Abort**: Utilizada para abortar uma operação em andamento, geralmente em situações críticas.
- **Fins de Curso NC**: Sensores de fim de curso Normally Closed (NC) que indicam a posição de extremidade de um atuador.

## Saídas

- **BUS_ENABLE**: Sinal para habilitar o barramento de comunicação.
- **ACTUATOR_ENABLE**: Sinal para ativar atuadores.

## Polaridades

- Usar polaridade adequada para não gerar curto-circuitos.

## Exemplos Práticos de Cabeamento/Interligação Fail-Safe

1. **Botões Físicos**: Conectar em série, utilizando resistores para garantir sinal de força em falha.
2. **E-STOP**: Conectar diretamente ao sistema de controle, com circuitos de backup para sinal de interrupção.
3. **Alavanca de Abort**: Utilizar um esquema de duplicação de sinal para garantir que o abort funcione mesmo se um circuito falhar.
4. **Fins de Curso NC**: Certificar que o sinal Normalmente Fechado não seja interrompido durante o uso normal da máquina.

5. **Diagrama Exemplo**: Inclua um diagrama visual dos cabeamentos e suas interligações para facilitar a compreensão.  

