# cybersecurity-desafio-phishing
Projeto da formação Cybersecurity Specialist da [DIO](https://dio.me), onde criamos uma página de login falsa para captura de senhas.
Utiliza o sistema operacional Kali Linux e a ferramenta _setoolkit_.

Ao rodar o _setoolkit_, escolhemos _Social Engineering Attacks_ e _Website Attack Vectors_. Depois, _Credential Harvester Attack Method_ e _Custom Import_.

<img width="671" height="581" alt="Captura de tela de 2026-02-19 10-44-08" src="https://github.com/user-attachments/assets/88b2f20b-1acb-4f94-8fd1-66115b40d42f" />

<img width="671" height="347" alt="Captura de tela de 2026-02-19 10-44-36" src="https://github.com/user-attachments/assets/0b4ca33f-e06b-4e13-9cf9-e17dab751c2d" />

<img width="680" height="622" alt="Captura de tela de 2026-02-19 10-54-53" src="https://github.com/user-attachments/assets/019191af-b2c0-4e45-be66-fbecd4d469aa" />

<img width="680" height="343" alt="Captura de tela de 2026-02-19 10-55-25" src="https://github.com/user-attachments/assets/751524ca-a562-49f5-97f2-e9f9caf4f6b4" />

Definimos o IP da máquina, apontamos o caminho até o diretório onde está localizado o formulário de login falso (index.html). O programa então serve a página na porta 80.

<img width="1257" height="343" alt="Captura de tela de 2026-02-19 10-56-44" src="https://github.com/user-attachments/assets/163696af-6bec-490a-95a3-486b2f1a5ccb" />

<img width="572" height="670" alt="Captura de tela de 2026-02-19 10-57-58" src="https://github.com/user-attachments/assets/a2b5ab53-fac4-4079-863c-036775624a93" />

Acessando pelo navegador, o console do _setoolkit_ gera um aviso de requisição GET indicando que abrimos. Inserimos um usuário e senha e, ao clicar no botão, esses dados são automaticamente capturados e exibidos no console do _setoolkit_.

<img width="582" height="223" alt="Captura de tela de 2026-02-19 10-58-34" src="https://github.com/user-attachments/assets/2722fe3d-885a-4fee-ba58-809323a433f9" />

Ao finalizar, pressionamos Ctrl-C para sair e gerar um pequeno relatório em XML com o resumo do que foi capturado.

<img width="582" height="181" alt="Captura de tela de 2026-02-19 10-59-54" src="https://github.com/user-attachments/assets/4f8810e6-7bb8-409a-af9f-042e359ad019" />

