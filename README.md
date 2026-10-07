# Conecta Check-in — atualizações

Este repositório público distribui os instaladores Windows, o APK Android e os metadados de atualização do Conecta Check-in.

## Instalador online permanente

Baixe [Conecta-Check-in-Instalador-Online.exe](https://raw.githubusercontent.com/renezit0/conecta-checkin-updates/main/Conecta-Check-in-Instalador-Online.exe). Este link permanece igual: ao abrir o arquivo, ele consulta a release mais recente, baixa o Setup correspondente, verifica sua integridade e inicia a instalação. Requer internet e Windows com .NET Framework 4.x.

Se preferir baixar diretamente uma versão específica, abra a [release mais recente](https://github.com/renezit0/conecta-checkin-updates/releases/latest) e escolha `Conecta-Check-in-Setup-*-x64.exe`. O Setup instala o app e consulta futuras atualizações. O executável portátil é separado e não recebe instalação automática de updates.

No app instalado, use **Mais opções > Verificar atualizações** para consultar manualmente. Após baixar uma nova versão, o app oferece reiniciar e instalar.

## Android

Na [release mais recente com APK Android](https://github.com/renezit0/conecta-checkin-updates/releases), baixe o arquivo `Conecta-Checkin-Android-X.Y.Z.apk` e abra no celular para instalar. O Android pode pedir permissão para instalar apps desta fonte.

Depois da instalação, o app procura atualizações quando é aberto. Também é possível tocar em **Ajustes > Aplicativo > Verificar atualização**. Se houver uma versão Android mais recente, o app baixa o APK e abre a confirmação de instalação do próprio Android. A instalação por cima preserva os dados quando o APK usa a mesma assinatura.

Os APKs Android seguem sua própria numeração nos nomes dos arquivos. Releases de Windows sem um APK novo não são tratadas como atualização Android.

O código-fonte fica no repositório privado do projeto; esta área pública contém apenas os arquivos necessários para instalação e atualização.
