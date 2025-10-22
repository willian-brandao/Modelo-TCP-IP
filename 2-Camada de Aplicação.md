# Camada de Aplicação

É a camada mais alta da arquitetura de ambos os modelos. Basicamente, essa é a camada que interage diretamente com os usuários. Responsável por fornecer interface entre as aplicações e as redes que são transmitidas as nossas mensagens.

Os protocolos da camada de aplicação são utilizados para troca de dados entre programas executados nos hosts de origem e de destino.

<table>
  <tr>
    <th>TCP/IP</th>
    <th>Protocolos da Camada de Aplicação</th>
  </tr>
  <tr>
    <td rowspan="3">Aplicação</td>
    <td rowspan="7">Transferência de Arquivo: TFTP, FTP, NFS <br>
                    Email: SMTP <br>
                    Login Remoto: Telnet, rLogin <br>
                    Gereciamento de Redes: SNMP  <br>
                    Gerenciamento de nomes: DNS
  </tr>
  <tr>

  </tr>
  <tr>
  </tr>
  <tr>
    <td>Transporte</td>
  </tr>
  <tr>
    <td>Internet</td>
 
  </tr>
  <tr>
    <td rowspan="2">Acesso à Rede</td>
  </tr>
  <tr>
  </tr>
</table>

A camada de aplicação do modelo TCP/IP trata de protocolos de alto nível, questões de representação, codificação e controle de diálogos, ou seja, o que as camadas 5, 6 e 7 do modelo OSI fazem separadamente a aplicação do TCP/IP trata como um pacote só, fazendo interface direta com a camada de transporte. 

## Protocolos da camada da camada de aplicação:

* DNS (Domain Name System - Sistema de nome de domínios) - O DNS é um sistema usado na internet para converter os nomes de domínios e seus respectivos nós de rede divulgados publicamente em endereços IP.
* DHCP (Dinamic Host Configuration Protocol) - Utilizado para fornecer dados de configuração das interfaces dinamicamente aos computadores e demais endpoints da rede. Os dados fornecidos são no mínimo endereço IP, máscara de rede, endereço do roteador padrão e servidor DNS. Sem ele os administradores de rede teriam um imenso trabalho braçal.

