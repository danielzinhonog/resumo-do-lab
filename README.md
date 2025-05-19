#Resumo do Lab - Introdução à Computação em Nuvem e Microsoft Azure

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento dos labs na DIO, com foco em **computação em nuvem** e na **criação de uma máquina virtual no Microsoft Azure**.

---

##Introdução à Computação em Nuvem

###O que é Computação em Nuvem?
Entrega de serviços de TI via internet, com escalabilidade, inovação rápida e redução de custos. Permite uso sob demanda sem precisar de infraestrutura própria.

---

##Modelos de Nuvem

###Nuvem Privada
- Exclusiva de uma organização
- Controle total de segurança e manutenção
- Ideal para empresas com alta exigência de conformidade

###Nuvem Pública
- Fornecida por provedores como Azure, AWS, Google Cloud
- Compartilhada, escalável e com pagamento sob demanda
- Elimina custos iniciais com hardware

###Nuvem Híbrida
- Combina pública e privada
- Flexível, com maior controle e conformidade legal

---

##Modelos de Serviço em Nuvem

###IaaS (Infraestrutura como Serviço)
- Aluguel de servidores, VMs, redes e armazenamento sob demanda
- Maior flexibilidade e controle sobre o ambiente
- Você gerencia o sistema operacional e o software instalado

###PaaS (Plataforma como Serviço)
- Ambiente gerenciado para desenvolvimento e implantação de aplicativos
- Foco total no código, sem se preocupar com a infraestrutura
- Infraestrutura e plataforma gerenciadas pelo provedor

###SaaS (Software como Serviço)
- Acesso direto a aplicativos via internet (ex: Office 365, e-mail)
- Modelo por assinatura: pague conforme o uso
- Sem necessidade de instalação ou manutenção

---

##Modelos de Custo

###CapEx (Despesas de Capital)
- Investimento inicial em hardware
- Valor se deprecia com o tempo

###OpEx (Despesas Operacionais)
- Pagamento conforme o uso dos serviços
- Mais ágil e escalável financeiramente

###Modelo Baseado em Consumo
- "Pay-as-you-go": paga apenas pelo que usar
- Maior previsibilidade e controle de custos

---

##Estrutura Regional e Organizacional do Azure

###Regiões do Microsoft Azure
- Mais de 60 regiões globais cobrindo 140 países
- Cada região contém um ou mais datacenters próximos
- Oferecem baixa latência e conformidade de residência dos dados

###Zonas de Disponibilidade
- Isolamento físico de datacenters dentro da mesma região
- Equipados com energia, resfriamento e rede independentes
- Interconectados por redes de fibra óptica privadas

###Pares de Regiões
- Separados por pelo menos 300 milhas
- Permitem replicação automática para certos serviços
- Garantem recuperação prioritária em caso de falhas

###Regiões Soberanas do Azure

####Azure Governamental (EUA)
- Para agências federais e órgãos públicos
- Infraestrutura isolada e com acesso restrito

####Azure China
- Em conformidade com as leis locais
- Operado pela 21Vianet, isolado dos outros serviços globais
- Todos os dados permanecem dentro da China

---

##Organização de Recursos no Azure

###Recursos do Azure
- Componentes como VMs, redes e armazenamento
- Usados para construir soluções na nuvem

###Grupos de Recursos
- Contêineres que agrupam recursos relacionados
- Um recurso pertence a apenas um grupo por vez
- Recursos podem estar em diferentes regiões
- É possível mover recursos entre grupos

###Assinaturas do Azure
- Acesso autenticado e autorizado aos recursos
- Controle de cobrança e acesso por assinatura
- Permite gerar faturas e relatórios individualizados

###Grupos de Gerenciamento
- Agrupam várias assinaturas do Azure
- Permitem aplicar políticas e controles em larga escala
- As assinaturas herdam as configurações definidas no grupo

---

##Desafio: Criando e Configurando uma VM no Azure

Durante o laboratório, aprendi a criar e configurar uma **máquina virtual** no Microsoft Azure. Aqui estão os principais conceitos aplicados:

---

##Benefícios da Nuvem

###Alta Disponibilidade
Serviços continuam operando mesmo com falhas técnicas.

###Escalabilidade
Ajuste de recursos conforme a demanda, com escala vertical (CPU/RAM) e economia.

###Elasticidade
Adição ou remoção automática de recursos em picos ou quedas de uso.

###Confiabilidade
Infraestrutura global descentralizada garante alta resiliência.

###Previsibilidade
Custo e desempenho previsíveis com base em boas práticas do Azure.

###Segurança
Ferramentas robustas para proteger dados e sistemas:
- **IaaS**: mais controle, maior responsabilidade
- **PaaS/SaaS**: menos controle, manutenção automatizada

###Governança
Monitoramento de conformidade, automação de atualizações e organização.

###Gerenciabilidade
Gerenciamento via:
- Portal Web
- CLI
- APIs
- PowerShell  
- Implantação rápida e escalável com modelos prontos.

---

##Conclusão

A criação de uma máquina virtual no Azure reforçou meu entendimento sobre **gestão de recursos, elasticidade, segurança, governança e estrutura organizacional em nuvem**. Este repositório será uma base de apoio para futuras implementações na plataforma Microsoft Azure.

---

> Feito por Daniel • Desafio da [DIO.me](https://www.dio.me)
