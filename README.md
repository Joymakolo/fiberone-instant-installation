<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FiberOne - Instant Installation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to FiberOne!</h1>
        <p>We provide fast and reliable internet services.</p>
        <button id="installButton" onclick="requestInstantInstallation()">Request Instant Installation</button>
        
        <!-- Form for user details (hidden initially) -->
        <div id="installationForm" style="display:none;">
            <h2>Kindly assist to fill the following:</h2>
            <form id="installForm">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="phone">Phone Number:</label><br>
                <input type="tel" id="phone" name="phone" required><br><br>

                <label for="email">E-mail:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="address">Address:</label><br>
                <textarea id="address" name="address" required></textarea><br><br>

                <button type="submit">Submit</button>
            </form>
        </div>
    </div>

    <script src="script.js"></script>
</body>  
</html>

