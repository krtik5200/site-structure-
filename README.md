<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eyebrow Service Website</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Treatments</a></li>
                <li><a href="#">Packages</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="welcome">
        <div>
            <img src="hero-image-placeholder.jpg" alt="Close-up of a person with well-defined eyebrows">
        </div>
        <div>
            <h1>We Change the World<br>One Eyebrow at a Time</h1>
            <a href="#" role="button">Book an Appointment</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div>
            <img src="about-image-placeholder.jpg" alt="Person working in a salon">
        </div>
        <article>
            <h2>Our Story</h2>
            <p>
            </p>
        </article>
    </section>

    <!-- Booking Section -->
    <section id="booking">
        <h2>BRW's #1 Service</h2>
        <div>
            <form>
                <label for="date">Select a Date and Time</label>
                <input type="date" id="date" name="date">

                <label for="service">Service Details</label>
                <select id="service" name="service">
                    <option value="brow-shaping">BRW Custom Shaping - $30</option>
                </select>

                <button type="submit">Check Next Availability</button>
            </form>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Follow Us @brwbar</h2>
        <div>
            <img src="gallery-image-1.jpg" alt="A coffee cup with 'Brows Before Bros'">
            <img src="gallery-image-2.jpg" alt="Close-up of someone applying brow pencil">
            <img src="gallery-image-3.jpg" alt="Makeup tools">
        </div>
    </section>

    <!-- Contact Section -->
    <footer>
        <section id="contact">
            <div>
                <h3>Contact</h3>
                <p>500 Terry Francine Street<br>San Francisco, CA 94158</p>
                <p>Mon-Fri: 10am - 7pm<br>Sat-Sun: 11am - 4pm</p>
            </div>
            <form>
                <label for="first-name">First Name</label>
                <input type="text" id="first-name" name="first-name" required>

                <label for="last-name">Last Name</label>
                <input type="text" id="last-name" name="last-name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message"></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>
    </footer>
</body>
</html>
