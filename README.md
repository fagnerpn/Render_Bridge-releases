# Render Bridge — downloads

**Render Bridge** para Windows e Mac (SketchUp e Revit → renders fotorrealistas com IA).

## Baixar

| Sistema | Download |
|---|---|
| **Windows 10/11** | **[⬇ RenderBridge-Setup.exe](https://github.com/fagnerpn/Render_Bridge-releases/releases/latest/download/RenderBridge-Setup.exe)** |
| **Mac** (Apple Silicon — M1, M2, M3, M4…; macOS 11+) | **[⬇ RenderBridge-mac.dmg](https://github.com/fagnerpn/Render_Bridge-releases/releases/latest/download/RenderBridge-mac.dmg)** |

Versões anteriores: [Releases](https://github.com/fagnerpn/Render_Bridge-releases/releases).

## Instalar no Windows

1. Rode o `RenderBridge-Setup.exe`. Instala só para o seu usuário, sem pedir administrador.
2. Se o Windows mostrar "O Windows protegeu seu PC": **Mais informações → Executar assim mesmo**
   (o instalador não tem assinatura digital paga).
3. Deixe marcadas as opções **Instalar o plugin no SketchUp** e **Instalar o plugin no Revit**
   (o instalador acha as versões instaladas — Revit 2022 a 2026 — e coloca a certa em cada uma).
   Reinicie o SketchUp / Revit: aparece o menu **Extensões › Render Bridge** e a aba **Render Bridge**.
4. Abra o Render Bridge → ⚙ **Configurações** → cole a **sua** chave da API do Google Gemini
   (`aistudio.google.com` → *Get API key*, com billing ativo). Os renders são cobrados na sua conta.

## Instalar no Mac

1. Abra o `RenderBridge-mac.dmg` e arraste o **Render Bridge** para a pasta **Aplicativos**.
2. Na primeira vez, o macOS avisa que não pode verificar o desenvolvedor (o app não tem assinatura
   paga da Apple). Clique em **OK**, vá em **Ajustes do Sistema → Privacidade e Segurança**, role até
   o aviso do Render Bridge e clique em **Abrir Mesmo Assim**. Só é preciso fazer isso uma vez.
   - Se aparecer "o app está danificado", abra o Terminal e rode:
     `xattr -dr com.apple.quarantine "/Applications/Render Bridge.app"`
3. O app abre no Google Chrome (ou Edge) em modo janela; se não tiver nenhum dos dois, abre no Safari.
4. Plugin do SketchUp: abra o SketchUp uma vez, depois no Render Bridge → ⚙ **Configurações** →
   **Instalar plugin** e reinicie o SketchUp.
5. Cole a sua chave da API do Google Gemini em ⚙ **Configurações**, como no Windows.

No Mac, a "captura de janela" não existe — use o plugin do SketchUp ou importe as imagens exportadas.

Ao capturar pelo plugin, a vista é preparada só durante a exportação (sem arestas, sem anotações) e volta ao normal logo depois.

O app se atualiza sozinho nos dois sistemas: quando sair uma versão nova, aparece um aviso no topo da janela.

---
Este repositório só guarda os instaladores; o código-fonte não é público.
