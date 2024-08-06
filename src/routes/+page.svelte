<header class="header__flex">
	<h1>ロゴ</h1>
	<nav>
		<ul>
			<li>About</li>
			<li>Works</li>
			<li>Contact</li>
			<li>Diary</li>
		</ul>
	</nav>
</header>

<img src="src/assets/v2osk-1Z2niiBPg5A-unsplash.jpg" />

<section class="about">
	<div class="section_title">About</div>
	<div class="section_content"><p>〇〇な悩みを抱えていませんか？</p></div>
</section>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	ul {
		list-style: none;
	}
	.header__flex {
		display: flex;
		background-color: rgba(248, 208, 172, 0.864);
		height: 60px;
		align-items: center;
	}
	.header__flex nav {
		margin-left: auto;
	}
	.header__flex ul {
		display: flex;
	}
	.header__flex ul li {
		margin-left: 40px;
	}
	.image_container {
		height: 500px;
		width: 100%;
	}
	img {
		width: 100%;
	}

	.about {
		height: 500px;
	}
	.section_title {
		font-weight: bold;
	}
	.section_content {
		display: flex;
		justify-content: center;
	}
</style>
