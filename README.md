# Datas com Função INTERVAL no MySQL

Explorando um pouco a função (interval) visando o passado, então, imagine que hoje a data atual seja, 19 de setembro de 2023.

## Como buscar uma Data em MySQL com intervalo de 30 dias no Passado

<pre>

SELECT 
    NOW() AS DATA_DE_HOJE,
    NOW() - INTERVAL 30 DAY AS DATA_COM_INTERVALO_NO_PASSADO;

Output------------------------------------------------------------------

<table>
  <tbody>
    <tr>
      <td>2023-09-19 00:00:00</td>
      <td>2023-08-20 00:00:00</td>
    </tr>
  </tbody>
</table>

</pre>

## Como buscar uma Data em MySQL com intervalo de 30 dias no Futuro

<pre>

SELECT 
    NOW() AS DATA_DE_HOJE,
    NOW() - INTERVAL 30 DAY AS DATA_COM_INTERVALO_NO_PASSADO;

Output------------------------------------------------------------------

<table>
  <tbody>
    <tr>
      <td>2023-09-19 00:00:00</td>
      <td>2023-10-19 00:00:00</td>
    </tr>
  </tbody>
</table>

</pre>
