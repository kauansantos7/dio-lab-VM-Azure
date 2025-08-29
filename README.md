# Computação em Nuvem: Microsoft Azure

## 1. Introdução

A computação em nuvem é um modelo de fornecimento de serviços de TI através da internet, permitindo que empresas e indivíduos utilizem recursos computacionais como servidores, armazenamento, bancos de dados, redes e softwares sem a necessidade de investir em infraestrutura física local. Esse modelo oferece flexibilidade, escalabilidade e custos proporcionais ao uso, sendo amplamente adotado em diversos setores.

A **Microsoft Azure** é uma plataforma de computação em nuvem da Microsoft, que fornece mais de 200 serviços integrados, incluindo máquinas virtuais, bancos de dados, inteligência artificial, redes e soluções de segurança. A Azure é amplamente reconhecida por sua confiabilidade, segurança e capacidade de suportar aplicações empresariais de grande escala.

---

## 2. Benefícios da Nuvem

Com base nas aulas do curso, destacam-se os seguintes benefícios ao utilizar serviços em nuvem como o Azure:

### 2.1 Escalabilidade e Elasticidade

A escalabilidade permite ajustar os recursos computacionais conforme a demanda. Na prática, isso significa que uma empresa pode aumentar ou reduzir a capacidade de suas máquinas virtuais (VMs), armazenamento ou bancos de dados de acordo com a necessidade, sem interrupções significativas.

**Exemplo prático:**  
Se um site ou aplicação está recebendo picos de acessos, é possível aumentar o número de CPUs de uma VM ou adicionar mais instâncias de servidor para manter a performance e atender a demanda de usuários sem falhas.

### 2.2 Confiabilidade, Previsibilidade e Segurança

O Azure oferece alta disponibilidade e confiabilidade através de backups automáticos, replicação de dados e zonas de disponibilidade distribuídas geograficamente. Isso garante que aplicações críticas continuem funcionando mesmo em caso de falhas de hardware ou interrupções regionais.

**Exemplo prático:**  
Para uma aplicação empresarial crítica, podemos configurar zonas de disponibilidade para VMs, assegurando que, caso uma zona falhe, outra assuma automaticamente, evitando perda de serviço.

### 2.3 Governança e Gerenciabilidade

A gestão de recursos em nuvem é facilitada por ferramentas de monitoramento, alertas, auditoria e políticas de governança. Isso permite controlar custos, definir regras de acesso e manter conformidade com normas corporativas e regulatórias.

**Exemplo prático:**  
A aplicação de políticas com o **Azure Policy** garante que apenas usuários autorizados possam criar certos tipos de recursos, evitando gastos desnecessários ou falhas de segurança.

### 2.4 Revisão Geral

Ao combinar escalabilidade, confiabilidade, segurança e governança, fica evidente que a computação em nuvem oferece às empresas uma solução robusta e eficiente, permitindo focar em inovação e crescimento, sem se preocupar com a manutenção física de servidores ou infraestrutura complexa.

---

## 3. Máquinas Virtuais

O lab envolveu a criação e configuração de uma VM no Azure, aplicando conceitos teóricos aprendidos durante o curso.

### 3.1 Criação da Máquina Virtual

1. Acesse o portal do Azure e selecione **Criar recurso > Computação > Máquina Virtual**.  
2. Escolha o sistema operacional: **Windows Server 2022** ou **Ubuntu 22.04**.  
3. Configure o tamanho da VM (CPU, memória e armazenamento) conforme a necessidade.  
4. Defina a rede, grupo de recursos e região da VM.

### 3.2 Teste de Escalabilidade

Após a criação, realizamos testes de escalabilidade:  
- Aumentamos a quantidade de CPUs e memória da VM para verificar se o desempenho da aplicação melhorava durante picos de carga.  
- Monitoramos o uso de recursos em tempo real pelo **Azure Monitor**.

### 3.3 Configurações de Segurança

Implementamos medidas básicas de segurança:  
- Configuração de firewall e regras de entrada e saída.  
- Criação de usuários e grupos com permissões específicas.  
- Configuração de backups automáticos e snapshots da VM.

---

## 4. Documentação do Processo

Durante o lab, documentamos cada etapa com capturas de tela e descrições detalhadas:

1. **Portal Azure**: imagens da criação da VM, configurações de rede e armazenamento.  
2. **Escalabilidade**: prints das alterações de CPU e memória, com resultados do monitoramento de desempenho.  
3. **Segurança**: exemplos de regras de firewall e políticas de acesso aplicadas.  
4. **Problemas e soluções**:  
   - **Problema:** lentidão ao aplicar alterações de CPU.  
   - **Solução:** reinicialização da VM após mudança de tamanho, conforme orientação do Azure.  

Esta documentação detalhada garante que o processo seja reproduzível e facilita o aprendizado.

---

## 5. Conclusão

O lab evidenciou diversos benefícios do uso de computação em nuvem e da plataforma Microsoft Azure:  
- **Escalabilidade**: recursos ajustáveis conforme demanda, sem necessidade de infraestrutura local.  
- **Confiabilidade**: alta disponibilidade e backups automáticos garantem continuidade do serviço.  
- **Segurança e Governança**: ferramentas de monitoramento e políticas de acesso aumentam a proteção e o controle sobre os recursos.  

Aprendemos a criar, configurar e gerenciar máquinas virtuais no Azure, aplicando conceitos teóricos de forma prática. Esse conhecimento permite que empresas possam inovar e crescer sem depender de infraestrutura física complexa, aproveitando a flexibilidade e eficiência da nuvem.

