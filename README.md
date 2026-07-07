# community-impact-dashboard
Community Impact Dashboard — a simple web-based dashboard for tracking volunteer hours, completed projects, participant satisfaction, and community program activity.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Community Impact Dashboard</title>

  <style>
    body{
      font-family:Arial,Helvetica,sans-serif;
      background:#f4f6f9;
      margin:40px;
      color:#333;
    }

    h1{
      margin-bottom:5px;
    }

    .cards{
      display:flex;
      gap:20px;
      flex-wrap:wrap;
      margin:30px 0;
    }

    .card{
      background:white;
      padding:20px;
      border-radius:12px;
      width:180px;
      box-shadow:0 2px 8px rgba(0,0,0,.08);
    }

    .number{
      font-size:32px;
      font-weight:bold;
      margin-bottom:8px;
    }

    table{
      width:100%;
      border-collapse:collapse;
      background:white;
      border-radius:10px;
      overflow:hidden;
    }

    th,td{
      padding:14px;
      border-bottom:1px solid #ddd;
      text-align:left;
    }

    th{
      background:#2f80ed;
      color:white;
    }
  </style>
</head>

<body>

<h1>Community Impact Dashboard</h1>

<p>
A simple dashboard demonstrating how a nonprofit could monitor volunteer activity
and community programs.
</p>

<div class="cards">

<div class="card">
<div class="number">42</div>
Volunteers
</div>

<div class="card">
<div class="number">860</div>
Hours Served
</div>

<div class="card">
<div class="number">12</div>
Projects
</div>

<div class="card">
<div class="number">95%</div>
Satisfaction
</div>

</div>

<h2>Current Projects</h2>

<table>

<tr>
<th>Project</th>
<th>Status</th>
</tr>

<tr>
<td>Food Drive</td>
<td>Completed</td>
</tr>

<tr>
<td>Student Mentoring</td>
<td>Active</td>
</tr>

<tr>
<td>Neighborhood Cleanup</td>
<td>Completed</td>
</tr>

<tr>
<td>School Supply Collection</td>
<td>Planning</td>
</tr>

</table>

</body>
</html>
