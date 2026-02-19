# cybersecurity-desafio-phishing
Projeto da formação Cybersecurity Specialist da [DIO](https://dio.me), onde criamos uma página de login falsa para captura de senhas.
Utiliza o sistema operacional Kali Linux e a ferramenta _setoolkit_.

Ao rodar o _setoolkit_, escolhemos _Social Engineering Attacks_ e _Website Attack Vectors_. Depois, _Credential Harvester Attack Method_ e _Custom Import_.

Definidmos o IP da máquina, apontamos o caminho até o diretório onde está localizado o formulário de login falso (index.html). O programa então serve a página na porta 80.

Acessando pelo navegador, o console do _setoolkit_ gera um aviso de requisição GET indicando que abrimos. Inserimos um usuário e senha e, ao clicar no botão, esses dados são automaticamente capturados e exibidos no console do _setoolkit_.
