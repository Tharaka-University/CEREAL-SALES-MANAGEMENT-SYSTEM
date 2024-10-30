<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Cereal Board Suppliers</title>
	<style>
		body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
		header, footer { background-color: #4CAF50; color: white; padding: 15px 20px; text-align: center; }
		.container { padding: 20px; }
		.section { margin: 20px 0; }
		h1, h2, h3, h4 { color: #333; }
		ul { list-style-type: none; padding: 0; }
		li { margin: 5px 0; }
		form label, form input, form select { display: block; margin: 10px 0; }
		.footer-links { display: flex; gap: 20px; justify-content: center; padding: 10px 0; }
		.footer-links li { list-style: none; }
		.social-links { display: flex; gap: 15px; justify-content: center; }
		.social-links a { color: white; text-decoration: none; font-size: 1.2em; }
	</style>
</head>
<body>

	<header>
		<h1>Cereal Board Suppliers</h1>
		<p>Your trusted source for quality cereals across Meru County and neighboring towns.</p>
	</header>

	<div class="container">
		<!-- About Us Section -->
		<section class="section" id="about-us">
			<h2>About Us</h2>
			<p>Welcome to Cereal Board Suppliers! We provide high-quality, reliable cereals across Meru county and the towns of Tharaka Nithi, Mwea, and Embu. Our mission is to ensure our customers enjoy safe, reliable products, and an excellent experience every time.</p>
		</section>

		<!-- Available Cereals Section -->
		<section class="section">
			<h3>Available Cereals</h3>
			<ul class="cereal-list">
				<li>Millet</li>
				<li>Sorghum</li>
				<li>Wheat</li>
				<li>Maize</li>
				<li>Rice</li>
			</ul>
		</section>

		<!-- Services Section -->
		<section class="section">
			<h3>Our Services</h3>
			<p>We offer the following services to our valued customers:</p>
			<ul>
				<li>Bulk cereal supply for businesses and institutions</li>
				<li>Individual cereal packs for households</li>
				<li>Custom orders and delivery options</li>
				<li>Customer support for inquiries and order tracking</li>
			</ul>
		</section>

		<!-- Testimonials Section -->
		<section class="section">
			<h3>What Our Customers Say</h3>
			<blockquote>
				<p>"Cereal Board Suppliers have been our trusted cereal source for years. Their quality and service are unmatched!" - Jane W.</p>
			</blockquote>
			<blockquote>
				<p>"Reliable, affordable, and top-notch cereals. Thank you, Cereal Board!" - Michael T.</p>
			</blockquote>
		</section>

		<!-- FAQ Section -->
		<section class="section">
			<h3>Frequently Asked Questions</h3>
			<h4>What payment methods do you accept?</h4>
			<p>We accept payments via mobile money transfer to our official number: 0740808068.</p>

			<h4>Do you offer delivery?</h4>
			<p>Yes, we offer delivery services across Meru County and neighboring towns. Delivery charges may apply based on the location.</p>

			<h4>How do I place an order?</h4>
			<p>You can place an order by filling out the form below and choosing your desired cereal selection.</p>
		</section>

		<!-- Order Form Section -->
		<section class="section">
			<h3>Order Form</h3>
			<form action="/submit-order" method="POST">
				<label for="cereal-name">Cereal Name:</label>
				<input type="text" id="cereal-name" name="cereal-name" required>

				<label for="user-email">Email:</label>
				<input type="email" id="user-email" name="user-email" required>

				<label for="phone-number">Phone Number:</label>
				<input type="tel" id="phone-number" name="phone-number" required>

				<label for="cereal">Choose a cereal:</label>
				<select id="cereal" name="cereal" required>
					<option value="Millet">Millet</option>
					<option value="Sorghum">Sorghum</option>
					<option value="Wheat">Wheat</option>
					<option value="Maize">Maize</option>
					<option value="Rice">Rice</option>
				</select>

				<input type="submit" value="Submit Order">
			</form>
		</section>

		<!-- Contact Us Section -->
		<section class="section" id="contact-us">
			<h3>Contact Us</h3>
			<p>For more information, feel free to reach out to us:</p>
			<p><strong>Phone:</strong> 0740808068</p>
			<p><strong>Email:</strong> support@cerealboardsuppliers.com</p>
			<p>We are here to answer all your cereal needs and inquiries.</p>
		</section>
	</div>

	<!-- Footer Section -->
	<footer>
		<div class="footer-links">
			<ul>
				<li><a href="#about-us" style="color: white;">About Us</a></li>
				<li><a href="#services" style="color: white;">Services</a></li>
				<li><a href="#contact-us" style="color: white;">Contact Us</a></li>
			</ul>
		</div>

		<div class="social-links">
			<a href="https://facebook.com" target="_blank">Facebook</a>
			<a href="https://twitter.com" target="_blank">Twitter</a>
			<a href="https://instagram.com" target="_blank">Instagram</a>
		</div>

		<p>&copy; 2024 Cereal Board Suppliers. All rights reserved.</p>
	</footer>
	
</body>
</html>



