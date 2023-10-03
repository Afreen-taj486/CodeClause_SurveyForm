# CodeClause_SurveyForm
<!DOCTYPE html>
<html>
<head>
  <title>Survey Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #705e63; 
      color: #fff; 
    }
    .container {
      width: 80%;
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
      background-color: rgba(255, 255, 255, 0.1); 
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }
    h1 {
      text-align: center;
    }
    form {
      margin-top: 20px;
    }
    label {
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #fff; 
      border-radius: 3px;
      background-color: rgba(255, 255, 255, 0.2);
      color: #fff; 
    }
    select {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #fff; 
      border-radius: 3px;
      background-color: rgba(255, 255, 255, 0.2); 
      color: #fff; 
    }
    input[type="radio"],
    input[type="checkbox"] {
      margin-right: 5px;
    }
    button {
      background-color: #a59ab127; 
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 3px;
      cursor: pointer;
    }
    button:hover {
      background-color: #948b8e; 
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Survey Form</h1>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required
      <label for="age">Age:</label>
      <input type="number" id="age" name="age" required>
      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="Male" required>
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="Female" required>
      <label for="female">Female</label>
      <input type="radio" id="other" name="gender" value="Other" required>
      <label for="other">Other</label>
      <label for="feedback">Feedback:</label>
      <textarea id="feedback" name="feedback" rows="4" required></textarea>
      <label for="rating">Rating:</label>
      <select id="rating" name="rating" required>
        <option value="5">5 (Excellent)</option>
        <option value="4">4 (Very Good)</option>
        <option value="3">3 (Good)</option>
        <option value="2">2 (Fair)</option>
        <option value="1">1 (Poor)</option>
      </select>
      <label for="subscribe">Subscribe to Newsletter:</label>
      <input type="checkbox" id="subscribe" name="subscribe" value="yes">
      <label for="subscribe">Yes, I want to subscribe</label>
      <button type="submit">Submit</button>
    </form>
  </div>
</body>
</html>
