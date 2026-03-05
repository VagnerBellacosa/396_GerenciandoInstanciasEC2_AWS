[Início](https://www.ibm.com/br-pt)[Produtos](https://www.ibm.com/br-pt/products)[Instana](https://www.ibm.com/br-pt/products/instana)[Tecnologias suportadas](https://www.ibm.com/br-pt/products/instana/supported-technologies)Monitoramento do AWS EC2

# Monitoramento do AWS – EC2

- [Monitoramento e gerenciamento do AWS EC2](https://www.ibm.com/br-pt/products/instana/supported-technologies/aws-ec2-monitoring#Monitoramento+e+gerenciamento+do+AWS+EC2)
- [Métricas de configuração e desempenho do AWS EC2](https://www.ibm.com/br-pt/products/instana/supported-technologies/aws-ec2-monitoring#Métricas+de+configuração+e+desempenho+do+AWS+EC2)
- [Monitoramento das mudanças na configuração do Amazon EC2](https://www.ibm.com/br-pt/products/instana/supported-technologies/aws-ec2-monitoring#Monitoramento+das+mudanças+na+configuração+do+Amazon+EC2)
- [Identificações do AWS EC2 e do Instana](https://www.ibm.com/br-pt/products/instana/supported-technologies/aws-ec2-monitoring#Identificações+do+AWS+EC2+e+do+Instana)
- [Introdução ao monitoramento do AWS EC2/instalação](https://www.ibm.com/br-pt/products/instana/supported-technologies/aws-ec2-monitoring#Introdução+ao+monitoramento+do+AWS+EC2%2Finstalação)

![Logotipo do AWS EC2](https://www.ibm.com/content/adobe-cms/br/pt/products/instana/supported-technologies/aws-ec2-monitoring/jcr:content/root/table_of_contents/body/content_section_styled/content-section-body/complex_narrative/logoimage.coreimg.png/1764270929574/aws-ec2.png)



Monitoramento e gerenciamento do AWS EC2









Uma parte importante das [soluções de APM para nuvem](https://www.ibm.com/br-pt/products/instana), especialmente na execução de aplicações na Amazon Web Services, é uma solução completa de monitoramento do Amazon EC2. [Amazon Web Services](https://aws.amazon.com/) (AWS) Elastic Compute Cloud (Amazon EC2) é uma parte central da plataforma de computação em nuvem da Amazon, que disponibiliza Infraestrutura como Serviço (IaaS). O usuário pode personalizar diferentes especificações de servidor privado virtual com cobranças por hora, minuto ou segundo, disponibilizando uma estrutura de infraestrutura altamente elástica. Monitorar instâncias do Amazon EC2 é uma tarefa difícil (pois ele não é tecnicamente controlado pelo usuário) e fácil (pois há várias APIs da Amazon criadas para ajudar com algumas informações).

O agente do Instana detecta automaticamente que está sendo executado em uma instância do Amazon EC2 e instala o sensor de monitoramento do AWS EC2.









Comece sua AVALIAÇÃO SEM CUSTO hoje!



14 dias, sem cartão de crédito, versão integral



[Comece já](https://www.ibm.com/account/reg/signup?formid=urx-52345)

Métricas de configuração e desempenho do AWS EC2

O monitoramento do desempenho e da disponibilidade das aplicações baseadas na nuvem pelo Amazon EC2 não é tão simples quanto monitorar um servidor local (ou hospedado), pois as instâncias do Amazon EC2 tendem a ser temporárias. Além disso, as plataformas instaladas em qualquer instância do Amazon EC2 devem ser o centro da atividade de monitoramento dos aplicativos. Por esse motivo, o monitoramento do Amazon EC2 do Instana concentra-se nos dados de configuração do Amazon EC2 para cada instância. Pois cada máquina virtual é basicamente um quadro em branco que os clientes podem instanciar, iniciar e interromper.

O monitoramento do Amazon EC2 do Instana inclui os seguintes dados de configuração:

- Zona de disponibilidade
- ID da AMI
- Tipo
- Grupos de segurança

Todos os metadados capturados são indexados pelo Instana e estão disponíveis para o mecanismo de pesquisa de foco dinâmico do Instana, permitindo consultas como: `entity.ec2.type:m4.xlarge E entity.selfType:mongodb`

Esses metadados são úteis para que os usuários vejam o estado exato de todas as entidades envolvidas de alguma forma com o Amazon EC2, como focar em todas as instâncias do Mongodb em execução em um tipo m4.xlarge, como no exemplo acima.







Monitoramento das mudanças na configuração do Amazon EC2

O Instana rastreará toda e qualquer mudança na linha do tempo, há um exemplo na captura de tela abaixo:

![Monitoramento do Amazon EC2 — Tela de status](https://www.ibm.com/content/adobe-cms/br/pt/products/instana/supported-technologies/aws-ec2-monitoring/jcr:content/root/table_of_contents/body/content_section_styled/content-section-body/simple_narrative_cop/image.coreimg.png/1764270931862/screen-shot-2017-09-18-at-18-22-11.png)







![Monitoramento do Amazon EC2 — Tela de status](https://www.ibm.com/content/adobe-cms/br/pt/products/instana/supported-technologies/aws-ec2-monitoring/jcr:content/root/table_of_contents/body/content_section_styled/content-section-body/simple_narrative_cop/image.coreimg.png/1764270931862/screen-shot-2017-09-18-at-18-22-11.png)







Identificações do AWS EC2 e do Instana

Observe que atualmente as identificações estão inacessíveis para o próprio host, principalmente porque elas estão ausentes na API de metadados da AWS. Gostaríamos muito que a Amazon implementasse esse recurso. Se você concorda, manifeste-se neste [encadeamento dos fóruns da AWS](https://repost.aws/forums?origin=thread.jspa&start=0&threadID=57062&tstart=0).







Introdução ao monitoramento do AWS EC2/instalação

Pronto para começar? Antes, você precisará ter uma conta ou avaliação do Instana. Já tem? Ótimo. O melhor local para começar é o Guia de introdução do Instana.

[Guia de introdução do Instana](https://www.ibm.com/docs/pt/instana-observability/1.0.309)