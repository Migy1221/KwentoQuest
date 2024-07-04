<?php
// Check if form is submitted
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Retrieve selected day, month, and year from POST data
    $day = $_POST['day'];
    $month = $_POST['month'];
    $year = $_POST['year'];

    // Validate the selected values
    if (!empty($day) && !empty($month) && !empty($year)) {
        // Construct the birthdate in a valid format (YYYY-MM-DD)
        $birthdate = $year . '-' . $month . '-' . $day;

        // Calculate age based on birthdate
        $today = new DateTime();
        $birthdateObj = new DateTime($birthdate);
        $age = $today->diff($birthdateObj)->y;

        // Check if age is less than 18
        if ($age < 18) {
            // Send back JSON response with error message
            http_response_code(403);
            echo json_encode(array("error" => "You must be at least 18 years old to enter this site."));
            exit();
        } else {
            // Age verification successful
            // Optionally, set a session or cookie to indicate successful verification
            // Redirect user to homepage
            http_response_code(200);
            echo json_encode(array("success" => "Age verification successful. Redirecting..."));
            exit();
        }
    } else {
        // Handle if day, month, or year is not selected
        http_response_code(400);
        echo json_encode(array("error" => "Please select valid day, month, and year."));
        exit();
    }
} else {
    // Handle if form is not submitted (optional)
    http_response_code(400);
    echo json_encode(array("error" => "Form submission error."));
    exit();
}
?>