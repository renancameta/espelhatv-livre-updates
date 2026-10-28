# EspelhaTV Livre — distribuição

**Candidata 0.5.19 para revisão de segurança.**

[APK e notas da candidata 0.5.19](https://github.com/renancameta/espelhatv-livre-updates/releases/tag/v0.5.19)

Foi relatado alerta “App nocivo bloqueado” do Play Protect durante uma atualização da versão instalada 0.5.17. A causa e a classificação do Google continuam sob investigação. Não desative o Play Protect para instalar. Ainda não há resultado de antivírus externo nem decisão de contestação.

A candidata acrescenta tratamento de pedidos IMA antes do vídeo e reforça os limites e a autenticação do receptor da TV, mantendo a interface. O mecanismo de resposta sem anúncios foi confirmado no inspector oficial IMA, e os testes de código passaram. A reprodução completa no player real e no aparelho continua pendente.

Oito suítes JavaScript, regressões Java, 11 testes Android, compilação e lint passaram. Consulta OSV completa para 69 dependências Maven de runtime sem alertas conhecidos retornados em 28/10/2026. Isso não equivale a certificação antimalware.

A candidata **não está ativada no feed automático**. latest.json permanece em 0.5.18/code 25 até a conclusão da revisão externa.

APK universal para celular e Android TV, Android 8 ou superior. Pacote br.com.espelhartv.busca, versionCode 26 e certificado permanente preservados.

SHA-256 da candidata: dbd51e934093ba6dfd01666c449f4502e06010c985cae751269c1e7323041089.

Código-fonte e chave de assinatura permanecem privados.
