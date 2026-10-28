# EspelhaTV Livre — atualizações

Versão disponível: **0.5.18**, versionCode **25**.

[Baixar versão 0.5.18](https://github.com/renancameta/espelhatv-livre-updates/releases/tag/v0.5.18)

Bloqueador revisado após inspeção da página real: filtros para a máscara transparente de clique publicitário, barra VIP e promoções de cabeçalho, conteúdo adulto e downloads de aplicativos. Preserva o iframe do player, logo principal, menus e controles. As imagens promocionais identificadas também são bloqueadas.

A regressão com trechos do DOM capturado falhou no filtro anterior e passou no novo. Testes JavaScript/Java, compilação, lint e testes Android passaram. A reprodução completa e o ensaio físico no celular/TV permanecem pendentes. Não há garantia de eliminar toda publicidade; marcas incorporadas ao próprio vídeo permanecem.

Mantém a interface aprovada, navegação direta de links, controle remoto, opções reais de qualidade e correção EBADF. APK para celular e Android TV, Android 8 ou superior. Pacote br.com.espelhartv.busca e certificado permanente preservados.

## Instalação

O aplicativo consulta latest.json ao abrir e oferece a versão nova. O download e a instalação exigem confirmação. Se uma versão anterior à 0.5.15 apresentar EBADF, baixe o APK e abra pelo navegador/gerenciador de arquivos do sistema, fora do EspelhaTV. Instale por cima, sem desinstalar ou apagar dados.

SHA-256: 28f735fabd32a7f1d0187a63c43f46cdcc724c7a25973339c456c2440b7d24e7.

Código-fonte e chave de assinatura permanecem privados.
