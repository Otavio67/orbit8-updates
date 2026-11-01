# Orbit8 — downloads e atualizações

Canal público de distribuição da alpha do Orbit8. O código-fonte do projeto permanece em repositório privado.

[Baixar Orbit8 0.2.2 para Windows x64](https://github.com/Otavio67/orbit8-updates/releases/download/v0.2.2/orbit8-win-x64.zip)

Extraia o ZIP inteiro em uma pasta do seu usuário e execute Orbit8.exe. Requer Windows 10/11 e .NET Desktop Runtime 8. O componente WebView2 é verificado/preparado na primeira abertura. Há licenças de terceiros na pasta Licenses.

O navegador verifica o manifesto público update.json com uma chave fixa e compara os arquivos por SHA-256. O botão de atualização aparece quando existe uma versão superior; instalar exige um clique e salva/reabre as abas. A versão inicial precisa ser aberta manualmente uma vez. As versões alpha ficam marcadas como pré-lançamento.

Alpha experimental: sem auditoria de segurança para credenciais sensíveis, sem sincronização de contas e sem respostas internas de IA. Bloqueio por domínio não remove todos os anúncios. Pacotes assinados pelo Orbit8 não significam certificado Windows/SmartScreen. O .NET 8 encerra suporte em 10/11/2026; migração para uma versão LTS atual está pendente e será necessária para continuidade do canal.