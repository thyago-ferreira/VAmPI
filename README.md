# VAmPI
Exploração de Vulnerabilidades do VAmPI com Postman, OWASP ZAP e Hashcat. 

Este repositório surgio através do trabalho de conclusão da matéria Defesa Cibernética (ministrada pelo professor Coronel Anderson), do Instituto Militar de Engenharia. 

Aqui você vai encontrar  resultados sobre a exploração de vulnerabilidades do VAmPI, usando Postman, OWASP ZAP e (não obrigatoriamente Hashcat). 

Sugiro a utilização de uma distro LINUX para essa atividade, caso tenha interesse. 

VAmPI
VAmPI is a vulnerable RESTful API application exposing OWASP Top Ten flaws. It was run directly using Python. Foi criada exatamente para promover um ambiente de treinamento para profissionais da área de segurança da informação ou similares.

Download in: https://github.com/erev0s/VAmPI

ZAP
OWASP ZAP (Zed Attack Proxy) é uma ferramenta de segurança de aplicações web de código aberto, desenvolvida pelo projeto OWASP (Open Web Application Security Project). Ele funciona como um proxy que permite aos usuários inspecionar, manipular e testar o tráfego HTTP e HTTPS de aplicações web para identificar vulnerabilidades de segurança. É amplamente utilizado em testes de penetração (pentest) e desenvolvimento seguro de aplicações. 
Version: 2.14.0.
https://www.zaproxy.org/

Postman
O Postman é uma plataforma colaborativa usada principalmente para desenvolvimento, testes e documentação de APIs (Interfaces de Programação de Aplicativos). Ele permite que desenvolvedores criem, enviem e testem requisições HTTP, visualizem e analisem respostas, e colaborem com outros membros da equipe, tudo através de uma interface gráfica intuitiva. Ele também pode ser utilizado para explorar vulnerabilidades de diversas naturezas, como faremos neste artigo.
Version: 10.x.
https://www.postman.com/downloads/

Hashcat (Optional)
Hashcat is a tool for hash cracking, useful to brute-force weak JWT keys.
Contudo, ela não é necessária, pois a informação do secret já se encontra na documentação do VAmPI, mas achei interessante usar uma ferramenta como essa, pois em um cenário real, geralmente, você não terá essa informação exposta tão facilmente.
Version: 6.2.6
https://hashcat.net/hashcat/

