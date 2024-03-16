# PHISHING: CAPTURA DE SENHAS DO FACEBOOK

## Ferramentas utilizadas

- Kali Linux;
- Setoolkit;
- Windows 7.

## Configurando o Phishing no Kali Linux  

- Acesso root: `sudo su`

- Desativando o Apache: `sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill`

- Iniciando o setoolkit: `setoolkit`

- Tipo de ataque: `Social-Engineering Attacks`

- Vetor de ataque: `Web Site Attack Vectors`

- Método de ataque: `Credential Harvester Attack Method` 

- Método de ataque: `Site Cloner`

- URL para clone: http://www.facebook.com

> [!WARNING]
> É importante que o apache seja desativado para que o projeto funcione corretamente.

## Abrindo o site clonado pelo Internet Explorer (Windows 7)

 <img src="https://media.discordapp.net/attachments/1203164000733495407/1218361859309305865/Imagem_do_WhatsApp_de_2024-03-15_as_21.50.48_714f3030.jpg?ex=660762e7&is=65f4ede7&hm=a96ed144d872a32d821909fd99bc65f67091c3c001b68a3e2f0cbe86ef7cb5ee&=&format=webp&width=500&height=400" />

> [!IMPORTANT]
> Alguns navegadores, principalmente aqueles mais atuais, não rodarão o clone. Uma das melhores opções para realizar o teste é o `Internet explorer` do Windows 7. É importante testar as possibilidades!

## Resultado
 <img src="https://media.discordapp.net/attachments/1203164000733495407/1218361859590193152/Imagem_do_WhatsApp_de_2024-03-15_as_21.53.46_9ef21252.jpg?ex=660762e7&is=65f4ede7&hm=924d99593543b6f90db72b5d1d7bd38c0ebedbba3b281c9ad2b686c289bf5a04&=&format=webp&width=515&height=400" />

## Referências
  <a href="https://web.dio.me/users/pedromasca_mkt?tab=achievements" target="_blank">
    <img src="https://lp.dio.me/wp-content/uploads/2023/03/LOGO-DIO-COLOR.png" height="20" "  />
  </a>
  
   <a href="https://github.com/cassiano-dio/cibersecurity-desafio-phishing" target="_blank">
    <img src="https://img.icons8.com/?size=100&id=12599&format=png" height="30" " />
  </a>
