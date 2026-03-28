# Relatório de Implementação AWS - Abstergo Industries

## 1. Amazon S3 (Intelligent-Tiering)
- **Foco:** Redução de custo de armazenamento de mídia.
- **Caso de Uso:** Armazenamento de vídeos de 80GB da Câmara de Mimoso do Sul. O Intelligent-Tiering move arquivos antigos para camadas baratas automaticamente.

## 2. Amazon VPC (Segurança de Rede)
- **Foco:** Isolamento de dados sensíveis.
- **Caso de Uso:** Criação de sub-redes privadas para o banco de dados RDS, garantindo que apenas a aplicação C# acesse os dados, bloqueando a internet externa.

## 3. Amazon DynamoDB + DAX
- **Foco:** Performance e economia de leitura.
- **Caso de Uso:** Cache de metadados das fotografias do acervo, reduzindo a latência e o custo de leitura no banco principal.
