# 💻 Laboratório: Criação e Configuração de Máquinas Virtuais no Microsoft Azure

Este repositório é o resultado de um laboratório prático realizado na plataforma **Microsoft Azure**, com o objetivo de aprender, praticar e documentar o processo de criação e configuração de **máquinas virtuais (VMs)**.

---

## 🎯 Objetivo

- Criar uma máquina virtual (VM) no Azure.
- Configurar o sistema operacional, regras de acesso e monitoramento.
- Documentar o processo com resumos, dicas e anotações.
- Construir um material de apoio para revisões futuras e compartilhamento de conhecimento.

---

## 📘 Conteúdo do Repositório

| Arquivo | Descrição |
|--------|-----------|
| `notas/criacao-vm.md` | Passo a passo completo da criação de uma VM |
| `notas/configuracoes-iniciais.md` | Primeiras configurações após o provisionamento |
| `notas/dicas-uso-vm.md` | Dicas práticas de uso, conexão e manutenção |
| `notas/comandos-uteis.md` | Comandos PowerShell/Linux mais utilizados |
| `docs/arquitetura.png` | (Opcional) Diagrama da arquitetura criada |

---

## 🧰 Tecnologias e Serviços Utilizados

- **Microsoft Azure**
- **Máquina Virtual (Windows/Linux)**
- **Azure Resource Group**
- **Azure Network Interface / IP Público**
- **Azure Bastion ou RDP/SSH**
- **PowerShell ou Azure CLI (opcional)**

---

## 📝 Resumo do Processo

1. **Acesse o Portal Azure**  
   [https://portal.azure.com](https://portal.azure.com)

2. **Crie um novo recurso → Máquina Virtual**

3. **Defina as configurações principais:**
   - Nome da VM
   - Região
   - Imagem do SO (ex: Ubuntu, Windows Server)
   - Tamanho (B1s, Standard_D2s, etc)
   - Usuário e senha/chave SSH

4. **Configure as redes:**
   - Grupo de recursos
   - Sub-rede
   - IP público
   - Regras de segurança (porta 22 ou 3389, etc)

5. **Crie e inicie a VM**

6. **Conecte-se à VM via SSH ou RDP**

7. **Execute as configurações pós-criação e atualizações**

---

## 📸 Exemplo de Interface

*Prints das telas da VM ou do portal Azure podem ser adicionados em `imagens/` para facilitar a compreensão.*

---

## 💡 Dicas Rápidas

- Utilize a **Azure CLI** para automações futuras.
- Cuidado com os custos! Use as **opções gratuitas** ou desligue a VM quando não estiver em uso.
- Acesse o Azure Learn para conteúdo oficial gratuito:  
  [https://learn.microsoft.com/pt-br/training/](https://learn.microsoft.com/pt-br/training/)

---

## 🔒 Segurança

- Nunca exponha sua VM diretamente à internet sem firewalls ou regras específicas.
- Prefira o uso de **chaves SSH** ao invés de senhas.
- Monitore o uso e configure alertas no portal Azure.
