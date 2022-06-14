<script>
	import 'papercss/dist/paper.min.css'
	import {Navbar,Article,Card, Form, Input, Button } from 'spaper';
</script>

<main>
	<!--https://www.getpapercss.com/docs/utilities/-->
	<div class="container">

		<Navbar border={false}>
			<h3 slot="brand">
				<a href="https://keevol.cn">KEEVOL持续进化</a>
			</h3>
			<!--
            <ul class="inline">
              <li><a href="#">Documentation</a></li>
              <li><a href="#">About</a></li>
              <li>
                <Button>Github</Button>
              </li>
            </ul>
            -->
		</Navbar>

		<div class="row flex-center flex-spaces margin">
			<div class="col lg-6 align-middle">
				<Form>
					<Input placeholder="email" class="margin-bottom-small" />
					<Input placeholder="password" type="password" />

					<Button type="secondary" class="margin-top-small">
						Sign in
					</Button>
				</Form>
			</div>
			<div class="col lg-6">
				<Card title="My awesome Paper card!"
					  subTitle="nice looking subtitle"
					  imagePlacement="bottom"
					  image="https://picsum.photos/768">
					Card Content
				</Card>
			</div>
		</div>

		<div class="row">
			<div class="col padding-none"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAACWAAAAAYAQMAAABEalRSAAAABlBMVEX///9TU1NYzE1OAAAAAXRSTlMAQObYZgAAAOtJREFUeF7tljEKwzAMRb/J0CWgI/QKOYAh1+pUcjQfpUfw2MFEHVyDQSQmQUNM9AYNcobnh4egU+YVqhAvZSpgsfolPnSv5d0nz3vHslgUdK81RLzyvHcsi+WBNxQh4Ln8pw4Wi7skAg9mXgHMrEACXJnbHIllsbqGAtwXhnYswzFzwPWxWEPc2CexoobkHM4ZpD6s2loWiyIEEwCChIomMiMEHqgP573C9eHkc5VLWh3XsljnGVoLWVl+31bp38piTVVuihtPOAm9kcRLbrFjEvqwamtZLK5eI8sSan9rXEK0LcNFrY5oWawf59S7YSRD7eMAAAAASUVORK5CYII=" style="max-width: 100%;height: auto; border:none;" alt="hr line"/></div>
		</div>
		<div class="row flex-center">
			<div class="col padding-none">
				©keevol.com, All Rights Reserved.
			</div>
		</div>
	</div>
</main>


