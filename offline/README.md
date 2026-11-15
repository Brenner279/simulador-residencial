# Versão offline — Simulador Residencial: Gestão de Energia

Esta pasta contém uma versão autocontida do simulador. A interface, os desenhos, as animações, os cálculos e os efeitos sonoros funcionam sem bibliotecas, fontes ou imagens externas.

## Usar no Chromebook sem internet

1. Baixe o repositório como ZIP pelo botão **Code → Download ZIP**.
2. No aplicativo **Arquivos** do Chromebook, abra **Downloads** e extraia o ZIP.
3. Entre na pasta extraída, abra `offline` e clique em `index.html`.
4. Escolha abrir com o Chrome. O simulador funcionará localmente, mesmo sem Wi-Fi.
5. Para facilitar o acesso, com a página aberta, use o menu do Chrome e escolha **Salvar e compartilhar → Criar atalho** (o nome do menu pode variar conforme a versão do ChromeOS).

## Instalar como aplicativo pelo GitHub Pages

Acesse `https://brenner279.github.io/simulador-residencial/offline/` enquanto estiver conectado à internet. Use a opção **Instalar página como app** ou **Instalar** do Chrome. Na primeira abertura, o aplicativo registra o service worker e armazena os arquivos necessários. Depois da instalação e do primeiro carregamento concluído, ele pode ser aberto sem conexão.

## Observações

- A abertura local de `index.html` não depende do service worker: todos os estilos e scripts já estão dentro do próprio arquivo.
- O service worker é usado apenas quando o app é servido por HTTPS (GitHub Pages) ou localhost.
- Os valores são estimativas didáticas baseadas nas potências, horas de uso e tarifa informadas. A simulação não mede o consumo real da residência nem substitui a conta da concessionária.
