- # Packer Base Project

Este projeto fornece uma base para a criação de imagens utilizando Packer, com provisionamento feito através de playbooks do Ansible. Além disso, integrações com GitHub Actions foram configuradas para automação de CI e releases.
## Estrutura do Projeto

O projeto possui a seguinte estrutura de diretórios: 
- **packer/** : Contém os arquivos necessários para a configuração do Packer. 
- **ansible/** : Contém os playbooks do Ansible utilizados para o provisionamento. 
- **.github/workflows/** : Contém os arquivos de configuração das GitHub Actions.
## Configuração do Packer

O diretório `packer/` contém os arquivos necessários para configurar e executar o Packer. Certifique-se de ajustar o arquivo `packer.json` conforme as necessidades do seu projeto.
## Playbooks do Ansible

Os playbooks do Ansible estão localizados no diretório `ansible/`. Personalize esses playbooks de acordo com os requisitos específicos do seu ambiente e aplicação.
## GitHub Actions

O diretório `.github/workflows/` contém os arquivos de configuração das GitHub Actions: 
- **ci.yml** : Configuração para CI, que é acionada a cada push para a branch principal. 
- **release.yml** : Configuração para releases, acionada quando uma nova tag é criada.

Certifique-se de revisar e personalizar esses arquivos conforme necessário.
## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests, relatar problemas ou propor melhorias.
## Licença

Este projeto é licenciado sob a [Licença MIT]() . Consulte o arquivo LICENSE para obter mais detalhes.---

Esperamos que este projeto forneça uma base sólida para a criação e provisionamento de imagens usando Packer e Ansible, facilitando o processo de integração contínua e lançamento automatizado.
