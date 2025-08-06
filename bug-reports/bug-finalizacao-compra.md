# Bug Report: Falha ao finalizar compra com campo ZIP vazio

*ID*: BUG-CHECKOUT-02  
*Data*: 05/08/2025  
*Encontrado por*: Ewellyn Melo  
*Gravidade*: Alta  
*Funcionalidade*: Finalização de compra (Checkout)

### Descrição:
Ao tentar finalizar uma compra com os campos "First Name" e "Last Name" preenchidos, mas sem preencher o campo “ZIP/Postal Code”, o sistema não bloqueia o usuário e prossegue para a tela seguinte.

### Passos para Reproduzir:
1. Ir até a tela de checkout
2. Preencher apenas First Name e Last Name
3. Deixar ZIP vazio
4. Clicar em “Continue”

### Resultado Esperado:
Sistema deve exibir uma mensagem de erro solicitando o preenchimento do campo obrigatório.

### Resultado Obtido:
Usuário é redirecionado para a próxima etapa sem validação.

### Evidência:
<img width="1421" height="694" alt="Captura de Tela 2025-08-06 às 00 27 40" src="https://github.com/user-attachments/assets/39cb9203-8f5e-42ea-9afe-6db87d84540b" />

### Status: Aberto
