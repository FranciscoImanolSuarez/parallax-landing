<script>
	// your script goes here		
</script>

<style>
.section-stream {
	min-height: 700px;
}

.section-stream h2 {
	font-size: 35px;
}

.section-stream .play {
	width: 27%;
	position: absolute;
	top: 100px;
	left: 50px;
}

.section-stream .content {
	position: absolute;
	width: 50%;
	top: 130px;
	right: 70px;
}

.section-stream .content > div, .section-grid > div {
	background: rgba(255, 255, 255, 0.1);
	padding: 20px;
	margin-bottom: 20px;
	border-radius: 10px;
}

/* Section Grid */
.section-grid {
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	grid-gap: 30px;
	text-align: center;
}

.section-grid p {
	color: #c5bbec ;
}

.section-grid .dot {
	font-size: 40px;
	padding-left: 2px;
}

.parallax {
  /* The image used */
  background-image: url("https://github.com/FranciscoImanolSuarez/parallax-landing/blob/master/public/images/bg2.png?raw=true");

  /* Set a specific height */
  height: 700px;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

</style>

<section class="section section-stream">
		<div class="parallax"></div>
		<img
				class="play"
				src="https://github.com/FranciscoImanolSuarez/parallax-landing/blob/master/public/images/play-button.png?raw=true"
				alt=""
			/>
			<div class="content rellax" data-rellax-speed="10">
				<div>
					<h2 class="secondary-text">Stream Everything</h2>
					<p>
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore et
						dicta consectetur incidunt omnis nam quis quidem nisi ipsa deserunt.
					</p>
				</div>
				<div>
					<h2 class="secondary-text">Short is the New Long</h2>
					<p>
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore et
						dicta consectetur incidunt omnis nam quis quidem nisi ipsa deserunt.
					</p>
				</div>
			</div>
		</section>

		<section class="section section-grid">
			<div>
				<i class="fas fa-video fa-3x secondary-text"></i>
				<h2>Watch<span class="secondary-text dot">.</span></h2>
				<p>
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore et
						dicta consectetur incidunt omnis nam quis quidem nisi ipsa deserunt.
				</p>
			</div>
			<div>
				<i class="fas fa-users fa-3x secondary-text"></i>
				<h2>Share<span class="secondary-text dot">.</span></h2>
				<p>
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore et
						dicta consectetur incidunt omnis nam quis quidem nisi ipsa deserunt.
				</p>
			</div>
			<div>
				<i class="fas fa-book fa-3x secondary-text"></i>
				<h2>Learn<span class="secondary-text dot">.</span></h2>
				<p>
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore et
						dicta consectetur incidunt omnis nam quis quidem nisi ipsa deserunt.
				</p>
			</div>
    </section>
