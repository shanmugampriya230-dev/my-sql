<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airlines Flight Ticket Booking App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Airlines Flight Ticket Booking App</h1>
    </header>
    <main>
        <section class="search-form">
            <h2>Search for Flights</h2>
            <form id="search-form">
                <label for="from">From:</label>
                <input type="text" id="from" name="from">
                <label for="to">To:</label>
                <input type="text" id="to" name="to">
                <label for="departure-date">Departure Date:</label>
                <input type="date" id="departure-date" name="departure-date">
                <label for="return-date">Return Date:</label>
                <input type="date" id="return-date" name="return-date">
                <button id="search-btn">Search</button>
            </form>
        </section>
        <section class="flight-results">
            <h2>Flight Results</h2>
            <ul id="flight-results-list"></ul>
        </section>
        <section class="booking-form">
            <h2>Book a Flight</h2>
            <form id="booking-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="phone">Phone:</label>
                <input type="text" id="phone" name="phone">
                <button id="book-btn">Book</button>
            </form>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
