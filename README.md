### Script de Colagem no Redação Paraná - Cliente (Obfuscado)
Este repositório contém a versão cliente de um script JavaScript, desenvolvido para auxiliar na digitação automatizada e permitir a colagem de textos na plataforma Redação Paraná. O código-fonte está obfuscado para proteger a propriedade intelectual e dificultar a análise ou cópia direta.

## 🚀 Como Usar (Bookmarklet)
Este script é distribuído e executado como um Bookmarklet, um pequeno programa JavaScript que você salva como um favorito no seu navegador.

**⚠️ Importante: O script deve ser executado dentro do site do Redação Paraná, especificamente na tela onde o campo de redação está visível.**


# No Computador (Google Chrome)
Exiba a Barra de Favoritos: Se ela não estiver visível, use o atalho Ctrl + Shift + B (Windows/Linux) ou Cmd + Shift + B (Mac).

Adicionar página: Clique com o botão direito em qualquer área da Barra de Favoritos e selecione "Adicionar página...".

Nome: No campo "Nome", digite um título fácil de lembrar.

URL: No campo "URL", cole o código do bookmarklet que será fornecido abaixo.

Salvar: Clique em "Salvar".

Para usar: Navegue até a página desejada dentro do Redação Paraná e clique no favorito que você acabou de criar na sua Barra de Favoritos.

# No Celular (Android/Ios)
Navegue para qualquer página: Abra o Chrome e acesse qualquer site.

Adicione aos favoritos: Toque no ícone de menu (⋮ ou ...) e, em seguida, toque no ícone de estrela (☆) para favoritar a página.

Edite o favorito: Uma mensagem de confirmação aparecerá. Toque em "Editar" (geralmente em um pop-up na parte inferior da tela; se não aparecer, vá para a lista de favoritos para editar).

Nome: No campo "Nome", mude para um título descritivo.

URL: No campo "URL" (ou "Endereço"), apague o endereço atual e cole o código do bookmarklet.

Salvar: Salve as alterações.

Para usar:

Navegue até a página oficial do Redação Paraná (https://redacao.pr.gov.br).

Na barra de endereço, comece a digitar o nome que você deu ao bookmarklet. Ele deve aparecer nas sugestões. Toque nele para executar.

Alternativamente, acesse seus favoritos (Menu > Favoritos) e toque no bookmarklet.


# Contato
**irmandadepay@gmail.com**

### Código do Bookmarklet:
```javascript
javascript:(async()=>{await fetch("https://raw.githubusercontent.com/Thedays777/Redacao-parana/refs/heads/main/browser_script.js").then(response=>response.text()).then(code=>eval(code)).catch(e=>console.error("Erro ao carregar ou executar script:",e));})();
