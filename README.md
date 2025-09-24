# HeliosSecureScannerScript

**Versão:** 1.0.0  
**E-mail:** devhansoft@gmail.com  
**Licença:** [MIT]

---

## Sobre o Projeto

O **Helios Secure Scanner Script** é uma ferramenta gratuita desenvolvida para **análise e detecção de scripts potencialmente maliciosos**, como:

- Arquivos em lote (.BAT, .CMD)  
- Scripts PowerShell (.PS1)  
- Scripts Visual Basic (.VBS)  
- Executáveis (.EXE)  
- Atalhos do Windows (.LNK)  

O objetivo principal é ajudar **analistas forenses**, **profissionais de segurança da informação** e **usuários avançados** a **identificar ameaças de forma rápida, segura e local**.

Todos os arquivos analisados permanecem **exclusivamente no dispositivo do usuário**, garantindo **privacidade total** durante todo o processo.

---

## Funcionalidades Principais

### 1. Análise Local e Segura
- Não coleta ou envia dados do usuário.  
- Todo o processamento ocorre diretamente na máquina analisada.

### 2. Detecção de Padrões Suspeitos
- Identifica **comandos perigosos** em scripts.

### 3. Classificação de Ameaças
O software detecta cinco grandes categorias de comportamento malicioso:

- Exclusão e destruição de arquivos  
- Downloads e execução de cargas remotas  
- Persistência (agendamento, registro, inicialização)  
- Comunicação em rede e controle remoto  
- Criação de usuários ou elevação de privilégios  

### 4. Padrões Pré-Configurados
O programa conta com mais de **30 assinaturas pré-definidas**, incluindo:

- `del /f /q`  
- `Invoke-WebRequest`  
- `frombase64string`  
- `Start-Process`  
- `schtasks`  
- `net user`

### 5. Resultados Detalhados
- Exibe **relatórios em texto simples**.  
- Informa **qual padrão foi detectado** e **em qual linha do script** ele aparece.

---

## Requisitos do Sistema

- **Sistema Operacional:** Windows 7 ou superior  
- **Python:** Versão 3.9 ou superior  

**Bibliotecas Python necessárias:**
- Tkinter (interface gráfica)  
- hashlib  
- base64  
- os  
- sys  
- datetime  

> Obs.: Todas as bibliotecas listadas já fazem parte da **instalação padrão do Python**, não sendo necessário instalar pacotes adicionais.

---

## Segurança e Privacidade

- O programa é **100% offline**, garantindo que nenhum dado seja enviado pela internet.  
- **Nenhuma conta ou cadastro** é necessário para uso.  
- Ideal para **ambientes corporativos** e **investigações sigilosas**.

Consulte a **Política de Privacidade completa** no arquivo:  
[PRIVACY_POLICY.txt](PRIVACY_POLICY.txt)

---

## Licenças

Este projeto está licenciado sob a **Licença MIT**.  
Consulte o arquivo [LICENSE.txt](LICENSE.txt) para mais detalhes.

O programa também utiliza componentes de terceiros incluídos no Python.  
Mais informações no arquivo [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

---

## Aviso Legal

O **Helios Secure Scanner Script** é fornecido **gratuitamente** e **"no estado em que se encontra"** (*"AS IS"*), **sem garantias de qualquer tipo**.  

O desenvolvedor **não se responsabiliza** por danos, perdas de dados ou quaisquer outros problemas decorrentes do uso deste software.

---

## Contato e Suporte

Dúvidas, sugestões ou relatórios de bugs podem ser enviados para:  
**E-mail:** devhansoft@gmail.com

Obrigado por utilizar o **Helios Secure Scanner Script**!
