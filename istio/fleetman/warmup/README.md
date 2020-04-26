# Fleetman on Istio

 Passo a passo para deixar o sistema rodando com Istio:

- Os três primeiros arqvuivos YAML servem para configurar o Istio + Minikube
> Atenção, antes de executar o YAML da aplicação, é necessário informar ao Istio qual namespace que ele poderá injetar os Sidecars Containers nos Pods. Isso é feito aplicando a label **istio-injection=enabled** no namespace desejado.
- O Último YAML irá subir a aplicação