# 👷♀ Rodar JAR e Publicar IG

Após todas as ferramentas instaladas e o projeto baixado, falta rodar o publisher e gerar o <mark style="color:red;">**Guia de Implementação**</mark> <mark style="color:red;"></mark><mark style="color:red;"></mark> básico.&#x20;

Para rodar o publisher, abra o <mark style="color:blue;">**terminal CMD**</mark> (com power shell podem haver problemas de codificação UTF-8) e utilize o seguinte comando:

```
java -Dfile.encoding=UTF-8 -jar -Xms1g -Xmx4g publisher.jar -ig ig.ini -tx 'n/a'
```

![](<../.gitbook/assets/image (1).png>)

Depois de rodar e dar certo, cria a estrutura restante e a pasta com os templates e output (HTML)

![](<../.gitbook/assets/image (8).png>)

Para saber se tudo está pronto e deu certo, é necessário acessar a pasta output e rodar o index.html.&#x20;

![](<../.gitbook/assets/image (11).png>)

