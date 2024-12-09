<?php
session_start();
include "connection1.php";

// Check if user is logged in (you can implement a login system)
if (!isset($_SESSION['user_id'])) {
    header("Location: register.php"); // Redirect to registration if not logged in
    exit();
}

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $user_id = $_SESSION['user_id'];
    $event_name = $_POST['event_name'];
    $event_date = $_POST['event_date'];
    $event_description = $_POST['event_description'];

    $sql = "INSERT INTO event (user_id, name, event_date, description) VALUES ('$user_id', '$event_name', '$event_date', '$event_description')";
    if ($connection->query($sql) === TRUE ) {
        echo "Event created successfully!";
    } else {
        echo "Error: " . $sql . "<br>" . $conn->error;
    }
}

$connection->close();
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create Event</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
<div class="container">
    <h1 class="mt-5">Create Your Event</h1>
    <form method="POST" action="">
        <div class="form-group">
            <label for="event_name">Event Name</label>
            <input type="text" id="event_name" name="event_name" class="form-control" required>
        </div>
        <div class="form-group">
            <label for="event_date">Event Date</label>
            <input type="date" id="event_date" name="event_date" class="form-control" required>
        </div>
        <div class="form-group">
            <label for="event_description">Event Description</label>
            <textarea id="event_description" name="event_description" class="form-control" rows="3" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Create Event</button>
    </form>
</div>
</body>
</html>