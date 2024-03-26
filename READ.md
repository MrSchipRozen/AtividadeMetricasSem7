# Atividade Metricas

# Tecnologidas utlizadas

-Prometheus: Este sistema funciona como um banco de dados para coletar, agregar e analisar métricas em série temporal. Capaz de adquirir dados periodicamente de serviços configurados, permite a análise dessas métricas como séries temporais e a sua representação através de gráficos.

-Jaeger: Esta ferramenta é empregada para o rastreamento de atividades em sistemas distribuídos, oferecendo a capacidade de monitorar dados, requisições e a interação entre várias aplicações através de uma interface gráfica para visualização.

-Grafana, uma ferramenta que facilita a criação de painéis de controle usando diversas fontes de dados. Na configuração presente, foi aproveitado para integrar e exibir dados obtidos do Prometheus.

-OpenTelemetry: Integrado à aplicação .NET, essa ferramenta tem a função de coletar e transmitir dados para os sistemas de monitoramento. Ela usa o protocolo OTLP para encaminhar dados ao Jaeger e o Prometheus Exporter para o Prometheus. Detalhes dessa integração podem ser observados na imagem subsequente. 

# Conceitos aprendidos

- Durante a configuracão dessa atividade eu fui aprendi a configurar ferramentas para monitorar uma aplicação em .NET, configurei o prometheus para poder coletar as metricas ofercendo graficos, aprendi também a configurar o grafana para poder receber todos os dados e gerar a dashboard para o acompanhmento de todas as metricas .

# Prints em execução

<img width="1792" alt="Screenshot 2024-03-26 at 10 38 45" src="https://github.com/MrSchipRozen/AtividadeMetricasSem7/assets/99350292/184ef40f-8a82-4005-9ef9-9e28afcb60c2">

<img width="1800" alt="Screenshot 2024-03-26 at 10 40 21" src="https://github.com/MrSchipRozen/AtividadeMetricasSem7/assets/99350292/5f0d4515-e9a8-4d67-8076-613261581fd0">

<img width="1760" alt="Screenshot 2024-03-26 at 10 40 42" src="https://github.com/MrSchipRozen/AtividadeMetricasSem7/assets/99350292/6544402e-700f-4539-9f50-fdc2d88ecb42">

<img width="1757" alt="Screenshot 2024-03-26 at 10 40 01" src="https://github.com/MrSchipRozen/AtividadeMetricasSem7/assets/99350292/8e72d6bf-44d0-46c0-90a7-713e73a3232c">

Conclusão - 



