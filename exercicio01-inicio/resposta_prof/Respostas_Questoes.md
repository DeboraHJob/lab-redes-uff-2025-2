# COM BASE NA LABORATÓRIO REALIZADO RESPONDA: - Minhas Respostas - Professora Déborah Job

1. Quais dos seguintes protocolos aparecem (ou seja, estão listados na coluna “Protocol” do Wireshark) no seu arquivo de rastreamento: TCP, QUIC, HTTP, DNS, UDP, TLSv1.2?

R.STP, TCP, DNS E HTTP

2. Quanto tempo levou desde o envio da mensagem HTTP GET até o recebimento da resposta HTTP OK? 
(Por padrão, o valor da coluna “Time” na janela de listagem de pacotes é a quantidade de tempo, em segundos, desde o início da captura no Wireshark. Se quiser exibir o campo “Time” no formato de hora do dia, selecione o menu suspenso View do Wireshark, depois Time Display Format e, em seguida, Time-of-day.)

R:
15	0.922288292	192.168.0.10	128.119.245.12	HTTP	550	GET /wireshark-labs/INTRO-wireshark-file1.html HTTP/1.1 
19	1.126362570	128.119.245.12	192.168.0.10	HTTP	504	HTTP/1.1 200 OK  (text/html)

15	14:56:40,759057335	192.168.0.10	128.119.245.12	HTTP	550	GET /wireshark-labs/INTRO-wireshark-file1.html HTTP/1.1 
19	14:56:40,963131613	128.119.245.12	192.168.0.10	HTTP	504	HTTP/1.1 200 OK  (text/html)



3. Qual é o endereço IP do site gaia.cs.umass.edu (também conhecido como wwwnet.cs.umass.edu)? Qual é o endereço IP do seu computador ou (se estiver usando o arquivo de rastreamento) do computador que enviou a mensagem HTTP GET?

R: site gaia =  128.119.245.12
endreço ip = 192.168.0.10


4. Expanda as informações da mensagem HTTP na janela “Details of selected packet” do Wireshark para que possa ver os campos na mensagem HTTP GET. Que tipo de navegador Web emitiu a solicitação HTTP?

(A resposta está no final das informações que seguem o campo “User-Agent:” na exibição expandida da mensagem HTTP. [Esse valor no campo da mensagem HTTP é como um servidor web descobre qual navegador você está usando.])

R:  Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36


5. Expanda as informações sobre o Transmission Control Protocol (TCP) deste pacote na janela “Details of selected packet” de modo que você possa ver os campos do segmento TCP que carrega a mensagem HTTP. Qual é o número da porta de destino (o número que aparece após “Dest Port:”) para o segmento TCP que contém a solicitação HTTP?

R: 80


6. Imprima as duas mensagens HTTP (GET e OK) mencionadas na pergunta 2 acima. Para isso, selecione Print no menu File do Wireshark, marque as opções “Selected Packet Only” e “Print as displayed”, e clique em OK.  (Imprima em PDF para anexar no trabalho)

