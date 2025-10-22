# Arquitetura TCP/IP

A Arquitetura TCP/IP é composta por apenas 4 camadas, sendo que na prática, as camadas 5, 6 e 7 do modelo OSI foram mescladas para formar a camada de Aplicação do TCP/IP. 

Já as camadas 3 e 4 do modelo OSI são similares às camadas 2 e 3 do TCP/IP, inclusive a camada de transporte do TCP/IP tem o mesmo nome, porém a camada 3 do modelo OSI(rede) no TCP/IP é chamada de Internet.

Por fim, as camadas 1 e 2 do modelo OSI foram mescladas no TCP/IP para formar a camada de acesso aos meios ou acesso à rede. 

<!---
|TCP/IP                  | ISO/OSI             |
|:-----------------------|--------------------:|
|                        |     Aplicação       |
|    Aplicação           |     Apresentação    |
|                        |     Sessão          |
|    Transporte          |     Transporte      |
|    Internet            |     Rede            |
|    Acesso à Rede       |     Enlace          |
|                        |     Física          |
-->

<table>
  <tr>
    <th>TCP/IP</th>
    <th>ISO/OSI</th>
  </tr>
  <tr>
    <td rowspan="3">Aplicação</td>
    <td>Aplicação</td>
  </tr>
  <tr>
    <td>Apresentação</td>
  </tr>
  <tr>
    <td>Sessão</td>
  </tr>
  <tr>
    <td>Transporte</td>
    <td>Transporte</td>
  </tr>
  <tr>
    <td>Internet</td>
    <td>Rede</td>
  </tr>
  <tr>
    <td rowspan="2">Acesso à Rede</td>
    <td>Enlace</td>
  </tr>
  <tr>
    <td>Física</td>
  </tr>
</table>


No TCP/IP não costumamos nos referir por camadas e sim pelos nomes delas, pois quando nos referimos pelo número da camada estamos falando de OSI. 

