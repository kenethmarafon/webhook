# Documentação de eventos webhook - Ticto para a Devzapp ⚡

### Versão 2.0 (Recomendada)

Para se integrar com eventos do tipo fatura, deve ser seguida a documentação abaixo.
Ela descreve quais campos e quais tipos de dados serão enviados enviandos na integração da Ticto com a Devzapp.

Os eventos são enviados toda vez que é gerado um novo evento de fatura na Ticto.

Parâmetro | Descrição | Formato e tamanho suportado
| ------------------ | ------------------ | ------------------ |
| campanhaId | | |
| customer_address_city | | |
| customer_address_complement | | |
| customer_address_neighborhood | | |
| customer_address_state | | |
| customer_address_street | | |
| customer_address_street_number | | |
| customer_address_zip_code | | |
| customer_cnpj | | |
| customer_cpf | | |
| customer_email | | |
| customer_is_foreign | | |
| customer_name | | |
| customer_phone_ddd | | |
| customer_phone_ddi | | |
| customer_phone_number | | |
| customer_type | | |
| dataCriacao | | |
| idPai | | |  
| idProcess | | 
| item_amount | | 
| item_coupon_id | | 
| item_days_of_access | | 
| item_members_classroom_id | | 
| item_members_portal_id | | 
| item_offer_id | | 
| item_offer_name | | 
| item_product_id | | 
| item_product_name | | 
| item_quantity | | 
| item_trial_days | | 
| order_hash | | 
| order_installments | | 
| order_paid_amount | | 
| payment_method | | 
| status | Status da Compra | <span style="color:blue">Possíveis valores</span> <br> **abandoned_cart:** Abandono de Carrinho <br> **authorized:** Venda Realizada <br> **bank_slip_delayed:** Boleto Atrasado <br> **bank_slip_created:** Boleto Impresso <br> **chargeback:** Chargeback <br> **close:** Encerrado <br> **pix_created:** Pix Gerado <br> **pix_expired:** Pix Expirado <br> **refunded:** Reembolso <br> **refused:** Venda Recusada <br> **trial:** Tempo de Teste <br> waiting_payment: Aguardando Pagamento <br> all_charges_paid: [Assinatura] - Encerrada (Todas as Cobranças Finalizadas) <br> card_exchanged: [Assinatura] - Cartão atualizado <br> extended: [Assinatura] - Extendida <br> subscription_canceled: [Assinatura] - Cancelada <br> subscription_delayed: [Assinatura] - Atrasada <br> trial_started: [Assinatura] - Período de Testes Iniciado <br> trial_ended: [Assinatura] - Período de Testes Encerrado <br> uncanceled: [Assinatura] - Retomada <span style="color:red">Este texto é vermelho</span>
<span style="color:blue">Este texto é azul</span>|
| telefone | | |
| token | | |
| transaction_bank_slip_code | | |
| transaction_bank_slip_url | | |
| url_params_query_params_code | | |
