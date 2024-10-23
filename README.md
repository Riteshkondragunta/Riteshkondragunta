<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CelebrateMate - Reminder App</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>CelebrateMate</h1>
        <p>Your automated birthday and anniversary reminder service.</p>
    </header>

    <main>
        <form id="reminderForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="date">Date of Birth/Anniversary:</label>
            <input type="date" id="date" name="date" required>

            <label for="contact">Contact (Email/SMS):</label>
            <input type="text" id="contact" name="contact" required>

            <button type="submit">Set Reminder</button>
        </form>

        <div id="confirmationMessage" style="display:none;">
            <p>Reminder set successfully!</p>
        </div>
    </main>

    <footer>
        <p>&copy; 2023 CelebrateMate. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

<!---
Riteshkondragunta/Riteshkondragunta is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
