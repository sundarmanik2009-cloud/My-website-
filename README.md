<!DOCTYPE html>
<html>
<head>
  <title>Admission Form</title>
  <style>
    body {
      padding: 25px;
      font-family: Arial, sans-serif;
    }
    .title {
      color: #5C6AC4;
    }
    form {
      text-align: left;
      display: inline-block;
    }
    label {
      display: inline-block;
      width: 120px;
    }
    input, select {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <center>
    <h1 class="title">ADMISSION FORM</h1>
    <form>
      <label>User Name</label>
      <input type="text"><br>

      <label>Father Name</label>
      <input type="text"><br>

      <label>Password</label>
      <input type="password"><br>

      <label>Date of Birth</label>
      <input type="date"><br>

      <label>Age</label>
      <input type="number"><br>

      <label>Gender</label>
      <input type="radio" name="gender"> Male
      <input type="radio" name="gender"> Female<br>

      <label>State</label>
      <select>
        <option>Tamilnadu</option>
        <option>Kerala</option>
      </select><br>

      <input type="submit" value="Submit">
    </form>

    <h3>Current Time: <span id="currentTime"></span></h3>
  </center>

  <script>
    function showTime() {
      document.getElementById('currentTime').innerHTML = new Date().toUTCString();
    }
    showTime();
    setInterval(showTime, 1000);
  </script>
</body>
</html># My-website-
