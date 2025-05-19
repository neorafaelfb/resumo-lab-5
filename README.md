# Resumo: Computação e Redes no Microsoft Azure

Este repositório contém anotações e resumos sobre os principais conceitos abordados no uso de serviços de **computação** e **rede** na plataforma Microsoft Azure. Aqui você encontrará explicações diretas sobre os componentes fundamentais para trabalhar com máquinas virtuais, contêineres, serviços de aplicativo e redes na nuvem.

---

## ☁️ Serviços de Computação e Máquinas Virtuais do Azure

- As **Máquinas Virtuais (VMs)** são ambientes de computação completos e isolados hospedados na nuvem.
- Podem ser utilizadas para hospedar sistemas operacionais Windows ou Linux.
- Permitem escalabilidade vertical e horizontal, além de customização total de recursos como CPU, memória e disco.

---

## 🛡️ Conjuntos de Disponibilidade de Máquinas Virtuais do Azure

- **Conjuntos de Disponibilidade (Availability Sets)** garantem **alta disponibilidade** das VMs.
- São compostos por:
  - **Domínios de falha** (fault domains): evitam que VMs dependam do mesmo hardware físico.
  - **Domínios de atualização** (update domains): permitem atualizações sem indisponibilidade total.

---

## 💻 Área de Trabalho Virtual e Contêineres do Azure

- A **Área de Trabalho Virtual do Azure (Azure Virtual Desktop)** oferece acesso remoto a ambientes Windows completos.
- **Contêineres** são leves, rápidos de iniciar e compartilham o mesmo sistema operacional, isolando apenas os aplicativos.
- As **Instâncias de Contêiner do Azure (ACI)** são classificadas como **PaaS**, oferecendo uma forma simples de executar contêineres sem se preocupar com a infraestrutura.

---

## ⚙️ Azure Functions e Serviços de Aplicativo Azure

- O **Azure App Service** permite hospedar aplicações web, APIs REST e back-ends móveis.
- **Azure Functions** é um serviço de computação **serverless**, ideal para executar código sob demanda com escalabilidade automática.
- Ambos são modelos **PaaS**, fornecendo abstração da infraestrutura.

---

## 🌐 Computação e Rede – Revisão

- A **ExpressRoute** permite conexões privadas seguras entre o data center local e o Azure (sem passar pela internet pública).
- **Instâncias de Contêiner do Azure** são **PaaS**, enquanto VMs são **IaaS**.
- VMs são isoladas do hardware do host; contêineres compartilham o sistema operacional do host, mas também oferecem isolamento de processo.
- **Grupos de Recursos** podem conter recursos de **diferentes regiões**.
- **Zonas de Disponibilidade** oferecem **alta disponibilidade** com **replicação de baixa latência**.
- Uma **região do Azure** contém múltiplos data centers conectados por rede de baixa latência.

---

## ✅ Conceitos Importantes

- **Modelo de responsabilidade compartilhada**: Em IaaS, o cliente gerencia mais. Em PaaS e SaaS, o provedor assume mais responsabilidades.
- **PaaS** permite que usuários criem e implantem aplicativos sem gerenciar a infraestrutura.
- **IaaS** exige mais gerenciamento do cliente.
- **Nuvem Híbrida** oferece a maior flexibilidade, combinando pública e privada.

---

📌 **Referência prática:** este resumo pode ser utilizado para revisões rápidas e consultas durante projetos na plataforma Azure.

