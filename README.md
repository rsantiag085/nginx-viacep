# Dockerfile Nginx - ViaCEP

Este projeto cria um container Docker com a aplicação Nginx exibindo a página de consulta de CEP da [ViaCEP](https://viacep.com.br/).

## Estrutura do Projeto

- **Dockerfile**: Define a imagem base do Nginx e copia o `index.html` para o servidor.
- **index.html**: Página HTML de exemplo retirada do site oficial da ViaCEP.

## Como Executar

1. **Buildar a imagem Docker**:
   ```bash
   docker build -t rsantiag085/nginx-viacep:latest .
