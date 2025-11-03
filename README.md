# Atividade-Desempenho_Threads
Atividade Pratica - Comparacao de Desempenho Threads
<h2>Integrantes do Grupo:</h2>
<h3><strong>Roberto Zhou</strong></h3>
<h3><strong>Matheus de Bortoli Silva</strong></h3>
<h1>Tabela de execução</h1>
<table>
  <thead>
    <tr>
      <th></th>
      <th>Thread 10</th>
      <th>Thread 100</th>
      <th>Thread 500</th>
      <th>Thread 1000</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>N:M</td>
      <td>517</td>
      <td>581</td>
      <td>628</td>
      <td>682</td>
    </tr>
    <tr>
      <td>1:1</td>
      <td>2517</td>
      <td>2552</td>
      <td>2597</td>
      <td>2643</td>
    </tr>
  </tbody>
</table>


Segue abaixo os gráficos do desempenho do sistema
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/0596d814-6c31-4d60-9164-33d8fd0203b7" />


<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/cef6fb65-09b5-4194-89c3-b9e0eab36d37" />


<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/193be7ca-dedb-490a-9cad-ecb51c22e86e" />


# Resultados
O modelo N:M apresentou melhor desempenho geral, sendo mais eficiente e escalável.
O modelo 1:1, embora mais simples, é menos indicado para cenários com alta concorrência, pois exige mais recursos do sistema.
