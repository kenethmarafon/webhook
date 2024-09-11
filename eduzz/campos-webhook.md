# Documentação de eventos webhook - Kiwify para a Devzapp

Para se integrar com eventos do tipo fatura, deve ser seguida a documentação abaixo.
Ela descreve quais campos e quais tipos de dados serão enviados enviandos na integração da Kiwify com a Devzapp.

Os eventos são enviados toda vez que é gerado um novo evento de fatura na Kiwify.

Parâmetro | Descrição
------------- | -------------
aff_cod | Id do afiliado | Int?
aff_document_number | Documento do afiliado | String?
aff_email | E-mail do afiliado | String?
aff_name |  Nome do afiliado | String?
aff_value | Valor da comissão do afiliado | Float?
billet_url | Página com a chave gerada para o produto | String
cus_address | Endereço do cliente | String
cus_address_city | Cidade do cliente | String
cus_address_comp | Complemento do endereço do cliente | String
cus_address_country | País do cliente | String
cus_address_district | Bairro do cliente | String
cus_address_number | Numero do endereço do cliente | String
cus_address_state | Estado do clieente | String
cus_address_zip_code | CEP do cliente | String
cus_cel | Celular do cliente | String
cus_tel | Telefone do cliente | String
cus_tel2 | Segundo telefone do cliente | String
cus_cod | Id do cliente na Eduzz | Int
