# portifólio QA - Rozsannah
Testes manuais realizados em sites reais para portifólio de transição para QA Júnior .
## Projeto 01 : Site IPTV One Play
**Data**:27/05/2025  | **Tipo**: Tetse Funcional + Usuabilidade Mobile
**URL Testada**? https://sites.google.com/views/iptv-aplicativosdetv-assitir/inicio

### Bugs Encontrados : 2

#### BUG-01 : CRITICO - CTA com redirecionamento inseguro
**Descrição**: Botão "Faça um teste" exibe página intermediaria do Google antes de abrir whatsApp.
**Impacto**: Usuário desconfia e abandona. Perda de conversão direta.
**Passo a passo**:
1. Acessar o site
2. Clicar em "Faca o teste"
3. Exibe tela "Redirecting you to...."
**Resultado esperado**: Abrir whatsApp direto
**Evidencia**: [Ver print](./evidências, iptv-oneplay/BUG-01_redirect_whatsApp.png)

####BUG-02 : ALTA - Falha no carregamento de imagem mobile
**Descrição**: Imagens não renderizam em resolução adequada. Só carregam com zoom.
**Impacto**: Experiência amadora. Cliente Cliente não entende a oferta.
**Evidencia**: [Ver print](./evidências/ iptv-oneplay/BUG-02_Imagem_quebrada_mobile.png)

### Ferramentas Utilizadas 
Chrome Devtools , Testes Manuais , Google Sheets

### Planilha completa 
https://docs.google.com/spreadsheets/d/1eBTvcY2I2wzBPCqApqdDog7rBYxpeJMgqRvUIC-CZLs/edit?usp=sharing



