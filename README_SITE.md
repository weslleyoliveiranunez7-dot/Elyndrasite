# ELYNDRA — Site oficial

Site estático preparado para publicação no GitHub Pages.

## Beta Android
O APK de testes está em `downloads/ELYNDRA-beta.apk`. O botão da seção **BETA PARA TESTADORES** baixa diretamente esse arquivo.

## Publicar/atualizar o site
1. Envie o conteúdo deste repositório para a branch `main`.
2. No GitHub, abra **Settings → Pages** e selecione **GitHub Actions** como fonte, se ainda não estiver configurado.
3. O workflow `.github/workflows/pages.yml` publica automaticamente o site a cada atualização na branch `main`.
4. Confira a aba **Actions** e abra o endereço publicado pelo GitHub Pages.

## Observações
- O contador regressivo original foi preservado e continua atualizando a cada segundo até 08/11/2026.
- A página identifica o APK como **beta para testadores**, não como versão final.
- O arquivo APK foi copiado sem alteração; este pacote não modifica o conteúdo interno do jogo.
