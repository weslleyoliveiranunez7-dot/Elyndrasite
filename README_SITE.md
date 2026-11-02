# ELYNDRA — Site oficial

Site estático preparado para publicação no GitHub Pages.

## Beta Android
O botão **BAIXAR APK BETA** direciona para o Google Drive:
https://drive.google.com/file/d/11B2SXl9JrTf3bUPy-_uBEkByV8K-oKNi/view?usp=drivesdk

Confirme que o compartilhamento do arquivo no Drive permite que os testadores com o link o visualizem e baixem.

## Publicar/atualizar o site
1. Envie o conteúdo deste repositório para a branch `main`.
2. No GitHub, abra **Settings → Pages** e selecione **GitHub Actions** como fonte, se ainda não estiver configurado.
3. O workflow `.github/workflows/pages.yml` publica automaticamente o site a cada atualização na branch `main`.
4. Confira a aba **Actions** e abra o endereço publicado pelo GitHub Pages.

## Observações
- O contador regressivo original foi preservado e continua atualizando a cada segundo até 08/11/2026.
- A página identifica o APK como **beta para testadores**, não como versão final.
- O APK é hospedado no Google Drive, não dentro do repositório do site.
