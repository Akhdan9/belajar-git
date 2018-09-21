<!DOCTYPE html>
<html>
  <head>
    <title> Latihan 1 </title>
    <style>
      table { border-collapse:collapse; }
      th,td {width: 150px; height: 30px; color: white;}
      th {background-color: gray; }
      tbody tr:nth-child(odd) td {background-color: green;}
      tbody tr:nth-child(even) td {background-color: black;}
      tbody tr:nth-child(odd):hover td {
        background-color: white;
        color: green;
      }
      tbody tr:nth-child(even):hover td {background-color: white;
        color: black;
      }
    </style>
  </head>
  <body>
    <table>
      <caption> Judul Tabel </caption>
      <thead>
        <tr>
          <th> Judul Kolom 1</th>
          <th> Judul Kolom 2</th>
          <th> Judul Kolom 3 </th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td> Baris 2 kolom 1 </td>
          <td> Baris 2 Kolom 2 </td>
          <td> Baris 2 Kolom 3 </td>
        </tr>
        <tr>
          <td> Baris 3 kolom 1 </td>
          <td> Baris 3 Kolom 2 </td>
          <td> Baris 3 Kolom 3 </td>
        </tr>
        <tr>
          <td> Baris 4 kolom 1 </td>
          <td> Baris 4 Kolom 2 </td>
          <td> Baris 4 Kolom 3 </td>
        </tr>
        <tr>
          <td> Baris 5 kolom 1 </td>
          <td> Baris 5 Kolom 2 </td>
          <td> Baris 5 Kolom 3 </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
<!-- MUHAMMAD AKHDAN BAIHAQI / 29 / XR4 -->
