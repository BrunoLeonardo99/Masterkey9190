Phishing para Captura de Senhas do Facebook com SETOOLKIT
Este repositório apresenta um passo a passo para configurar um ataque de phishing utilizando o Social-Engineer Toolkit (SET) no Kali Linux. É destinado a profissionais e estudantes de segurança da informação, exclusivamente para fins educacionais e testes em ambientes controlados e autorizados.

Pré-requisitos
Kali Linux atualizado

Acesso root (sudo)

Conexão de rede funcional

Conhecimentos básicos de redes e terminal

Passo a Passo
1. Obtenha privilégios de superusuário:
sudo su

2. Inicie o Social-Engineer Toolkit:
Copiar código
setoolkit

3. Navegue pelo menu do SET:
Selecione as seguintes opções na ordem apresentada:
1) Social-Engineering Attacks  
2) Web Site Attack Vectors  
3) Credential Harvester Attack Method  
4) Site Cloner

4. Obtenha o IP da sua máquina:
ifconfig
Anote o endereço IP local (ex: 192.168.0.105)

5. Clone o site alvo:
Na opção "Site Cloner", insira a URL a ser clonada:
http://www.facebook.com
Avisos Importantes
Este projeto é fornecido somente para fins educacionais.

Não utilize em redes públicas, pessoas reais ou sistemas sem autorização.

Utilize apenas em ambientes de testes locais ou laboratórios controlados.

O uso indevido pode violar leis e regulamentos de cibersegurança. Responsabilize-se por seus atos.
Testando a Página Clonada
Use outro dispositivo na mesma rede local.
Acesse via navegador:

http://[SEU-IP]
Exemplo:
http://192.168.0.105
Preencha com qualquer usuário/senha.

Veja os dados capturados diretamente no terminal onde o SET está rodando.


<!--
**masterkey9190/Masterkey9190** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
