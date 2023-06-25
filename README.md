<!DOCTYPE html>
<html>
<head>
  <title>Survey Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: aquamarine;
    }

    h1 {
      text-align: center;
    }

    .survey-form {
      max-width: 500px;
      margin: 0 auto;
      padding: 20px;
      background-color: #f2f2f2;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
    }

    .survey-form label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }

    .survey-form input[type="text"],
    .survey-form select {
      width: 95%;
      padding: 9px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 3px;
    }

    .survey-form textarea {
      width: 95%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 3px;
    }

    .survey-form input[type="submit"] {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: #fff;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }

    .survey-form input[type="submit"]:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h1>Survey Form</h1>

  <form class="survey-form">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="age">Age:</label>
    <input type="number" id="age" name="age" required>

    <label for="gender">Gender:</label>
    <select id="gender" name="gender" required>
      <option value="">Select</option>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select>

    <label for="feedback">Feedback:</label>
    <textarea id="feedback" name="feedback" rows="5" required></textarea>

    <input type="submit" value="Submit">
  </form>
</body>
</html>

