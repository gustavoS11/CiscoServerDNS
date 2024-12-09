# CiscoServerDNS

Enunciado de Atividade: Configuração de Redes com Redundância e Firewall no Cisco Packet Tracer

Objetivo: Nesta atividade, você deverá configurar um ambiente de rede no Cisco Packet Tracer com as seguintes características:

Redes:
Crie duas redes de Classe A:
Rede Alunos: Destinada ao tráfego de dados dos alunos.
Rede Professores: Exclusiva para o tráfego de dados dos professores.
Ambas as redes devem ter acesso à internet.

Internet com Redundância:
Configure a internet de modo a garantir redundância. Se o link principal falhar, o tráfego de internet deve ser redirecionado automaticamente por um link secundário, garantindo continuidade no acesso.

Firewall:
Implemente um firewall que bloqueie o acesso ao site Ttube.com para todas as redes, sem afetar o acesso aos demais sites.

DNS:
Configure um servidor DNS para o domínio senac.com.br que irá resolver os nomes de máquinas dentro da rede para o endereço IP correspondente.

Requisitos Técnicos:
Configure roteadores e switches conforme necessário para conectar as redes e garantir redundância no acesso à internet.
Utilize ACLs no firewall para implementar as regras de bloqueio do site Ttube.com.
Defina as entradas no servidor DNS para que o domínio senac.com.br seja resolvido corretamente dentro da rede.
Documente cada etapa da configuração e justifique as escolhas feitas para as configurações de redundância, regras do firewall, e registros DNS.

Avaliação:
Sua configuração será avaliada pela funcionalidade de cada um dos requisitos listados acima, incluindo a efetividade do firewall, a operação da redundância do link de internet, e a configuração correta do DNS.
