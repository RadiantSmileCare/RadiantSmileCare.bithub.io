<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Radiant Smile Care - Book Appointment</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Book an Appointment</h1>
    <form id="appointmentForm">
      <label for="fullName">Full Name:</label>
      <input type="text" id="fullName" name="fullName" required><br><br>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br><br>
      
      <label for="phoneNumber">Phone Number:</label>
      <input type="tel" id="phoneNumber" name="phoneNumber" required><br><br>
      
      <label for="date">Preferred Date:</label>
      <input type="date" id="date" name="date" required><br><br>
      
      <label for="time">Preferred Time:</label>
      <input type="time" id="time" name="time" required><br><br>
      
      <input type="submit" value="Book Appointment">
    </form>
  </div>
  <script src="script.js"></script>
</body>
</html>
