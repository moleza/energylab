
<header>
	<nav class="navbar navbar-expand-lg navbar-dark">
		<div class="container">
			<div class="d-flex flex-grow-1">
				<span class="w-100 d-lg-none d-block">
					<!-- hidden spacer to center brand on mobile --></span>
				<!-- svelte-ignore a11y-invalid-attribute -->
				<a class="navbar-brand" href="#">
					<img src="/navbar-logo.png" alt="logo" />
				</a>
				<div class="w-100 text-right">
					<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#energyNavbar">
						<i class="bi bi-list"></i>
					</button>
				</div>
			</div>
			<div class="collapse navbar-collapse flex-grow-1 text-right" id="energyNavbar">
				<ul class="navbar-nav ms-auto flex-nowrap">
					<li class="nav-item">
						<a href="/" class="nav-link">HOME</a>
					</li>
					<li class="nav-item">
						<!-- svelte-ignore a11y-invalid-attribute -->
						<a href="#" class="nav-link">EVENTS</a>
					</li>
					<li class="nav-item">
						<!-- svelte-ignore a11y-invalid-attribute -->
						<a href="#" class="nav-link">HOW IT WORKS</a>
					</li>
					<li class="nav-item">
						<!-- svelte-ignore a11y-invalid-attribute -->
						<a href="#" class="nav-link">PREVIOUS EVENTS</a>
					</li>
					<li class="nav-item">
						<!-- svelte-ignore a11y-invalid-attribute -->
						<a href="#" class="nav-link">LOGIN/REGISTER</a>
					</li>
				</ul>
			</div>
		</div>
	</nav>
	
</header>

<main>
	<slot />
</main>

<footer class="bg-black text-white-50 h-auto pt-2">
	Copyright © 2022 Energy Lab Athletic Company.
</footer>