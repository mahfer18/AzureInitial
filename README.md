# Azure 

Esse é um overview sobre Microsoft Azure

Inicio dos estudos do bootcamp Microsoft Azure Essentials.



MICROSOFT AZURE

A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.


Nuvem pública
Nenhuma despesa de capital para escalar verticalmente (CapEx)
Quando cria um servidor na nuvem, paga somente pelo que utiliza
Aplicativos e serviços podem ser provisionados ou desligados rapidamente (cria uma máquina e rapidamente pode ser excluída.

Nuvem Privada (on-premisses)
Controle total sobre recursos e segurança (por conta da organização)
Responsabilidade pela atualização e manutenção de hardware

Nuvem Híbrida(melhor dos dois mundos)
Organizações determinam onde executar aplicativos
Controle de segurança, conformidade e requisitos legais.
Maior flexibilidade

CapEx:
Gasto inicial em infraestrutura física
As despesas do CapEx têm um valor que se reduz com o tempo

OpEx:
Gasto produtos/serviços conforme necessário, pagamento conforme o uso.
Seja cobrado imediatamente



# Benefícios

* Alta disponibilidade

Garantia de disponibilidade máxima, independente de interrupções ou eventos que possam ocorrer. 
Porém sempre lembrar do SLA (Service Level Agreement) nível de serviço acordado, é o que está em contrato não há garantia de 100%, mas sempre 99% - 99,5% - 99,9% essa diferença para 100% é convertido em horas de indisponibilidade contratual.
Ultrapassando as ‘horas’ de indisponibilidade (caso haja) é convertido em horas e fica disponível para o cliente como crédito (voucher).

* Escalabilidade
É a capacidade de ajustar recursos para atender a demanda, adicionar mais recursos para lidar com o aumento da demanda (exemplo colocar mais memória).
Pago exatamente o que está sendo usado, somente o necessário. A nuvem é um modelo baseado em consumo.
Se a demanda cair, pode-se reduzir os recursos e consequentemente reduzir custos.

* Elasticidade
Salto repentino acentuado na demanda, recursos implantados poderiam ser expandidos (automaticamente ou manualmente) ex.:época de Black Friday.
Dimensionamento do meu ambiente conforme requisições, adicionar máquinas virtuais ou contêineres por meio da expansão, se houver queda significativa na demanda os recursos podem ser reduzidos horizontalmente (automaticamente ou manual).

* Confiabilidade
Design descentralizado, suporte a infraestrutura confiável e resiliente, permite recursos implantados em várias regiões do mundo. Devido à escala global, mesmo ocorrendo um evento catastrófico em uma região, as outras ainda estarão em funcionamento.

 * Previsibilidade
Microsoft Azure Well-Architected Framework - a previsibilidade na nuvem permite que se avance com confiança, seja no desempenho ou no custo.

* Segurança
Oferece ferramentas de segurança que atendam as necessidades dos clientes.
Obs: lembrar que a implementação de muitas devem ser realizadas pelo cliente, não é responsabilidade da Microsoft.
A infraestrutura como serviço fornece recursos físicos, mas permite que o cliente(usuário) gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção(controle máximo).
Patches e manutenção podem ser tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias.
Provider: oferecer produtos que forneçam segurança.

* Governança
Auditoria sinaliza qualquer recurso esteja fora da conformidade conforme os padrões corporativos
Governança e segurança andam juntos.
Estabelecer a governança o mais rápido possível, para manter proteção e gerenciamento.

* Gerenciabilidade
Opções de capacidade de gerenciamento. Linha de comando, por portal, por arquivos.
Diz respeito a gerenciar seus recursos de nuvem. Ex.: escalar automaticamente a implantação de recursos com base na necessidade.
Implantar recursos com base em um modelo pré configurado, removendo a necessidade de configuração manual.

# Máquinas Virtuais 

Criar uma máquina virtual (VM) no Azure é uma das tarefas mais comuns para usuários da plataforma. Este é um guia passo a passo para iniciar:

- Acesse o Portal do Azure: Faça login em sua conta no portal do Azure.

- Crie um Novo Recurso: No painel esquerdo, clique em "Criar um recurso" e selecione "Máquina Virtual".

- Configure a VM (Virtual Machine)

- Escolha uma imagem do sistema operacional (Windows ou Linux).

- Selecione um tamanho de máquina virtual com base nas suas necessidades de CPU e RAM.

- Configure as opções de rede e armazenamento.

- Defina Credenciais: Crie um nome de usuário e uma senha para acessar a VM.

- Revise e Crie: Revise suas configurações e clique em "Criar".

  # Banco de Dados

  Assim como foi feito para criar uma Máquina Virtual os passos necessários para criar uma instância de Bando de Dados na plataforma:

  - Acesse o Portal do Azure: Faça login em sua conta no portal do Azure.

  - Crie um Novo Recurso: No painel esquerdo, clique em "Criar um recurso" e selecione "SQL Database" ou pode analisar os favoritos onde por padrão tem a opção "Banco de Dados SQL" .
 
    
  ![image](https://github.com/user-attachments/assets/95b1897e-b485-43ee-90d5-9634237ddfec)

  - Configure os detalhes do projeto de Banco de Dados com base na assinatura e grupo de recursos.
 
  - Configure os detalhes do Banco de Dados, como nome do Banco e Servidor (caso não haja um servidor configurado, criar um novo).

  - Defina a computação + armazenamento.
 
  - Revise e Crie: Revise suas configurações e clique em "Criar".

