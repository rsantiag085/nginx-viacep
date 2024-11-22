# Dockerfile Nginx - ViaCEP

Este projeto cria um container Docker com a aplicação Nginx exibindo a página de consulta de CEP da [ViaCEP](https://viacep.com.br/).

## Estrutura do Projeto

- **Dockerfile**: Define a imagem base do Nginx e copia o `index.html` para o servidor.
- **index.html**: Página HTML de exemplo retirada do site oficial da ViaCEP.

## Como Executar

1. **Buildar a imagem Docker**:
   ```bash
   docker build -t rsantiag085/nginx-viacep:latest .

### Principais Funcionalidades:

- Build de uma imagem Docker do Nginx com um arquivo HTML personalizado.
- Exposição da aplicação na porta 8080 para acesso local.
- Disponibilização da imagem no Docker Hub para fácil reuso.

### Como Usar:
Clone o repositório.
Build a imagem com o comando docker build.
Execute o container e acesse a aplicação via navegador.
