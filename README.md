+-- .ArquivosXML        
    +-- NFe
        +-- ConsultaStatusServidorNFe           #Consultas do status dos Webservices
            +-- AAAA-MM-DDTHHMMSS.-ped-sta.xml  # envio
            +-- AAAA-MM-DDTHHMMSS.-sta.xml      # resposta
        +-- ConsultaCadastro                    #Consulta cadastro contribuinte
            +-- XXX*_*YYY-cons-cad.xml          # XXX=CPF*_* ou CNPJ*_* ou IE*_*, YYY=numero CPF/CNPJ/IE, envio
            +-- XXX*_*YYY-cad.xml               # XXX=CPF*_* ou CNPJ*_* ou IE*_*, YYY=numero CPF/CNPJ/IE, resposta
        +-- homologacao                         #Emitidos em ambiente de homologação. (igual ao produção)
        +-- producao                            #Emitidos em ambiente de produção.
            +-- AAAA-MM                         #Ano e mês da emissão
                +-- NFeSituacao                 #Consulta da situação atual da NF-e na Base de Dados do Sefaz
                    +-- XXX-ped-sit.xml         # XXX=chave de acesso NFe, envio
                    +-- XXX-sit.xml             # resposta
                +-- Lotes                       #Envio de lote de NFes
                    +-- XXX-env-lot.xml         # XXX=idLote, envio
                    +-- XXX-rec.xml             # resposta
                    +-- XXX-nfe.xml             # XXX=chave nfe, NF-es do lote enviado
                +-- Recibos                     #Consulta de recibos
                    +-- XXX-ped-rec.xml         # XXX=numero do recibo, envio
                    +-- XXX-pro-rec.xml         # resposta
                +-- NFeAutorizada               #Notas autorizadas
                    +-- XXX-pro-nfe-aut.xml     # XXX=chave, protocolo da nota autorizada
                    +-- XXX-proc-nfe.xml        # processamento da nota autorizada, com a NFe e protocolo
                +-- NFeDenegada                 #Notas denegadas
                    +-- XXX-pro-nfe-den.xml     # XXX=chave, protocolo da nota denegada
                    +-- XXX-proc-nfe-den.xml    # processamento da nota denegada, com a NFe e protocolo
                +-- NFeRejeitada                #Notas rejeitadas
                    +-- XXX-pro-nfe-rej.xml     # XXX=chave, protocolo da nota rejeitada
                    +-- XXX-proc-nfe-rej.xml    # processamento da nota rejeitada, com a NFe e protocolo
        
