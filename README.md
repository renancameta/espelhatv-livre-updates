# EspelhaTV Livre — atualizações

Versão disponível: **0.5.17**, versionCode **24**.

[Baixar versão 0.5.17](https://github.com/renancameta/espelhatv-livre-updates/releases/tag/v0.5.17)

Esta versão acrescenta filtros para o aviso promocional de instalação toggleVPN e para faixas de Telegram/aluguel de API no contexto relatado. Os testes preservam player, controles, catálogo e pôsteres e verificam que o filtro não aciona Instalar. A validação usa exemplos locais baseados na imagem; confirmar na página e no aparelho reais. Os filtros não garantem eliminar toda publicidade.

Links de nova aba abrem na tela principal. Colar um endereço completo pelo menu ou teclado abre automaticamente, sem outro toque em Abrir. Links recebidos de outro aplicativo por ACTION_VIEW também são abertos diretamente, conforme a escolha feita no Android. Redirecionamentos HTTP normais são permitidos; filtros de anúncios conhecidos, saídas automáticas por script e janelas extras permanecem ativos.

Erros de DNS têm explicação e ações Tentar novamente e Editar endereço. A atualização não torna acessível um domínio indisponível nem resolve uma falha externa da rede. Não escolhe endereços alternativos.

Mantém o visual aprovado, o controle remoto e a correção EBADF da 0.5.15. APK para celular e Android TV, Android 8 ou superior. Pacote br.com.espelhartv.busca e certificado permanente preservados.

Compilação, lint, 11 testes Android e testes JavaScript/Java passaram. Teste de navegação nos aparelhos e na rede do usuário ainda pendente.

## Instalação

A partir da 0.5.15, as ofertas pelo feed usam o instalador corrigido e exigem confirmação do Android. Se uma versão anterior apresentar EBADF, baixe o APK e abra pelo navegador/gerenciador de arquivos do sistema, fora do EspelhaTV. Instale por cima, sem desinstalar ou apagar dados.

SHA-256: c270c21c6e08061233194768efec9dfd15b967a6b51783448469e5144d5cbae3.

Código-fonte e chave de assinatura permanecem privados.
