# Sistema de Doação de Sangue

- Este programa foi desenvolvido utilizando SWI-Prolog para gerenciar um sistema especialista de doação de sangue. Ele permite realizar consultas, verificações e operações relacionadas aos doadores, receptores e à compatibilidade de tipos sanguíneos.

# Funcionalidades

O programa possui as seguintes funcionalidades:

- **Cadastro de doadores e receptores:** registrar pessoas com suas informações básicas, como seu nome, tipo sanguíneo e peso.
- **Verificação da compatibilidade:** verifica se um doador e receptor são compatíveis.
- **Regras de compatibilidade sanguínea:** Essa regra se baseia nos padrões universais de transfusão.

# Estrutura do Arquivo

Sua estrutura contém:

- Um arquivo **.pl** contendo a implementação em Prolog, que define as regras de compatibilidade e as operações de consulta..

# Requisitos

Para executar o programa, são necessários os seguintes componentes:

**SWI-Prolog:** 
- Baixar e instalar a versão mais recente do SWI-Prolog.
- Certifique-se de que o Prolog está no PATH do sistema.

**Python 3.x:**
- Instalar o Python.

**wxPython:** 
- Instalar a biblioteca wxPython com o seguinte comando:
**pip install wxpython**

# Como executar o programa:

1. Verificar a localização do arquivo SistemaDeDoacao no seu dispositivo.

2. Abrir o terminal e executar o programa com o seguinte comando:
**python sistemaDoacaoDeSangue.py**
Ou
**py sistemaDoacaoDeSangue.py**

3. **Interagir com o programa:**
- Utilizar a interface para registrar doadores e receptores.
- Verifique compatibilidades de doação.
- Explorar outras funcionalidades disponíveis.

# Estrutura do Projeto
- **sistemaDoacaoDeSangue.py:** Arquivo principal que contém a implementação do sistema com interface gráfica e consultas Prolog.
- **sistema_doacao.pl:** Arquivo de regras em Prolog que define a compatibilidade sanguínea e outros dados.
