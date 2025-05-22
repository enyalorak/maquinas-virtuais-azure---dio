# maquinas-virtuais-azure---dio
DIO - Criando máquinas Virtuais na Azure

Resumo: Criando Máquinas Virtuais na Azure
Ao criar uma máquina virtual (VM) na Azure, a eficiência e o custo estão diretamente ligados ao SLA (Service Level Agreement), que representa o tempo garantido de disponibilidade do serviço. Quanto maior o SLA, menor o tempo de inatividade e, consequentemente, maior o custo da VM.

Exemplos de SLA e Tempo de Inatividade (TIna):
99%: até 3,65 dias/ano de inatividade

99,9%: até 8,76 horas/ano

99,95%: até 4,38 horas/ano

99,99%: até 52,56 minutos/ano

99,999%: até 5,26 minutos/ano

Além disso, a Azure oferece a opção de configurar zonas de disponibilidade, permitindo distribuir as VMs entre diferentes zonas para maior resiliência. Selecionar múltiplas zonas implica na criação de várias VMs, o que também impacta no custo.

👉 Por isso, é essencial definir claramente o propósito da VM e avaliar o custo-benefício ao escolher o SLA e as configurações de disponibilidade.
