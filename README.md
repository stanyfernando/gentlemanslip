<!DOCTYPE html>
<html>
<head>
	<title>My Website</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="https://fonts.googleapis.com/css?family=Playfair+Display:400,700&display=swap" rel="stylesheet">
<style>
	body {
		font-family: "Playfair Display", serif;
		max-width: 800px;
		margin: 0 auto;
		color: #FFFFFF;
		background-color: #000000;
		text-align: justify;
	}
	.container {
		display: flex;
		align-items: center;
		justify-content: center;
		margin-top: 50px;
	}
	.text-container {
		width: 77%;
		max-width: 600px;
		margin-left: 20px;
	}
	.img-container {
		width: 55%;
		max-width: 400px;
		margin-right: 20px;
		text-align: center;
	}
	.img-container img {
		width: 100%;
		margin: 0;
	}
	.menu {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		margin-top: 20px;
	}
	.menu a {
		color: #FFFFFF;
		margin: 0 10px;
		font-size: 18px;
		font-weight: normal;
		text-decoration: none;
	}
	.menu a:hover {
		text-decoration: underline;
	}
	@media (max-width: 480px) {
  .container {
    flex-direction: column;
    margin-top: 30px;
  }
  .text-container {
    width: 100%;
    max-width: 75%;
    margin: 20px 0;
  }
  .img-container {
    width: 60%;
    max-width: 100%;
    margin: 0;
  }
  .menu {
    flex-direction: column;
    align-items: center;
  }
  .menu a {
    margin: 15px 0;
  }
}

</style>

</head>
<body>
	<div class="container">
		<div class="img-container">
			<img src="https://i.ibb.co/kS85Nkd/with-frame.jpg" alt="i write">
		</div>
		<div class="text-container">
			<p>Draped in mystery and cloaked in shadows, gentlemanslip's poetry draws inspiration from the gothic literature of writers like edgar allan poe and neil gaiman, and from the haunting works of gothic poets such as john keats, christina rossetti, and samuel taylor coleridge. his works serve as a reflection of his personal struggles with mental health, providing a way for him to express the unspeakable horrors that lurked within him. his verses are a journey into the abyss of the soul, exploring the darker corners of human nature.</p>
			<p>gentlemanslip's poetry is both morose and tenebrous, influenced by the works of charles baudelaire, william blake, emily bronte, anne rice, h.p. lovecraft, algernon blackwood, arthur machen, and nathaniel hawthorne. amidst the pitch-black abyss, his poetry reveals that even in the depths of despair, there is the promise of enlightenment and self-realization. like a ray of light piercing through the darkness, his words beckon readers to embrace their inner demons and confront the shadows that lurk within. for within the macabre and melancholic lies the key to unlock the mysteries of the human soul, and the potential for rebirth and transcendence.</p>
		</div>
	</div>
</body>
	<footer>
  <nav>
    <ul class="menu">
      <li><a href="https://www.instagram.com/gentlemanslip/" target="_blank">poems</a></li>
      <li><span>|</span></li>
      <li><a href="https://www.tiktok.com/@gentlemanslip" target="_blank">tiktok</a></li>
      <li><span>|</span></li>
      <li>
        <a href="#">Playlist</a>
        <ul class="sub-menu">
          <li><a href="https://open.spotify.com/playlist/7E3sG0PY7MfQXIMZCueqmT?si=4cd52590cb3e489d" target="_blank">from instagram</a></li>
          <li><a href="https://open.spotify.com/playlist/0OEjTE05Ri1YtLlzaBny4H?si=077250f1812d4fae" target="_blank">from tikTok</a></li>
          <li><a href="https://open.spotify.com/playlist/6k6G9O7fScXsjq8YAwu2Ku?si=5394d7c536374e59" target="_blank">inspired by</a></li>
        </ul>
      </li>
      <li><span>|</span></li>
      <li><a href="https://linktr.ee/gentlemanslip" target="_blank">for more</a></li>
    </ul>
  </nav>
</footer>
<style>
  footer {
    background-color: #000000;
    text-align: center;
    padding: 20px;
  }
  
  .menu {
    display: inline-block;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  .menu > li {
    display: inline-block;
    margin: 0 10px;
    position: relative;
  }
  
  .menu > li:first-child:before {
    display: none;
  }
  
  .menu a {
    color: #FFFFFF;
    font-size: 12px;
    font-family: 'Libre Caslon Display', serif;
    text-decoration: none;
    text-transform: lowercase;
    letter-spacing: 1px;
    padding: 5px 10px;
  }
  
  .menu > li > span {
    color: #fff;
    font-size: 12px;
    font-family: 'Libre Caslon Display', serif;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin: 0 5px;
  }
  
  .sub-menu {
    display: none;
    position: absolute;
    left: 50%;
    top: 100%;
    transform: translateX(-50%);
    background-color: #fff;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    min-width: 200px;
    z-index: 1;
  }
  
  .sub-menu li {
    display: block;
    text-align: left;
  }
  
  .menu li:hover .sub-menu {
    display: block;
  }
  
  .sub-menu a {
    font-size: 12px;
    font-family: 'Roboto', sans-serif;
    color: #000;
    padding: 10px;
    text-decoration: none;
    display: block;
    text-transform: lowercase;
  }
</style>
</html>
