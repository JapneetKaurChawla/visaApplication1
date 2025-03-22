<?php
$visaStatusMessage = '';
$visaApplicationMessage = '';
$errorMessage = '';
$submitted = false;

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    if (isset($_POST['check_visa'])) {
        $country = $_POST['country'];

        if ($country == "") {
            $visaStatusMessage = "<p class='error'>Please select a country.</p>";
        } else {
            switch ($country) {
                case "USA":
                    $visaStatusMessage = "<p>Visa required for most applicants.</p>";
                    break;
                case "Canada":
                    $visaStatusMessage = "<p>Visa required unless you have an eTA.</p>";
                    break;
                case "India":
                    $visaStatusMessage = "<p>Visa required before travel.</p>";
                    break;
                case "UK":
                    $visaStatusMessage = "<p>Visa depends on the duration of stay.</p>";
                    break;
                case "Australia":
                    $visaStatusMessage = "<p>eVisa available for eligible travelers.</p>";
                    break;
                default:
                    $visaStatusMessage = "<p class='error'>Invalid country selection.</p>";
            }
        }
    }

    if (isset($_POST['apply_visa'])) {
        $name = $_POST['name'];
        $passport = $_POST['passport'];
        $country = $_POST['country'];

        if (!$name || !$passport || !$country) {
            $errorMessage = "All fields are required!";
        } elseif (strlen($passport) < 8 || strlen($passport) > 10) {
            $errorMessage = "Invalid passport number!";
        } else {
            $submitted = true;
            $visaApplicationMessage = "Visa application submitted successfully!";
        }
    }
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visa Application and Check</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        h2 {
            color: #4CAF50;
            margin-bottom: 10px;
        }
        .form-container {
            width: 50%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
        }
        label {
            display: block;
            margin: 8px 0;
        }
        select, input[type="text"], button {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        .message {
            margin-top: 20px;
            font-size: 16px;
        }
        .error {
            color: red;
            font-weight: bold;
        }
        #visaStatus {
            margin-top: 20px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            background-color: #fff4f4;
            color: #d9534f;
        }
    </style>
</head>
<body>

    <header>
        <h1>Visa Check and Application</h1>
    </header>

    <div class="form-container">
        <h2>Visa Check</h2>
        <form action="" method="POST">
            <label for="country">Select your country:</label>
            <select id="country" name="country">
                <option value="">--Select a Country--</option>
                <option value="USA">USA</option>
                <option value="Canada">Canada</option>
                <option value="India">India</option>
                <option value="UK">UK</option>
                <option value="Australia">Australia</option>
            </select>
            <button type="submit" name="check_visa">Check Visa</button>
        </form>

        <div id="visaStatus">
            <?php echo $visaStatusMessage; ?>
        </div>
    </div>

    <div class="form-container">
        <h2>Visa Application Form</h2>
        <form action="" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="passport">Passport Number:</label>
            <input type="text" id="passport" name="passport" required><br><br>

            <label for="country">Select your country:</label>
            <select id="country" name="country" required>
                <option value="">--Select a Country--</option>
                <option value="USA">USA</option>
                <option value="Canada">Canada</option>
                <option value="India">India</option>
                <option value="UK">UK</option>
                <option value="Australia">Australia</option>
            </select><br><br>

            <button type="submit" name="apply_visa">Apply for Visa</button>
        </form>

        <div class="message">
            <?php
            if ($submitted) {
                echo "<p>$visaApplicationMessage</p>";
            } elseif ($errorMessage) {
                echo "<p class='error'>$errorMessage</p>";
            }
            ?>
        </div>
    </div>

    <script>
        document.getElementById("country").addEventListener("change", function() {
            var country = this.value;
            var visaStatus = document.getElementById("visaStatus");

            if (country === "") {
                visaStatus.innerHTML = "<p class='error'>Please select a country.</p>";
            } else {
                switch (country) {
                    case "USA":
                        visaStatus.innerHTML = "<p>Visa required for most applicants.</p>";
                        break;
                    case "Canada":
                        visaStatus.innerHTML = "<p>Visa required unless you have an eTA.</p>";
                        break;
                    case "India":
                        visaStatus.innerHTML = "<p>Visa required before travel.</p>";
                        break;
                    case "UK":
                        visaStatus.innerHTML = "<p>Visa depends on the duration of stay.</p>";
                        break;
                    case "Australia":
                        visaStatus.innerHTML = "<p>eVisa available for eligible travelers.</p>";
                        break;
                    default:
                        visaStatus.innerHTML = "<p class='error'>Invalid country selection.</p>";
                        break;
                }
            }
        });
    </script>

</body>
</html>
