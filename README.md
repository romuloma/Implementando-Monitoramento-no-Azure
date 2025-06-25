# Monitoramento de Máquinas Virtuais no Azure com Log Analytics

## Descrição
Repositório de apoio para configuração, monitoramento e análise de eventos críticos em máquinas virtuais do Azure utilizando Azure Monitor e Log Analytics.

## Índice
- [Pré-requisitos](#pré-requisitos)
- [Configuração do Monitoramento](#configuração-do-monitoramento)
- [Criação de Alertas](#criação-de-alertas)
- [Consultas no Log Analytics](#consultas-no-log-analytics)
- [Dicas e Boas Práticas](#dicas-e-boas-práticas)
- [Referências](#referências)

## Pré-requisitos
- Conta no Azure
- Permissão para criar e gerenciar recursos
- Conta no GitHub

## Configuração do Monitoramento

1. **Implante o Agente do Azure Monitor**  
   Instale o agente nas VMs para coletar dados do sistema operacional e das cargas de trabalho.

2. **Habilite o VM Insights**  
   Ative os insights para monitorar desempenho, processos e dependências das VMs.

3. **Configure Regras de Coleta de Dados (DCR)**  
   Defina quais logs e métricas serão coletados do sistema operacional e aplicativos.

4. **Valide a Coleta de Dados**  
   Use o portal do Azure para visualizar gráficos de desempenho e mapas de dependências.

## Criação de Alertas

- Configure alertas para eventos críticos, como exclusão de VMs, alto uso de CPU ou falhas de conectividade.
- Associe grupos de ação para notificar administradores via e-mail ou outros canais.

## Consultas no Log Analytics

- Utilize a linguagem KQL (Kusto Query Language) para criar consultas personalizadas.
- Exemplos de consultas para identificar eventos de exclusão, uso de CPU, logs de erro, etc.

## Dicas e Boas Práticas

- Documente cada etapa com clareza e objetividade.
- Use queries pré-definidas do Log Analytics como ponto de partida, adaptando conforme necessário.
- Estruture o conteúdo para facilitar a leitura e a busca de informações.
- Atualize o README.md sempre que houver mudanças relevantes no ambiente ou nas práticas.

## Referências

- [Configurar o monitoramento de máquinas virtuais - Microsoft Learn](https://learn.microsoft.com/pt-br/training/modules/configure-monitoring-virtual-machines/)
- [Tutorial: Habilitar o monitoramento com insights de VM](https://learn.microsoft.com/pt-br/azure/azure-monitor/vm/tutorial-monitor-vm-enable-insights)
- [Documentação de introdução ao GitHub](https://docs.github.com/pt/get-started)
- [Melhores práticas para documentos do GitHub](https://docs.github.com/pt/contributing/writing-for-github-docs/best-practices-for-github-docs)
