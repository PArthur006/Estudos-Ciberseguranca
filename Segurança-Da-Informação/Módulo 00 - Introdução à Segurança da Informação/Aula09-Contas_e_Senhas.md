# Aula 09 - Contas e Senhas

### 1. Princípio do Menor Privilégio (Contas de Usuários)
- **A Regra de Ouro:** Não use a conta de Administrador para as tarefas do dia a dia (navegar na internet, checar e-mails, etc.).
- Crie uma conta de usuário padrão, sem privilégios administrativos, e use-a para 99% do seu tempo.
- Use a conta de Administrador (ou o comando `sudo` no Linux) somente quando for estritamente necessário instalar um programa ou alterar uma configuração importante, e pelo menor tempo possível.
- Se você for infectado por um malware enquanto usa a conta padrão, o dano será contido e limitado aos seus arquivos pessoais. Se você estiver na conta de Administrador, o malware terá controle total para danificar todo o sistema operacional.

### 2. Higiene das Contas

- **Contas de Convidado:** Devem ser mantidas desabilitadas por padrão.
- **Contas Compartilhadas:** Evite ao máximo. Cada usuário deve ter sua própria conta para que as ações possam ser rastreadas (auditabilidade).
- **Exigência de Senha:** Todas as contas devem ter uma senha. Desabilite o "login automático" para que a senha seja sempre solicitada ao ligar o computador.

### 3. Criação de Senhas Fortes

- Uma senha forte é sua primeira linha de defesa.
- **Regras Essenciais:**
    - **Comprimento é mais importante que complexidade:** Uma senha longa é mais difícil de quebrar do que uma curta e complexa. Pense em "frases-senha".
    - **Use variedade:** Combine letras maiúsculas, minúsculas, números e símbolos.
    - **Evite o óbvio:** Não use sequências de teclado (`qwerty`, `123456`), dados pessoais (seu nome, data de nascimento, nome do cachorro) ou qualquer informação que possa ser facilmente descoberta sobre você nas redes sociais.

### 4. Segurança Física (Em locais públicos)

- A segurança digital não adianta se a segurança física for negligenciada.
- **Proteção Física:** Use travas de segurança (cabos de aço) para prender seu notebook a um objeto fixo, dificultado o furto.
- **Bloqueio de Tela:** Sempre bloqueie a tela (`Super/Windows + L`) quando se afastar do seu computador, mesmo que seja por um minuto.
- **Criptografia de Disco:** Ative a criptografia de disco completo (como BitLocker no Windows ou o LUKS no Linux). Se seu notebook for roubado, o ladrão terá o hardware, mas não conseguirá acessar seus dados, que estarão ilegíveis sem a senha de descriptografia.
