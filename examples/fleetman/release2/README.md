# Fleetman - Release 2
  
## Novidades

O rastreamento de veículos mostra o histórico de cada veículo.

> Problema: o histórico dos veículos está sendo armazenado em memória pelo microserviço **Position Tracker**, e isso pode acarretar em falta de memória ao longo do tempo.
>
>  **Solução:** Na **Release 3** será adicionado um novo microsserviço que se encarregará de tratar a persistência desses dados.