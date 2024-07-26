# Relatório de Configuração de Rede

## Contextualização da Topologia

Neste projeto, configurei uma topologia de rede para testar a conectividade e o acesso a recursos externos. A topologia inclui:

- **Roteadores e Switches:** Configurados para permitir a comunicação entre dispositivos na rede local e a conexão com a Internet.
- **Dispositivos Finais:** PCs ou servidores configurados para realizar testes de conectividade e resolução de nomes de domínio.

## Testes Realizados

1. **Teste de Conectividade com IP Público**

   Realizei um teste de conectividade utilizando o endereço IP público `8.8.8.8`, que é um dos servidores DNS do Google. O comando utilizado foi:
   
   `ping 8.8.8.8`
Este teste verifica se há conectividade com um servidor externo pela Internet, indicando que a configuração de NAT e roteamento estão funcionando corretamente.

2. **Teste de Conectividade por Nome de Domínio**

Para verificar a resolução de nomes de domínio e a conectividade com sites populares, realizei testes de ping para os seguintes domínios:

## YouTube:
`ping www.youtube.com`

## Facebook:
`ping facebook.com`

## Google:
`ping google.com`

Esses testes confirmam que a resolução de nomes de domínio está funcionando corretamente e que os dispositivos finais podem acessar os sites através de seus nomes de domínio.

# Conclusão
Todos os testes foram realizados com sucesso, confirmando que a configuração da rede está adequada para fornecer conectividade tanto por IP quanto por nomes de domínio. A conectividade com a Internet foram verificadas e estão funcionando conforme o esperado.
