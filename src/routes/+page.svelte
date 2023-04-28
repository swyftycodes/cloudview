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
		margin: 0.5rem;
		border: none;
		padding: 10px;
	}

	#message {
		margin: 0.5rem;
		border: none;
		padding: 10px;

		height: 100px;
		resize: none;
		font-family: Poppins, sans-serif;
		font-size: 14px;
	}

	#services {
		display: flex;
	}

	.service {
		text-align: center;
		flex: 1;
		background-color: #00000099;
		background-size: cover;
		background-blend-mode: darken;
		color: white;
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
</style>
