---
title: KIRE CUT — Política de privacidade
---

# Política de privacidade do KIRE CUT

Última atualização: 25 de novembro de 2026.

O KIRE CUT é desenvolvido por elifrigeridev.

O KIRE CUT é um editor de vídeo para Windows. Esta página explica, em linguagem simples, o que acontece
com os seus dados quando você usa o app.

## Resumo

- **Não coletamos nenhum dado seu.** O app não tem cadastro, não tem anúncios e não envia estatísticas de uso
  nem relatórios de erro para nós.
- **Seus vídeos, músicas e imagens ficam no seu computador.** Todo o processamento (cortes, prévias, limpeza
  do som, exportação) é feito no próprio computador.
- **A única coisa que sai do computador é o pedido à IA**, e só se você ativar a IA com a sua própria chave e
  fizer um pedido. Ele vai direto do seu computador para a Anthropic (a empresa do Claude), não para nós.

## O que fica no seu computador

- Os seus arquivos de mídia e os projetos que você salva, nas pastas que você escolher.
- Arquivos temporários do app (prévias, formas de onda, som limpo, salvamento automático do projeto) e as
  configurações (estilos de texto, projetos recentes, modelo da IA, cotação do dólar, arrumação da tela),
  na pasta de dados do app no Windows. Desinstalar o app apaga essa pasta.
- A chave da API da IA, guardada no **Gerenciador de Credenciais do Windows**. Ela só é usada para falar com
  a Anthropic e nunca é enviada para nós.

## Assistente de IA (opcional)

O app funciona por completo sem a IA. Se você colar a sua chave da Anthropic nas Configurações e fizer um
pedido na barra da IA, o app envia para a Anthropic (api.anthropic.com):

- o texto do seu pedido e os últimos pedidos da mesma sessão;
- um resumo do projeto: nome do projeto, nomes dos arquivos usados (sem as pastas), posição e duração dos
  clipes na linha do tempo, o começo dos textos que você colocou no vídeo e ajustes de volume;
- números da análise de áudio feita no seu computador (andamento/BPM, batidas, partes mais altas e mais
  baixas).

**Não são enviados:** os arquivos de vídeo, áudio ou imagem, as pastas onde eles estão, nem qualquer outro
dado do seu computador.

A Anthropic trata esses dados conforme os termos e a política de privacidade dela, que você aceitou ao criar
a sua chave: <https://www.anthropic.com/legal/privacy>. O custo de cada pedido é cobrado pela Anthropic na
sua conta. A cotação do dólar mostrada no app é digitada por você; o app não a busca na internet.

## Microsoft Store e Windows

O app é distribuído e atualizado pela Microsoft Store. A Microsoft pode coletar dados sobre instalação,
atualizações e funcionamento do Windows conforme a política de privacidade dela:
<https://privacy.microsoft.com/pt-br/privacystatement>. Nós não recebemos esses dados.

## Seus direitos

Como não coletamos dados pessoais, não guardamos nada sobre você que possa ser consultado, corrigido ou
apagado. Para apagar o que o app guarda no seu computador, desinstale o app (ou apague os seus projetos).
A chave da IA não é apagada ao desinstalar: antes, use o botão **Apagar** ao lado da chave, nas
Configurações do app (ou apague-a no Gerenciador de Credenciais do Windows).

## Crianças

O app não coleta dados de ninguém, incluindo crianças. O uso da IA exige uma conta na Anthropic, que tem as
próprias regras de idade.

## Mudanças nesta política

Se esta política mudar, a data no topo desta página será atualizada.

## Contato

Dúvidas sobre esta política: **elifrigeridev@protonmail.com**.
