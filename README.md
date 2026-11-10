# Convite de Elizeu Bonfim & Danielle

Casamento: **18/12/2026 às 20h**, Cerimônia no Templo do Vale do Amanhecer. Recepção no Antigo Orfanato.

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub (por exemplo `convite-elizeu-danielle`).
2. Envie `index.html`, `presentes.html`, `style.css`, `config.js`, `presentes.js`, a pasta `assets/` e `apps-script/`.
3. Em **Settings > Pages**, selecione **Deploy from a branch**, `main`, `/ (root)`.
4. Acesse `https://SEU-USUARIO.github.io/convite-elizeu-danielle/`.

## Conectar Google Planilhas
1. Crie uma planilha Google exclusiva para o casamento.
2. Abra **Extensões > Apps Script** e cole o conteúdo de `apps-script/Code.gs`.
3. Execute a função `setup()` **uma única vez** (ela recria a aba Presentes e apaga seu conteúdo anterior). Autorize a execução.
4. Em **Implantar > Nova implantação > Aplicativo da Web**, execute como **você** e permita acesso a **qualquer pessoa** para que os convidados possam reservar sem conta Google. Copie a URL terminada em `/exec`.
5. Cole a URL em `appsScriptUrl` no arquivo `config.js` e envie a alteração ao GitHub.
6. Edite os presentes diretamente na aba `Presentes`. Colunas: ID, Nome, Tipo (`fisico` ou `pix`), Valor, URL, Imagem, Disponivel, ReservadoEm, CodigoReserva.
7. Faça um teste com dois navegadores tentando reservar o mesmo presente. Somente um deverá conseguir.

**Atenção:** a lista é pública e a reserva é anônima. Não armazene nomes, telefones ou dados privados na planilha. A chave Pix é pública na página, confirme se o titular está correto antes de divulgar. O endpoint público permite reservas sem login, portanto pode sofrer reservas indevidas; monitore a planilha. O site não verifica pagamento Pix. Links externos devem começar por `https://`.

## Ajustes antes do envio
- O botão Google Maps aponta para o Templo Mãe do Vale do Amanhecer, conforme o link fornecido. A recepção no Antigo Orfanato não possui link próprio neste projeto.
- Verifique se a chave Pix `61974023450` pertence ao destinatário correto.
- Substitua os presentes demonstrativos pelos presentes reais.
- Teste em celulares e valide a implantação do Apps Script.
- A imagem floral foi recortada da referência fornecida, apenas para composição decorativa.


## Correção visual v6
O fundo floral está em `assets/moldura-floral-sem-texto.webp`: apenas rosas nos cantos, moldura dourada e centro livre para texto HTML. Removidas imagens anteriores que continham inscrições.
