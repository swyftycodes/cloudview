<div id="main">
	<div id="text">
		<h1>We are committed to making IT work for your business</h1>
		<p>We welcome all sorts of enquiries in the field of IT solutions and business consulting services.</p>
		<button id="learn-more">
			Learn More
			<img src="down.svg" width="11px" alt="">
		</button>
	</div>
	<form id="form">
		<h1>Request Callback</h1>
		<p>Please complete this form</p>
		<input type="text" placeholder="Name">
		<input type="text" placeholder="Email">
		<input type="text" placeholder="Contact No">
		<input type="text" placeholder="Purpose Of Contact">
		<textarea placeholder="Your Message..." id="message"></textarea>
		<button id="submit-btn" type="submit">Submit</button>
	</form>
</div>

<div id="services">
	<div id="security" class="service">
		<h2>Security solutions</h2>
		<p>We help your business with our full-spectrum scanning, testing, auditing, compliance and protection solutions for your IT system and web applications.</p>
		<button class="contact">Contact Us</button>
	</div>
	<div id="outsourcing" class="service">
		<h2>IT outsourcing</h2>
		<p>We provide on-site security measurement services, as well as firewall configuration, log audit, patches update, antivirus and anti-spam solution.</p>
		<button class="contact">Contact Us</button>
	</div>
	<div id="consultancy" class="service">
		<h2>Consultancy</h2>
		<p>Members of our professional teams are multi-skilled and experienced consultants, system analysts and project managers.</p>
		<button class="contact">Contact Us</button>
	</div>
</div>

<div id="why">
	<div id="why-text">
		<div>
			<h1>Why Choose Us</h1>
			<hr>
			<p>We are specialized in providing system analysis, consultancy and infrastructure design. We offer services and solutions with expert IT know-how.</p>
		</div>

	</div>
	<div id="reasons">
		<div id="safe" class="reason">
			<img src="safe.jpg" alt="could not load image">
			<h1>Safe & Secure</h1>
			<p>We care for your system safety as well as operation efficiency</p>
		</div>
		<div id="support" class="reason">
			<img src="support.jpg" alt="could not load image">
			<h1>24x7 Support</h1>
			<p>We are here to solve your IT challenges. 24 hours a day, 7 days a week.</p>
		</div>
		<div id="cost" class="reason">
			<img src="cost.jpg" alt="could not load image">
			<h1>Low Cost</h1>
			<p>We provide services with competitive prices and payment plans.</p>
		</div>
	</div>
</div>

<footer id="footer">
	<div id="footer-1">
		<p>Copyright © 2023 Cloud View Technology</p>
		<p>Powered by Cloud View Technology</p>
	</div>
	<div id="footer-2">
		<div>
			<h3>location</h3>
			<hr>
			<p>Rm J3, 11/F, Phase 2 Kaiser Estate, 51 Man Yue Street, Hung Hom, KLN, Hong Kong</p>
		</div>
		<div>
			<h3>Email</h3>
			<hr>
			<p>info@cloudviewhk.com</p>
		</div>
		<div>
			<h3>Phone</h3>
			<hr>
			<p>+852 1234 5678, +852 8765 4321</p>
		</div>
		<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3691.1800879510524!2d114.18638221083991!3d22.30902794249435!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x340400df06a4c729%3A0x90801fb17af3b209!2s51%20Man%20Yue%20St%2C%20Hung%20Hom%2C%20Hong%20Kong!5e0!3m2!1sen!2sau!4v1683630961426!5m2!1sen!2sau" id="map" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
	</div>
</footer>

<style>
	#main {
		background-color: #1c72a8;
		background-image: url('plug.jpg');
		background-size: cover;
		background-blend-mode: screen;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-evenly;
		color: white;
	}

	#text {
		margin-top: 10rem;
		margin-bottom: 10rem;
		width: 50%;
		align-items: center;
	}

	#learn-more {
		background-color: white;
		border: none;
		color: #1c72a8;
		padding: 10px;
		margin-top: 15px;
		font-size: 16px;
		transition-duration: 0.2s;
	}

	#learn-more:hover {
		background-color: lightgray;
	}

	#form {
		display: flex;
		flex-direction: column;
		margin-top: 10rem;
		margin-bottom: 10rem;
		background-color: whitesmoke;
		color: black;
		padding: 2rem;
	}

	#form input {
		border: none;
		padding: 10px;
		margin-top: 5px;
		margin-bottom: 5px;
	}

	#message {
		border: none;
		padding: 10px;
		margin-top: 5px;
		margin-bottom: 5px;
		height: 100px;
		resize: none;
		font-family: Poppins, sans-serif;
		font-size: 14px;
	}

	#submit-btn {
		background-color: lightgray;
		border: none;
		height: 50px;
		font-size: 15px;
		margin-top: 5px;
	}

	#services {
		display: flex;
		flex-wrap: wrap;
	}

	.service {
		text-align: center;
		flex: 1;
		background-color: #00000099;
		background-size: cover;
		background-blend-mode: darken;
		color: white;
		padding: 50px;
	}

	#security {
		background-image: url('security.jpg');
	}

	#outsourcing {
		background-image: url('outsourcing.jpg');
	}

	#consultancy {
		background-image: url('consultancy.jpg');
	}

	.contact {
		background-color: white;
		border: none;
		color: #1c72a8;
		padding: 10px;
		margin-top: 15px;
		font-size: 16px;
	}
	
	#why {
		display: flex;
		padding: 20px;
		flex-wrap: wrap;
		margin-top: 50px;
		margin-bottom: 50px;
	}

	#why-text {
		display: flex;
		align-items: center;
	}

	#reasons {
		margin-left: 10px;
		display: flex;
		justify-content: space-evenly;
		align-content: center;
		flex: 1;
	}

	.reason {
		text-align: center;
		margin-left: 20px;
		margin-right: 20px;
		background-size: cover;
		color: white;
		background-color: #00000099;
		background-blend-mode: darken;
		padding: 50px 10px 50px 10px;
	}

	#safe {
		background-image: url('security.jpg');
	}

	#support {
		background-image: url('outsourcing.jpg');
	}

	#cost {
		background-image: url('consultancy.jpg');
	}
	
	#footer {
		color: white;
		background-color: #203444;
		padding: 10px 30px 10px 30px;
	}

	#footer-1 {
		display: flex;
		justify-content: space-between;
	}

	#footer-2 {
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
		gap: 40px;
	}

	#map {
		flex: 1;
	}
</style>
