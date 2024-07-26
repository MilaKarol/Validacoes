# Validação de CPF e Email📰📧
 
Este repositório contém dois scripts JavaScript para validação de CPF e email. Abaixo está uma explicação detalhada de como cada script funciona.
 
## Validação de CPF📰
 
O script de validação de CPF adiciona um escutador de evento ao formulário de CPF e valida o CPF quando o formulário é enviado.
 
## Validação de Email📧
 
### Script (email.js)📍
O script de validação de email contém quatro funções principais para verificar se o email é válido quando o campo perde o foco e se o campo de email está preenchido quando o formulário é enviado.
 
1. **Função `checarEmail`**:
   - Esta função é chamada quando o campo de email perde o foco.
   
2. **Verificação de caracteres**:
   - A função verifica se o email contém os caracteres "@" e ".", e se o campo não está vazio.
   
3. **Mensagem de validação**:
   - Exibe uma mensagem indicando se o email é válido ou inválido.
   
4. **Função `verifica`**:
   - Esta função é chamada quando o formulário é enviado, verificando se o campo de email não está vazio.