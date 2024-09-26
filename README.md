# DIO-resumo-lab-2
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

<h1>Desvendando os serviços da nuvem</h1>

<h2>SLA</h2>
<p>SLA, ou Acordo de Nível de Serviço, é um assunto super importante quando falamos de tecnologia. Basicamente, ele define quanto tempo um serviço pode ficar fora do ar sem afetar demais a operação. Isso é medido de três formas: por semana, por mês e por ano. </p>

<p>Por exemplo, se você tem um SLA que permite um tempo de inatividade de uma hora por mês, isso significa que a empresa espera que o serviço esteja funcionando a maior parte do tempo. E quando se trata de tempo de inatividade por ano, a conta muda um pouco, mas a ideia é a mesma: garantir que os serviços sejam confiáveis. Saber disso ajuda a entender como escolher provedores e planejar melhor seus projetos. </p>

<h2>Porcentagem SLA</h2>
<ul>
  <li><strong>99%:</strong> Isso significa que o serviço pode ter até 14 horas e 24 minutos de inatividade por mês. É um nível básico de confiabilidade.</li>
  <li><strong>99,5%:</strong> Permite cerca de 10 horas de inatividade por mês. É um pouco melhor, mas ainda pode não ser ideal para aplicações críticas.</li>
  <li><strong>99,9% (três noves):</strong> Com isso, o tempo de inatividade permitido é de cerca de 40 minutos por mês. É um padrão comum para muitas empresas que buscam boa confiabilidade.</li>
  <li><strong>99,99% (quatro noves):</strong> Aqui, o tempo de inatividade máximo é de cerca de 4 minutos por mês. Esse nível é ótimo para serviços que não podem se dar ao luxo de falhas.</li>
  <li><strong>99,999% (cinco noves):</strong> Isso permite apenas cerca de 26 segundos de inatividade por mês. É o nível mais alto de confiabilidade e é crucial para sistemas críticos.</li>
</ul>

<h2>Detalhes da instância</h2>
<p>Quando falamos de "detalhes da instância" em ambientes de nuvem, como o Azure, estamos nos referindo a várias características importantes de uma máquina virtual ou serviço. Aqui estão alguns dos principais detalhes que costumam ser considerados:</p>

<ol>
  <li><strong>Tipo de Instância:</strong> O tipo determina os recursos que a instância terá, como CPU, memória e armazenamento. Por exemplo, instâncias de série D são boas para aplicações gerais, enquanto as de série F são otimizadas para desempenho de CPU.</li>
  <li><strong>Tamanho da Instância:</strong> Relaciona-se à quantidade de recursos alocados, como núcleos de CPU e RAM. O tamanho afeta diretamente o desempenho e o custo.</li>
  <li><strong>Região:</strong> A localização onde a instância está hospedada. A escolha da região pode influenciar a latência e a conformidade com regulamentos locais.</li>
  <li><strong>Sistema Operacional:</strong> O tipo de sistema operacional instalado, como Windows ou Linux, que pode afetar a compatibilidade de software e a configuração.</li>
  <li><strong>Armazenamento:</strong> O tipo e a quantidade de armazenamento associado à instância, que pode incluir discos SSD ou HDD, e suas capacidades.</li>
  <li><strong>Rede:</strong> Configurações de rede, como endereços IP e grupos de segurança, que determinam como a instância se comunica com outras instâncias e serviços.</li>
  <li><strong>Escalabilidade:</strong> A capacidade de aumentar ou diminuir os recursos da instância conforme necessário, como adicionar mais CPU ou RAM.</li>
  <li><strong>Tempo de Atividade:</strong> Informações sobre a disponibilidade da instância, incluindo SLAs que garantem a operação contínua.</li>
</ol>

<h2>Criar uma conta de armazenamento</h2>
<p>Para criar uma conta de armazenamento no Azure, siga estes passos:</p>

<p>Acesse o Portal do Azure: Vá para portal.azure.com e faça login na sua conta.</p>

<p>Criar um Novo Recurso: Clique em “Criar um recurso” no menu à esquerda.</p>

<p>Selecionar Armazenamento: Na barra de pesquisa, digite “Conta de Armazenamento” e selecione “Conta de Armazenamento” nos resultados.</p>
<br>

<strong>Preencher as Informações:</strong>

<p><strong>Assinatura:</strong> Selecione a assinatura que deseja usar.</p>
<p><strong>Grupo de Recursos:</strong> Escolha um grupo existente ou crie um novo.</p>
<p><strong>Nome da Conta:</strong> Escolha um nome exclusivo para sua conta de armazenamento.</p>
<p><strong>Região:</strong> Selecione a região onde deseja que a conta esteja localizada.</p>
<p><strong>Tipo de Conta:</strong> Escolha entre “StorageV2” para recursos gerais, “BlobStorage” para armazenamento de blobs, etc.</p>
<p><strong>Configurações Avançadas:</strong> Defina opções como redundância (LRS, GRS, etc.) e opções de acesso.</p>
<p><strong>Revisar e Criar:</strong> Revise suas configurações e clique em “Criar” para finalizar o processo.</p>
