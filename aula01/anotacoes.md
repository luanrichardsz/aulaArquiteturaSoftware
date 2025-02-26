# Aula Arquitetura de Software

## Requisitos

Os Requisitos são uma especificação do que **deve ser implementado**.

- São descrições de como o sistema deve se **comportar**, ou de uma propriedade ou atributo do sistema;
- Eles tambem podem ser uma **restrição** no processo de desenvolvimento do sistema;

### Requisitos Funcionais

Os requisitos funcionais definem as funcionalidades que o sistema deve oferecer para atender às necessidades do usuário. Eles especificam **o que o sistema deve fazer**.  

### Requisitos Não Funcionais

Os requisitos não funcionais definem as **qualidades** do sistema, ou seja, **como o sistema deve se comportar** em termos de desempenho, segurança, usabilidade, entre outros fatores.  

#### 📌 **Robustez**  
Refere-se à capacidade do sistema de lidar com falhas e situações inesperadas sem comprometer seu funcionamento.

✅ Exemplos:  
- O sistema deve continuar operando mesmo que um serviço externo esteja indisponível. 
- O sistema deve possuir mecanismos de backup para evitar perda de dados. 

#### ⚡ **Desempenho**  
Define a rapidez e a eficiência com que o sistema executa suas funções.  

✅ Exemplos:  
- O tempo de resposta para qualquer solicitação não deve exceder 2 segundos.  
- O sistema deve ser capaz de processar 1.000 transações simultâneas. 

#### 🎨 **Usabilidade**  
Diz respeito à facilidade de uso e à experiência do usuário ao interagir com o sistema. 

✅ Exemplos:  
- A interface do sistema deve ser intuitiva e acessível a usuários iniciantes.  
- O sistema deve seguir padrões de design para garantir uma experiência consistente. 

#### 🌍 **Portabilidade**  
Refere-se à capacidade do sistema de ser executado em diferentes ambientes e dispositivos sem necessidade de grandes modificações.

✅ Exemplos:  
- O sistema deve ser compatível com os navegadores mais populares (Chrome, Firefox, Edge).  
- O software deve poder ser executado em diferentes sistemas operacionais (Windows, Linux e macOS).  

#### ✅ **Verificabilidade**  
A verificabilidade está relacionada à capacidade de testar e validar o sistema, garantindo que ele atenda aos requisitos especificados e funcione corretamente.

✅ Exemplos:  
- O sistema deve permitir testes automatizados para validar suas funcionalidades.  
- Deve ser possível rastrear e auditar todas as ações dos usuários no sistema.  

#### 📈 **Escalabilidade**  
Refere-se à capacidade do sistema de lidar com o crescimento da demanda, seja aumentando a quantidade de usuários, dados ou requisições sem comprometer o desempenho.

✅ Exemplos:  
- O sistema deve suportar um aumento de 100% na quantidade de usuários sem degradação perceptível no desempenho.  
- A arquitetura deve permitir a adição de novos servidores para distribuir a carga quando necessário. 

#### 🔄 **Reutilização**  
A reutilização refere-se à capacidade do sistema de reaproveitar código, componentes e módulos em diferentes contextos, reduzindo custos e tempo de desenvolvimento.  

✅ Exemplos:  
- O sistema deve utilizar bibliotecas e frameworks reutilizáveis sempre que possível.  
- Os módulos de autenticação e validação devem ser implementados de forma genérica para serem reaproveitados em diferentes partes do sistema.

### Requisitos de Negócio
Os requisitos de negócio descrevem **as necessidades e objetivos da empresa** que o sistema deve atender. Eles não dizem respeito diretamente à implementação técnica, mas sim ao propósito e valor que o sistema deve entregar ao negócio.  

✅ Exemplos de requisitos de negócio:  
- O sistema deve aumentar a taxa de conversão de clientes em 20% nos próximos seis meses.  
- O software deve reduzir o tempo de atendimento ao cliente em pelo menos 30%.  
- A plataforma deve permitir a venda de produtos para clientes internacionais.  
- O sistema deve gerar relatórios financeiros precisos para auxiliar na tomada de decisão. 

### Requisitos do Usuário

Os requisitos do usuário descrevem as necessidades e expectativas dos usuários em relação ao sistema. Eles focam na experiência do usuário e na usabilidade, garantindo que o sistema seja adequado para seu público-alvo.

✅ Exemplos de requisitos do usuário:
- O usuário deve conseguir se cadastrar no sistema com um e-mail e senha ou utilizando redes sociais.
- O sistema deve permitir que o usuário recupere sua senha através de um e-mail de redefinição.