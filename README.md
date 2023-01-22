# carbon-credits-setup
Setup dos contêineres docker para a aplicação de créditos de carbono

## Instruções

1. É necessário ter o Docker e Docker Compose instalados
2. Clone esse repositório
3. Clone o repositório do [API Gateway](https://github.com/all-minds/GatewayAPI) na raiz do projeto
4. Clone o repositório do [Owner API](https://github.com/all-minds/OwnerAPI) na raiz do projeto
5. Clone o repositório do [Property API](https://github.com/all-minds/PropertyAPI) **dentro da pasta PropertyAPI**
6. Clone o repositório do [sft-eng-front-end](https://github.com/all-minds/sft-eng-front-end) na raiz do projeto
6. No fim, a estrutura de diretórios estará dessa forma:

+ carbon-credits-setup (setup clonado)
	+ GatewayAPI (repositório clonado)
	+ OwnerAPI (repositório clonado)
	+ PropertyAPI
		+ PropertyAPI (repositório clonado)
	+ sft-eng-front-end

Tendo feito isso, basta ir na raiz do setup clonado e rodar docker compose up.