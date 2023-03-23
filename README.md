# rum

## Instalação react-native
https://docs.datadoghq.com/real_user_monitoring/reactnative/

pontos de atenção:
 - No aplicativo para IOS nós usamos use_frameworks! (configuração do Podfile(gerenciador de dependencias swift/objetive C)), e na documentação inicial a uma nota sobre um problema com essa config e uma solução 
 
 https://docs.datadoghq.com/real_user_monitoring/reactnative/#troubleshooting
 
 ### Features de nosso interesse:
 - Metadados sobre o usuário que está usando a aplicação
 - Crashreport (javascript e nativo)
 - Envio de sourcemaps para melhor compreensão dos erros
 - Envio de eventos com diferentes níveis de severidade e metadados adicionais
 
 ### Partes especificas da documentação para implementação das features de nosso interesse
 
 - Metadados do usuário que está usando a aplicação
 https://docs.datadoghq.com/real_user_monitoring/reactnative/#user-information
 
 - Crashreport
 tanto nativo como javascript: https://docs.datadoghq.com/real_user_monitoring/error_tracking/reactnative/
 
 - Envio de sourcemaps
 https://docs.datadoghq.com/real_user_monitoring/error_tracking/reactnative/#symbolicate-crash-reports
 
 - Envio de eventos com diferentes níveis de severidade e metadados adicionais
 https://docs.datadoghq.com/real_user_monitoring/reactnative/advanced_configuration/#manual-instrumentation
 ![image](https://user-images.githubusercontent.com/9970959/227126171-439b8510-6beb-4780-b3c7-d82222c5dd83.png)
