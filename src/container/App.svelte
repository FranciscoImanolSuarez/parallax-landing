<script>
	import Header from '../components/Header.svelte';
	import Main from '../components/Main.svelte';
	import Footer from '../components/Footer.svelte';

</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
:global(*){
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

:global(body){
	font-family: 'Montserrat', sans-serif;
	background: #2f2254;
	color: #fff;
	font-size: 18px;
	line-height: 1.6;

}

:global(h1,h2,h3,h4,p){
	margin-bottom: 10px;
}

:global(a){
	text-decoration: none;
	color: #fff;

}

:global(ul){
		list-style: none;
}

:global(.btn){
	display: inline-block;
	border: 0;
	background: #f5c42f;
	color: #fff;
	border-radius: 20px;
	padding: 8px 30px;
	text-transform: uppercase;
	font-weight: bold;
	font-size: 16px;
	margin-top: 10px;
}

:global(.btn:hover){
		transform: scale(0.98);
}

:global(.primary-text){
		color: #2d2254;
}

:global(.secondary-text){
	color: #f5c42f;
}

:global(.section){
	position: relative;
	padding: 0 20px;
}




</style>

<div class="main">
	<Header />
	<Main />
	<Footer />
</div>
