# Aula 08 - Aplicativos de Terceiros

### 1. Cuidados ao Instalar Aplicativos

- **Verificação de Permissões:** 
    - Antes de instalar, sempre verifique quais permissões um aplicativo está solicitando. Um aplicativo de lanterna, por exemplo, não tem motivo para pedir acesso aos seus contatos.
    - Questione se as permissões pedidas são coerentes com a função do aplicativo. Se parecer excessivo, não instale ou procure uma alternativa.
- **Acesso a Dados Pessoais:**
    - Muitos aplicativos pedem para se conectar às suas contas (Google, Facebook, etc.) ou acessar seus dados pessoais. Seja muito seletivo. Conceda esse acesso apenas a aplicativos de empresas conhecidas e confiáveis. Revise periodicamente as permissões concedidas nas configurações das suas contas.

### 2. Mecanismos de Proteção (Defesa em Camadas)

- **Antivírus / Antimalware:**
    - Atua como um "segurança" que verifica arquivos novos e processos em execução em busca de assinaturas de software malicioso.
    -Como já registrei anteriormente, para usuários de Linux, a melhor "proteção" é a prática de instalar softwares apenas de repositórios confiáveis (loja do Ubuntu, `apt`, Flatpak), manter o sistema atualizado e ter cuidado com o que você executa com `sudo`.
- **Firewall Pessoal:**
    - É um "porteiro" que controla o tráfego de rede que entra e sai do seu computador. Ele pode bloquear conexões indesejadas.
    - O Ubuntu já vem com um firewall poderoso chamado `ufw` (Uncomplicated Firewall), que por padrão vem desativado, mas com uma política segura. Ativá-lo é uma boa prática: `sudo ufw enable`.
- **Disco de Recuperação:**
    - é uma "cópia de segurança" do seu sistema. Se o seu sistema for danificado por um malware a ponto de não iniciar mais, você pode usar o disco de recuperação para tentar consertá-lo ou para salvar seus arquivos pessoais antes de uma formatação.
- **Cuidado com Links e Mensagens:**
    - A principal porta de entrada para malware é a **Engenharia Social**.
        - Nunca clique em links de fontes não confiáveis.
        - Use copmlementos de navegador para expandir links encurtados antes de clicar.
        - Lembre-se que contas de amigos podem ser invadidas. Se receber uma mensagem estranha de um desconhecido, confirme por outro meio antes de clicar em qualquer coisa.
- **Desabilitar a Auto-Execução:**
    - A função que faz com que mídias removíveis (pendrives) ou anexos rodem automaticamente.
    - Sempre desabilite essa função no Windows e MacOs. No Linux, isso já é o padrão; nada é executado sem a sua permissão explícita. Você precisa dar permissão de execução `chmod +x` e então rodar o arquivo manualmente `./arquivo`.