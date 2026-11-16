TerraMap Converter V2 - versão de testes

COMO PUBLICAR
1. Extraia este ZIP.
2. Envie o arquivo index.html para a raiz do repositório GitHub Pages.
3. Aguarde a publicação e abra o site.

MELHORIAS DESTA VERSÃO
- Processamento dos DDS um por vez.
- Liberação de referências temporárias e redução do tamanho do canvas após cada conversão.
- Pausas curtas para o navegador atualizar a interface durante o processamento.
- Limite de segurança para texturas extremamente grandes.
- Progresso e mensagens mais detalhadas.
- Reconstrução do ZIP com streamFiles ativado.

LIMITAÇÕES IMPORTANTES
- O processamento continua sendo feito no navegador com JSZip.
- O ZIP de entrada e a saída ainda podem exigir bastante memória.
- Não há garantia para mapas de 2 GB ou para todos os formatos DDS/DX10.
- A biblioteca DDS externa precisa carregar pela internet.
- Teste primeiro com uma cópia do mapa e mantenha "Manter DDS original" marcado.
- A conversão usa a primeira imagem/mipmap retornada pelo decodificador. Múltiplos mipmaps, cubemaps e formatos não reconhecidos podem não ser convertidos corretamente.
- Esta versão ainda precisa ser testada com o mapa que travou nos 152 DDS.
