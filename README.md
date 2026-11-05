# EspelhaTV Livre — distribuição

**Versão atual: 0.5.22 (versionCode 29).**

[Baixar APK e consultar as notas](https://github.com/renancameta/espelhatv-livre-updates/releases/tag/v0.5.22)

## Correção do redirecionamento ao tocar no vídeo

Bloqueia o caminho publicitário da Shopee relatado e mantém links de players incorporados dentro do próprio frame. Toque ou sinal de redirecionamento, isoladamente, não autorizam trocar a página principal por outro domínio. O endereço seguro é preservado; páginas rejeitadas não substituem o endereço pela finalização do carregamento. O fallback interrompe uma saída já iniciada e reabre a página segura, podendo reiniciar o player.

Mantém interface, controles, qualidade e ponte de transmissão. Links externos sem informações suficientes para confirmar a navegação ficam disponíveis em Configurações para abertura deliberada; o campo de endereço continua permitindo escolher um site.

## Atualização e assinatura

A 0.5.22 usa a mesma assinatura da 0.5.21 e pode atualizar essa versão sem desinstalar. O aplicativo consulta latest-20261104.json ao abrir; download e instalação continuam sujeitos à confirmação e às verificações do Android.

Versões com a chave antiga (até 0.5.20) precisam da reinstalação manual já documentada porque a chave anterior foi perdida. Desinstalar pode apagar dados locais. O feed legado latest.json permanece na 0.5.20 para não oferecer um APK incompatível àquelas instalações.

## Validação

Dez suítes JavaScript, regressões Java, 21 testes Android, compilação e lint passaram: zero erros e 22 avisos de lint. OSV: 69 dependências de runtime, consulta completa, sem alertas conhecidos; não é laudo antimalware. Os sete assets do APK correspondem ao código testado. O APK público foi baixado sem sessão e verificado por hash, pacote, versão, certificado e alinhamento.

O cenário é baseado na imagem fornecida e em regressões do WebView e do script de links. O site anterior do filme e sua sequência de requisições não aparecem na imagem; não houve reprodução real do filme ou ensaio desta versão na TV física. Não há garantia de bloquear toda publicidade. APK universal para Android 8 ou superior; não é aplicativo Tizen.

**Play Protect:** o alerta anterior continua sem confirmação de retirada. Esta publicação não representa aprovação do Google e mantém as proteções do Android. Resultados antimalware e contestação anteriores não equivalem à análise deste novo APK.

SHA-256 do APK: d07eb3a95846c1727363b3e5a3f45d5f96d0bac12593b7abfe0de3c2e52a06b8.

SHA-256 do certificado: 84ce6393b645d70415f43c86e779c3799316541adf57e93c8c3b0fdc5b06d7b4.

Código-fonte, chave e senhas não ficam neste repositório público.
