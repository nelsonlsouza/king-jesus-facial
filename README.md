#  King Jesus Facial

Protótipo de um sistema de **reconhecimento facial para automatização de frequência em academias de Jiu-Jitsu**.

O projeto está sendo desenvolvido como uma extensão de um sistema de gestão, com o objetivo de identificar alunos e registrar automaticamente sua presença durante as aulas.

>  Projeto em fase de prototipação e estudo técnico.

##  Objetivo

A proposta é desenvolver uma solução própria de reconhecimento facial em vez de depender exclusivamente de equipamentos comerciais fechados, como leitores biométricos ou terminais de reconhecimento facial.

O desenvolvimento de uma solução própria permite explorar maior autonomia de integração com o sistema de gestão e, ao mesmo tempo, aprofundar conhecimentos em reconhecimento facial, visão computacional, backend e arquitetura de software.

##  Funcionamento planejado

O fluxo esperado do sistema é:

`Captura facial → Identificação do aluno → Validação → Sistema da academia → Registro automático de presença`

Ao reconhecer um aluno cadastrado, a aplicação deverá comunicar-se com o sistema de gestão e registrar sua presença automaticamente.

##  Protótipo atual

A versão atual é utilizada para validar conceitos técnicos relacionados a:

- Captura e processamento facial
- Identificação de usuários
- Integração entre frontend e backend
- Persistência de informações
- Funcionamento em diferentes dispositivos
- Viabilidade do reconhecimento facial para controle de frequência

##  Tecnologias

Atualmente o protótipo utiliza:

- React
- TypeScript
- Vite
- Supabase
- Human
- Vitest
- PWA
- Git
- GitHub

##  AWS Rekognition

A utilização do **AWS Rekognition está em avaliação** para futuras versões do projeto.

A proposta é estudar sua viabilidade para identificação facial e comparar aspectos como precisão, custo, escalabilidade e facilidade de integração antes de definir a arquitetura definitiva.

Portanto, AWS Rekognition ainda não deve ser considerado uma dependência definitiva do sistema.

##  Roadmap

- [x] Desenvolvimento do protótipo inicial
- [x] Estrutura inicial da aplicação
- [x] Integração com banco de dados
- [ ] Aprimorar identificação facial
- [ ] Avaliar integração com AWS Rekognition
- [ ] Integrar com o sistema principal da academia
- [ ] Automatizar registro de presença
- [ ] Implementar regras de validação
- [ ] Realizar testes em ambiente real
- [ ] Avaliar segurança e proteção dos dados biométricos

##  Segurança e privacidade

Como o projeto envolve dados relacionados à identificação facial, segurança e privacidade fazem parte dos requisitos da solução.

Credenciais e configurações sensíveis não devem ser armazenadas diretamente no repositório.

O tratamento definitivo dos dados biométricos ainda será definido conforme a evolução da arquitetura do projeto.

##  Status

**Protótipo em desenvolvimento / estudo de viabilidade técnica.**

O projeto ainda não representa uma solução final de produção.

##  Desenvolvedor

**Nelson Souza**  
Desenvolvedor de Software

GitHub: [@nelsonlsouza](https://github.com/nelsonlsouza)
