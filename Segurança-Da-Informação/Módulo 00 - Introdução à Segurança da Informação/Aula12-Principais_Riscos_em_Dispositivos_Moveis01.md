# Aula 12: Principais Riscos em Dispositivos Móveis (Parte 1)

### 1, A Convergência de Riscos

- **Funcionalidades e Riscos Similares:** Dispositivos móveis, na prática, são computadores. Portante, eles herdam os mesmos riscos: *infecção por códigos maliciosos (malwares), golpes de phishing,perda de dados, etc.*.
- **O Fator Agravante:** As características que tornam os celulares tao úteis (portabilidade, conectividade constante, grande volume de dados pessoais) também os tornam alvos ainda mais atraentes para atacantes.

### 2. O Grande Risco: Vazamento de Informações

- **Armazenamento Centralizado:** Celulares contêm uma enorme quantidade de informações sobre nós em um único local: Contatos, fotos, mensagens, histórico de localização, dados de saúde, informações financeiras.
- **Ciclo de Vida do Aparelho:** A rápida substituição de modelos gera riscos. Ao vender ou descartar um aparelho antigo, é crucial garantir que todos os dados foram apagados de forma segura e permanente (restauração de fábrica).
    - `NOTA: Lembre-se do princípio fundamental da forense digital: "apagar" raramente significa "destruir". Em um disco não criptografado, apagar um arquivo é como remover o nome dele do índice de um livro; as páginas ainda existem até que algo novo seja escrito por cima. A restauração de fábrica em um celular moderno e criptogradado é muito segura, pois ela destrói a "chave" que decifra os dados. Mesmo assim, a regra de outro ao se desfazer de qualquer dispositivo é sempre realizar a restauração completa para as configurações de fábrica`.
- **Coleta Indevida de Dados:** Aplicativos maliciosos ou mesmo legítimos podem coletar mais informações do que o necessário, como acesso a microfone, câmera, contatos e localização, sem um motivo claro. É fundamental verificar as permissões que cada app solicita.