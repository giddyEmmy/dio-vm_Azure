# dio-vm_Azure

## 1. Acesso ao Portal do Azure  
Efetue login no [Portal do Azure](https://portal.azure.com/), ambiente no qual será realizado o gerenciamento de todos os recursos da sua assinatura.  

## 2. Início da Criação da Máquina Virtual  
No painel principal, utilize a barra de pesquisa para localizar **“Máquinas Virtuais” (Virtual Machines)**. Em seguida, selecione a opção **“Criar”** para iniciar o processo de configuração.  

## 3. Definição dos Detalhes Básicos  
- **Nome da Máquina Virtual:** Defina uma nomenclatura clara e de fácil identificação.  
- **Região:** Escolha a região de hospedagem, preferencialmente a mais próxima de seus usuários ou do local de operação.  
- **Imagem:** Selecione o sistema operacional desejado (ex.: Windows ou Linux).  
- **Tamanho:** Determine o tamanho da VM de acordo com os requisitos de processamento, memória e armazenamento.  

## 4. Configuração de Rede  
- **Rede Virtual:** Crie uma nova rede virtual ou utilize uma já existente.  
- **Sub-rede:** Especifique a sub-rede em que a máquina será alocada.  
- **Grupo de Segurança de Rede (NSG):** Configure as regras de firewall necessárias para controlar o tráfego de entrada e saída.  

## 5. Definição de Credenciais de Acesso  
Configure o **nome de usuário** e a **senha** que serão utilizados para autenticação.  
> **Recomendação:** utilize uma senha forte e segura.  

## 6. Revisão e Criação  
Revise todas as configurações definidas, garantindo que estejam de acordo com os requisitos. Após a validação, clique em **“Criar”** e aguarde o provisionamento automático da máquina virtual.  

## 7. Conexão à Máquina Virtual  
Após a conclusão do provisionamento:  
- Para máquinas virtuais **Windows**, utilize o **Remote Desktop Protocol (RDP)**.  
- Para máquinas virtuais **Linux**, utilize acesso via **SSH**.
