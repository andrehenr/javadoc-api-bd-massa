## javadoc-api-bd-massa

Documentação da API para comunicação com o banco de dados.

### Download 

O Download do jar pode ser encontrado em [package](https://andrehenr.github.io/javadoc-api-bd-massa/jar/api-bd-massa-1.0.jar).

### Java Doc

O JavaDoc completo da API pode ser encontrado em [JavaDoc](https://andrehenr.github.io/javadoc-api-bd-massa/apidocs/index.html).

### Modo de usar

```Java

	//Para buscar a massa do cenário com ID "URA98"
	Cenario cenarioUra98 = new CenarioBuilder.buscaCenario("URA98");
	Massa massaDoCenarioUra98 = cenarioUra98.massa();
	
	//Busca o renavam para o mesmo ID de cenário acima
	Renavam renavam = cenarioUra98.renavam();
	
	//Coleta o primeiro renavam do renavam do Cenario com ID "URA98"
	String primeiroRenavam = renavam.getRenavam1();
	
	//Busca o código de barras para o mesmo ID do cenário acima
	CodigoBarras codigoBarras = cenarioUra98.codigoBarras();

	//Coletar o número do código de barras relacionado ao código de barras acima
	String numeroCodigoBarras = codigoBarras.getCodigoBarras();
```

Para mais informações acesse o [JavaDoc](https://andrehenr.github.io/javadoc-api-bd-massa/apidocs/index.html) ou entre em contato com andre.graca@rsinet.com.br 


