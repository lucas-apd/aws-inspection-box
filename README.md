# aws-inspection-box

A ideia é que esse projeto apoie times dando visibilidade sobre itens de segurança em nuvem AWS, ajudando a evitar configurações/práticas que aumentam riscos.

#### Como:
 - A ideia é criar uma stack que tenha rotinas que coletem as informações e apresentem em formato de dashboard;
 - Seguindo os frameworks mais conhecidos do mercado, como da própria AWS e o CIS;
 - Não é para ser em tempo real;
 - Fazer o básico para qualquer time que trabalhe com AWS;

#### Porquê?
 - Reports são chatos;
 - Quem paga nossos salários não curte terminal e json;
 - As ferramentas ou estão muito complexas ou são pagas;
 - Não encontrei nada com dashboard;
 - Dashboards são bonitos;


#### Verificações:
 - GuardDuty está habilitado?
 - Quais portas estão públicas?
 - Quais são os Buckets Públicos?
 - Temos RDS públicos?
 - Temos RDS sem criptografia?
 - Temos contas IAM sem MFA?
 - Temos contas IAM com Chaves muito antigas?
 - ...

#### Sobre:
 - Segurança em nuvem;
 - Segurança com visibilidade e simplicidade;
 - Redução de superfície de ataque;
 - Melhores práticas de segurança em nuvem;
 - Observability  - Security Stack;

#### Referências:
 - https://github.com/amazon-archives/aws-security-benchmark
