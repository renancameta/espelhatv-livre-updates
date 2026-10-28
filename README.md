# EspelhaTV Livre — distribuição

**Candidata 0.5.19 para revisão de segurança.**

[APK e notas da candidata 0.5.19](https://github.com/renancameta/espelhatv-livre-updates/releases/tag/v0.5.19)

Foi relatado alerta “App nocivo bloqueado” do Play Protect durante uma atualização da versão instalada 0.5.17. A causa e a classificação do Google continuam sob investigação. Não desative o Play Protect para instalar. A análise externa no VirusTotal foi concluída; a contestação ao Google ainda não foi enviada.

A candidata acrescenta tratamento de pedidos IMA antes do vídeo e reforça os limites e a autenticação do receptor da TV, mantendo a interface. O mecanismo de resposta sem anúncios foi confirmado no inspector oficial IMA, e os testes de código passaram. A reprodução completa no player real e no aparelho continua pendente.

Oito suítes JavaScript, regressões Java, 11 testes Android, compilação e lint passaram. Consulta OSV completa para 69 dependências Maven de runtime sem alertas conhecidos retornados em 28/10/2026. Isso não equivale a certificação antimalware.

A candidata **não está ativada no feed automático**. latest.json permanece em 0.5.18/code 25 até a conclusão da revisão externa.

APK universal para celular e Android TV, Android 8 ou superior. Pacote br.com.espelhartv.busca, versionCode 26 e certificado permanente preservados.

SHA-256 da candidata: dbd51e934093ba6dfd01666c449f4502e06010c985cae751269c1e7323041089.

Código-fonte e chave de assinatura permanecem privados.

## Resultados externos — 28/10/2026

- [0.5.18: 0/66 detecções](https://www.virustotal.com/gui/file/28f735fabd32a7f1d0187a63c43f46cdcc724c7a25973339c456c2440b7d24e7?nocache=1). Houve 1 timeout e 8 mecanismos sem suporte; mecanismo Google retornou Undetected.
- [0.5.19: 0/65 detecções](https://www.virustotal.com/gui/file/dbd51e934093ba6dfd01666c449f4502e06010c985cae751269c1e7323041089?nocache=1). Houve 3 falhas (ALYac, Elastic e Google) e 7 mecanismos sem suporte. Falha não equivale a resultado limpo.

Os resultados descrevem os mecanismos que completaram a análise. Não garantem segurança nem equivalem a uma decisão do Play Protect. A oferta automática da candidata continua pendente da revisão.
