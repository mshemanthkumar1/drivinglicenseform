<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Driving License Registration Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Driving License Registration Form</h1>
    <form action="submit-form.php" method="post">
        <label for="fullName">Full Name:</label>
        <input type="text" id="fullName" name="fullName" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <label for="address">Address:</label>
        <textarea id="address" name="address" rows="4" cols="50" required></textarea><br><br>

        <label for="licenseType">License Type:</label>
        <select id="licenseType" name="licenseType" required>
            <option value="twoWheeler">Two Wheeler</option>
            <option value="fourWheeler">Four Wheeler</option>
            <option value="both">Both</option>
        </select><br><br>

        <label for="photo">Upload Photo:</label>
        <input type="file" id="photo" name="photo" accept="image/*" required><br><br>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
# drivinglicenseform
