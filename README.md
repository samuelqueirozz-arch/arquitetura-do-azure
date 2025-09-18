# arquitetura-do-azure


Microsoft Azure.

🔹 Passo a Passo da Arquitetura

Grupo de Recursos (Resource Group)

Criado para centralizar e organizar todos os componentes da arquitetura.

Rede Virtual (VNet) e Sub-redes

Definida uma VNet principal.

Criadas sub-redes para segmentar os recursos (ex.: aplicação, banco de dados e gerenciamento).

Máquina Virtual (VM)

Implantada VM para hospedar a aplicação.

Configurado acesso via RDP/SSH.

Associada à VNet e à sub-rede correta.

Banco de Dados SQL (Instância Gerenciada)

Criada instância gerenciada do SQL Server.

Configurado firewall e acesso seguro.

Integrada à rede virtual para comunicação privada com a aplicação.

Controle de Tráfego (NSG / Firewall)

Definidas regras de entrada e saída para permitir apenas tráfego essencial.

Garantida segurança entre as camadas da arquitetura.

Testes e Validação

Verificação da comunicação entre aplicação e banco de dados.

Teste de acesso remoto à infraestrutura.

Validação das políticas de segurança aplicadas.
