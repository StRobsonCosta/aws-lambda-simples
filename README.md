# aws-lambda-simples
aulas de aws Alura

No Lambda é possível definir Regras Assíncronas (Servless) para realizar Funções de acordo com estratégias, exemplo, sempre que um arquivo com tamanho de XX mb for recebido por UpLoad ... faça tal ação.

# Comando cli para subir regras de lambda

- aws lambda update-function-code --function-name primeiraFuncao --zip-file fileb://lambda.zip
(exemplo em node, foi criado um código para lidar com log, transformado em zip e feito updload)

## Relevante

- No serviço *Amazon EventBridge* é possível criar cronogramas para disparar eventos no *Lambda*
- CloudWatch para Monitorar os Logs
