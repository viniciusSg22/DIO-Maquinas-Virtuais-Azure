# DIO-Maquinas-Virtuais-Azure


# Guia de Criação de Máquinas Virtuais no Azure

Este documento fornece um resumo sobre o uso do Azure para criar e gerenciar **Máquinas Virtuais (VMs)** por meio do **Portal do Azure** e artigos relevantes no **Microsoft Learn**.

## 1. Introdução
O Azure é uma plataforma de nuvem da Microsoft que oferece uma ampla gama de serviços de computação, incluindo a criação de Máquinas Virtuais (VMs) para executar aplicativos, sistemas operacionais e serviços na nuvem. As VMs permitem que você crie e gerencie servidores virtuais de maneira eficiente, escalável e com segurança.

## 2. Criando uma Máquina Virtual através do Portal do Azure

### Passos para criação de uma VM no portal:
1. **Acesse o Portal do Azure:**
   - Abra o portal [portal.azure.com](https://portal.azure.com/).
   - Faça login com sua conta do Azure.
   
2. **Crie um novo recurso:**
   - No painel do portal, clique em **"Criar um recurso"**.
   - Selecione **"Máquina Virtual"**.

3. **Configuração da máquina virtual:**
   - Escolha uma **assinatura** e **grupo de recursos**.
   - Defina um nome para a VM.
   - Selecione a **região** onde deseja hospedar a VM.
   - Escolha a **imagem do sistema operacional** desejada (Windows, Linux, etc.).
   - Selecione o **tamanho da VM**, com base nos requisitos de CPU, memória e armazenamento.
   
4. **Configurações de rede e segurança:**
   - Configure a rede e o **endereço IP** da VM.
   - Defina regras de **firewall** para acesso à VM.
   
5. **Criação e inicialização:**
   - Revise suas configurações.
   - Clique em **"Criar"** para iniciar a implantação da máquina virtual.

Após a criação, você pode acessar a VM através de **Remote Desktop (RDP)** para Windows ou **SSH** para Linux.

## 3. Artigos do Microsoft Learn sobre Máquinas Virtuais no Azure

- **Artigo: [Introdução às Máquinas Virtuais no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)**:
  Este artigo fornece uma visão geral sobre o que são as VMs no Azure, como funcionam e como você pode usar as VMs para hospedar seus aplicativos e sistemas.

- **Artigo: [Configuração e gerenciamento de VMs no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/manage-virtual-machines)**:
  Este tutorial ensina como configurar, gerenciar e monitorar suas máquinas virtuais no Azure.

- **Artigo: [Escalabilidade e Disponibilidade de Máquinas Virtuais](https://learn.microsoft.com/pt-br/azure/virtual-machines/scaling-availability)**:
  Aprenda como configurar e escalar suas VMs para lidar com aumentos de tráfego e garantir alta disponibilidade.

## 4. Benefícios das Máquinas Virtuais no Azure

- **Escalabilidade**: É possível ajustar facilmente o tamanho da VM conforme necessário para atender à demanda de processamento e memória.
- **Segurança**: O Azure fornece recursos avançados de segurança, incluindo firewalls e controles de acesso baseados em função (RBAC).
- **Alta Disponibilidade**: Com recursos como **escala automática** e **zona de disponibilidade**, é possível garantir que suas VMs permaneçam operacionais, mesmo em caso de falhas.
- **Gerenciamento fácil**: Com ferramentas como **Azure Monitor** e **Azure Automation**, o gerenciamento das VMs fica mais simples e eficaz.

## 5. Conclusão

O Azure é uma plataforma robusta e flexível para criação e gerenciamento de **máquinas virtuais**. Com a interface intuitiva do portal e os artigos de aprendizado do **Microsoft Learn**, é fácil começar a trabalhar com VMs, desde a criação até o gerenciamento avançado.

Para mais informações, explore os recursos do **Microsoft Learn** e continue aprendendo sobre o Azure.
