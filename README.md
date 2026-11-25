# RayCleaner 5.0

<div align="center">

> Uma ferramenta de limpeza de sistema leve, minimalista e elegante para Windows, desenvolvida em Python com Flet.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Flet](https://img.shields.io/badge/Flet-UI-purple?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows&logoColor=white)

</div>

---

## Sobre o Projeto

O **RayCleaner 5.0** evolui o conceito original para oferecer uma interface ainda mais limpa, rápida e minimalista (**"Dark Soft"**) para realizar a manutenção básica e a remoção de arquivos temporários no Windows. Agora construído com **Flet**, o aplicativo apresenta um visual monocrômico moderno, janela compacta sem molduras (*frameless*) com dimensões fixas e execução assíncrona com logs em tempo real.

---

## Novidades da Versão 5.0

- **Novo Motor Gráfico (Flet):** Interface completamente refeita com visual monocrômico *Dark Soft* e bordas em destaque.
- **Janela Compacta e Frameless:** Sem barras de título nativas ou botões de fechamento padrão, mantendo dimensões fixas e não redimensionáveis para preservar a estética.
- **Feedback Visual & Logs em Tempo Real:** Animações suaves na seleção de opções, barra de progresso integrada e console de logs coloridos diretamente na tela.
- **Processamento Assíncrono (`asyncio`):** Limpeza fluida em segundo plano sem travar a interface.

---

## Funcionalidades

- **Limpeza de Pastas Temporárias do Sistema** (`C:\Windows\Temp`)
- **Temporários do Usuário** (`%TEMP%`)
- **Arquivos de Prefetch** (`C:\Windows\Prefetch`)
- **Histórico de Arquivos Recentes** do Windows
- **Esvaziamento Automático da Lixeira**
- **Seleção Rápida:** Botões dedicados para marcar ou desmarcar todas as opções de limpeza com um clique.

---

## Como Instalar e Executar

Você pode usar o aplicativo de duas formas: através do arquivo executável pronto ou pelo código-fonte.

### Opção 1: Executável Pronto (Recomendado)

1. Acesse a aba **Releases** no lado direito do repositório.
2. Baixe o arquivo `.exe` da versão mais recente do **RayCleaner 5.0**.
3. Clique com o botão direito sobre o arquivo baixado e selecione **Executar como Administrador** (necessário para limpar pastas do sistema como Temp e Prefetch).

---

### Opção 2: Executar via Código-Fonte (Desenvolvimento)

Caso prefira rodar o projeto diretamente pelo Python:

1. Certifique-se de ter o **Python 3.8+** instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone [https://github.com/RayO-builder/RayCleaner4000.git](https://github.com/RayO-builder/RayCleaner4000.git)
   cd RayCleaner4000
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install flet
   ```
4. Execute a aplicação (como Administrador no terminal):
   ```bash
   python interface.py
   ```

---

## Requisitos de Execução

- **Sistema Operacional:** Windows 10 ou 11.
- **Privilégios:** O aplicativo exige permissões de **Administrador** para conseguir limpar corretamente os diretórios protegidos do sistema (`Temp` e `Prefetch`).

---

## Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* com melhorias, correções de bugs ou novas ideias.
