<template>
	<div class="container mx-auto bg-light mt-0">
		<header>
			<div class="container-fluid">
				<!-- NAV-BAR -->
				<nav class="navbar navbar-expand-md bg-dark navbar-dark fixed-top mb-5">
					<div class="container">
						<a class="navbar-brand text-uppercase fw-bold" href="/index.html">
							<span class="bg-primary bg-gradient p-1 rounded-3 text-light">John</span> Doe
						</a>
						<button
							class="navbar-toggler"
							type="button"
							data-bs-toggle="collapse"
							data-bs-target="#navbarNav"
							aria-controls="navbarNav"
							aria-expanded="false"
							aria-label="Toggle navigation"
						>
							<span class="navbar-toggler-icon"></span>
						</button>
						<div class="collapse navbar-collapse justify-content-end" id="navbarNav">
							<ul class="navbar-nav">
								<li class="nav-item active">
									<a class="nav-link" href="#johndoe">Qui suis-je ?</a>
								</li>
								<li class="nav-item">
									<a class="nav-link" href="#expertise">Expertises</a>
								</li>
								<li class="nav-item">
									<a class="nav-link" href="#portfolio">Portfolio</a>
								</li>
								<li class="nav-item">
									<a class="nav-link" href="#contact">Contact</a>
								</li>
							</ul>
						</div>
					</div>
				</nav>
				<!-- NAV-BAR -->
			</div>
		</header>
		<main>
			<!-- Header-top -->
			<section class="py-5 mt-5" id="johndoe">
				<div class="container">
					<div class="row align-items-center gy-4 gy-md-0 mt-5">
						<div class="col-12 col-md-6">
							<h1 class="fw-bold">Je suis John Doe Développeur et Designer Web</h1>
							<h2 class="fw-light">Bienvenue dans mon univers créatif</h2>
							<button class="mb-3 mt-3 btn btn-primary">Mon expertise Web</button>
						</div>
						<div class="col">
							<img src="../assets/img/portrait.jpg" alt="John Doe" width="100%" class="shadow" />
						</div>
					</div>
				</div>
			</section>
			<!-- Header-top -->
			<div id="expertise"></div>
			<section class="py-5 bg-light mt-5">
				<!-- Main-top -->
				<div class="container">
					<h2>Mon expertise</h2>
					<h3 class="fs-3 fs-md-2">Développement web et design</h3>

					<!-- Developpement -->
					<div class="row gy-4 mt-5 d-flex align-items-center">
						<div class="col-12 offset-md-1 col-md-7 mb-5 mb-md-0">
							<div class="bg-white p-3 shadow">
								<div class="row">
									<div class="col-5 col-sm-4 col-md-3 col-xl-2">
										<div class="d-flex justify-content-center">
											<p class="fw-bold m-0">Vue JS</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-75"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-5 col-sm-4 col-md-3 col-xl-2">
										<div class="d-flex justify-content-center">
											<p class="fw-bold m-0">SWIFT</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-50"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-5 col-sm-4 col-md-3 col-xl-2">
										<div class="d-flex justify-content-center">
											<p class="fw-bold m-0">JavaScript</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-75"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-5 col-sm-4 col-md-3 col-xl-2">
										<div class="d-flex justify-content-center">
											<p class="fw-bold m-0">HTML5</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-75"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="col-12 offset-1 col-md-4">
							<img src="../assets/img//code.jpg" alt="écran montrant du code php" width="100%" />
						</div>
					</div>
					<!-- Developpement -->

					<!-- Design -->
					<div class="row gy-4 mt-5 d-flex align-items-center">
						<div class="col-12 col-md-4">
							<img src="../assets/img/design.jpg" alt="écran montrant des designs" width="100%" />
						</div>
						<div class="col-12 offset-md-1 col-md-7 mt-5 mt-md-0">
							<div class="mb-3 p-3 bg-white shadow">
								<div class="row align-items-center">
									<div class="col-5 col-sm-4 col-lg-3 col-xl-2">
										<div class="d-flex align-items-center">
											<p class="fw-bold m-0">Video</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-75"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
								<div class="row align-items-center">
									<div class="col-5 col-sm-4 col-lg-3 col-xl-2">
										<div class="d-flex align-items-center">
											<p class="fw-bold m-0">Design UX</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-75"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
								<div class="row align-items-center">
									<div class="col-5 col-sm-4 col-lg-3 col-xl-2">
										<div class="d-flex align-items-center">
											<p class="fw-bold m-0">Figma</p>
										</div>
									</div>
									<div class="col">
										<div class="progress">
											<div
												class="progress-bar w-75"
												aria-valuenow="75"
												aria-valuemin="0"
												aria-valuemax="100"
											></div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- Design -->
				</div>
				<!-- Main-top -->
			</section>
			<div id="portfolio" class="mb-3"></div>
			<section class="py-5">
				<!-- Main-middle -->
				<div class="container">
					<h2>Mon portfolio</h2>
					<h3 class="fs-3 fs-md-2">Projets perso et pro</h3>
					<div class="row gy-4 mt-4">
						<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">
							<!-- Cart -->
							<div class="card shadow mb-3">
								<img src="https://picsum.photos/300/150?random=1" class="card-img-top" alt="..." />
								<div class="card-body">
									<h5 class="card-title">Projet 1</h5>
									<p class="card-text">
										Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sollicitudin.
									</p>
									<a class="btn btn-primary" data-bs-toggle="offcanvas" data-bs-target="#infoProjet1"
										>En savoir plus</a
									>
									<div
										class="offcanvas offcanvas-bottom h-75"
										tabindex="-1"
										id="infoProjet1"
										aria-labelledby="titreProjet1"
									>
										<div class="offcanvas-header">
											<h5 class="offcanvas-title" id="titleProjet1">Projet 1</h5>
											<button
												type="button"
												class="btn-close text-reset"
												data-bs-dismiss="offcanvas"
												aria-label="Close"
											></button>
										</div>
										<div class="offcanvas-body small">
											<div id="carouselProjet1" class="carousel slide" data-bs-ride="carousel">
												<div class="carousel-indicators">
													<button
														type="button"
														data-bs-target="#carouselProjet1"
														data-bs-slide-to="0"
														class="active"
														aria-current="true"
														aria-label="Slide 1"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet1"
														data-bs-slide-to="1"
														aria-label="Slide 2"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet1"
														data-bs-slide-to="2"
														aria-label="Slide 3"
													></button>
												</div>
												<div class="carousel-inner">
													<div class="carousel-item active" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=1"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>First slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=2"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Second slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=3"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Third slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
												</div>
												<button
													class="carousel-control-prev"
													type="button"
													data-bs-target="#carouselProjet1"
													data-bs-slide="prev"
												>
													<span class="carousel-control-prev-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Previous</span>
												</button>
												<button
													class="carousel-control-next"
													type="button"
													data-bs-target="#carouselProjet1"
													data-bs-slide="next"
												>
													<span class="carousel-control-next-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Next</span>
												</button>
											</div>
										</div>
									</div>
								</div>
							</div>
							<!-- Cart -->
						</div>
						<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">
							<!-- Cart -->
							<div class="card shadow mb-3">
								<img src="https://picsum.photos/300/150?random=2" class="card-img-top" alt="..." />
								<div class="card-body">
									<h5 class="card-title">Projet 2</h5>
									<p class="card-text">
										Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sollicitudin.
									</p>
									<a class="btn btn-primary" data-bs-toggle="offcanvas" data-bs-target="#infoProjet2"
										>En savoir plus</a
									>
									<div
										class="offcanvas offcanvas-bottom h-75"
										tabindex="-1"
										id="infoProjet2"
										aria-labelledby="titreProjet2"
									>
										<div class="offcanvas-header">
											<h5 class="offcanvas-title" id="titleProjet2">Projet 2</h5>
											<button
												type="button"
												class="btn-close text-reset"
												data-bs-dismiss="offcanvas"
												aria-label="Close"
											></button>
										</div>
										<div class="offcanvas-body small">
											<div id="carouselProjet2" class="carousel slide" data-bs-ride="carousel">
												<div class="carousel-indicators">
													<button
														type="button"
														data-bs-target="#carouselProjet2"
														data-bs-slide-to="0"
														class="active"
														aria-current="true"
														aria-label="Slide 1"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet2"
														data-bs-slide-to="1"
														aria-label="Slide 2"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet2"
														data-bs-slide-to="2"
														aria-label="Slide 3"
													></button>
												</div>
												<div class="carousel-inner">
													<div class="carousel-item active" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=4"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>First slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=5"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Second slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=6"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Third slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
												</div>
												<button
													class="carousel-control-prev"
													type="button"
													data-bs-target="#carouselProjet2"
													data-bs-slide="prev"
												>
													<span class="carousel-control-prev-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Previous</span>
												</button>
												<button
													class="carousel-control-next"
													type="button"
													data-bs-target="#carouselProjet2"
													data-bs-slide="next"
												>
													<span class="carousel-control-next-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Next</span>
												</button>
											</div>
										</div>
									</div>
								</div>
							</div>
							<!-- Cart -->
						</div>
						<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">
							<!-- Cart -->
							<div class="card shadow mb-3">
								<img src="https://picsum.photos/300/150?random=3" class="card-img-top" alt="..." />
								<div class="card-body">
									<h5 class="card-title">Projet 3</h5>
									<p class="card-text">
										Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sollicitudin.
									</p>
									<a class="btn btn-primary" data-bs-toggle="offcanvas" data-bs-target="#infoProjet3"
										>En savoir plus</a
									>
									<div
										class="offcanvas offcanvas-bottom h-75"
										tabindex="-1"
										id="infoProjet3"
										aria-labelledby="titreProjet3"
									>
										<div class="offcanvas-header">
											<h5 class="offcanvas-title" id="titleProjet3">Projet 3</h5>
											<button
												type="button"
												class="btn-close text-reset"
												data-bs-dismiss="offcanvas"
												aria-label="Close"
											></button>
										</div>
										<div class="offcanvas-body small">
											<div id="carouselProjet3" class="carousel slide" data-bs-ride="carousel">
												<div class="carousel-indicators">
													<button
														type="button"
														data-bs-target="#carouselProjet3"
														data-bs-slide-to="0"
														class="active"
														aria-current="true"
														aria-label="Slide 1"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet3"
														data-bs-slide-to="1"
														aria-label="Slide 2"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet3"
														data-bs-slide-to="2"
														aria-label="Slide 3"
													></button>
												</div>
												<div class="carousel-inner">
													<div class="carousel-item active" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=7"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>First slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=8"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Second slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=9"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Third slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
												</div>
												<button
													class="carousel-control-prev"
													type="button"
													data-bs-target="#carouselProjet3"
													data-bs-slide="prev"
												>
													<span class="carousel-control-prev-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Previous</span>
												</button>
												<button
													class="carousel-control-next"
													type="button"
													data-bs-target="#carouselProjet3"
													data-bs-slide="next"
												>
													<span class="carousel-control-next-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Next</span>
												</button>
											</div>
										</div>
									</div>
								</div>
							</div>
							<!-- Cart -->
						</div>
						<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">
							<!-- Cart -->
							<div class="card shadow mb-3">
								<img src="https://picsum.photos/300/150?random=4" class="card-img-top" alt="..." />
								<div class="card-body">
									<h5 class="card-title">Projet 4</h5>
									<p class="card-text">
										Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sollicitudin.
									</p>
									<a class="btn btn-primary" data-bs-toggle="offcanvas" data-bs-target="#infoProjet4"
										>En savoir plus</a
									>
									<div
										class="offcanvas offcanvas-bottom h-75"
										tabindex="-1"
										id="infoProjet4"
										aria-labelledby="titreProjet1"
									>
										<div class="offcanvas-header">
											<h5 class="offcanvas-title" id="titleProjet4">Projet 4</h5>
											<button
												type="button"
												class="btn-close text-reset"
												data-bs-dismiss="offcanvas"
												aria-label="Close"
											></button>
										</div>
										<div class="offcanvas-body small">
											<div id="carouselProjet4" class="carousel slide" data-bs-ride="carousel">
												<div class="carousel-indicators">
													<button
														type="button"
														data-bs-target="#carouselProjet4"
														data-bs-slide-to="0"
														class="active"
														aria-current="true"
														aria-label="Slide 1"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet4"
														data-bs-slide-to="1"
														aria-label="Slide 2"
													></button>
													<button
														type="button"
														data-bs-target="#carouselProjet4"
														data-bs-slide-to="2"
														aria-label="Slide 3"
													></button>
												</div>
												<div class="carousel-inner">
													<div class="carousel-item active" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=10"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>First slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=11"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Second slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
													<div class="carousel-item" data-bs-interval="2000">
														<img
															src="https://picsum.photos/1920/1080?random=12"
															class="d-block w-100"
															alt="..."
														/>
														<div class="carousel-caption d-none d-md-block">
															<h5>Third slide label</h5>
															<p>
																Lorem, ipsum dolor sit amet consectetur adipisicing
																elit. Delectus quam, itaque id corporis distinctio
																fugit.
															</p>
														</div>
													</div>
												</div>
												<button
													class="carousel-control-prev"
													type="button"
													data-bs-target="#carouselProjet4"
													data-bs-slide="prev"
												>
													<span class="carousel-control-prev-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Previous</span>
												</button>
												<button
													class="carousel-control-next"
													type="button"
													data-bs-target="#carouselProjet4"
													data-bs-slide="next"
												>
													<span class="carousel-control-next-icon" aria-hidden="true"></span>
													<span class="visually-hidden">Next</span>
												</button>
											</div>
										</div>
									</div>
								</div>
							</div>
							<!-- Cart -->
						</div>
					</div>
				</div>
				<!-- Main-middle -->
			</section>
			<div id="contact" class="mb-2"></div>
			<section class="py-5 bg-light">
				<!-- Main-bottom -->
				<div class="container">
					<h2>Un projet de création web ?</h2>
					<h3 class="fs-3 fs-md-2">Allons en discuter autour d'un café</h3>

					<div class="row gy-4 mt-5 align-items-center">
						<div class="col-12 col-md-5 mb-3">
							<img src="../assets/img/grab-a-coffee.jpg" alt="Image d'une tasse de café" width="100%" />
						</div>
						<div class="col-12 offset-md-1 col-md-6">
							<form action="" class="row text-start">
								<div class="col-6 mb-3">
									<label for="prenom" class="form-label">Prenom</label>
									<input type="text " class="form-control" name="prenom" id="prenom" />
								</div>
								<div class="col-6 mb-3">
									<label for="nom" class="form-label">Nom</label>
									<input type="text " class="form-control" name="nom" id="nom" />
								</div>
								<div class="col-12 mb-3">
									<label for="email" class="form-label">Email</label>
									<input type="text " class="form-control" name="email" id="email" />
								</div>
								<div class="col-12 mb-3">
									<label for="message" class="form-label">Message</label>
									<textarea type="text " class="form-control" name="message" id="message" />
								</div>
								<div class="col-12 mb-3">
									<button type="submit" class="btn btn-primary w-100" title="Envoyer le formulaire">
										Envoyer
									</button>
								</div>
							</form>
						</div>
					</div>
				</div>
				<!-- Main-bottom -->
			</section>
		</main>
		<footer class="border-top">
			<div class="container py-5">
				<div class="row">
					<!-- Mention legal -->
					<div class="col-12 col-md-6">
						<!-- Button trigger modal -->
						<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#mentions">
							Mentions légales
						</button>

						<!-- Modal -->
						<div
							class="modal fade"
							id="mentions"
							tabindex="-1"
							aria-labelledby="exampleModalLabel"
							aria-hidden="true"
						>
							<div class="modal-dialog modal-dialog-centered mx-auto">
								<div class="modal-content">
									<div class="modal-header">
										<h5 class="modal-title" id="mentions">Mentions légales</h5>
										<button
											type="button"
											class="btn-close"
											data-bs-dismiss="modal"
											aria-label="Close"
										></button>
									</div>
									<div class="modal-body">
										Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo, dolorum
										quibusdam! Aut, blanditiis quasi? Suscipit unde minima quisquam atque cum
										voluptas obcaecati, veritatis magni? Impedit nisi cum perspiciatis! Unde,
										libero.
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- Mention legal -->
					<!-- <div class="col-12 col-md-4">
						<div class="bg-secondary py-5 mt-3 mt-md-0"></div>
					</div> -->
					<div class="col-12 col-md-6 text-md-end">
						<ul class="list-inline">
							<li class="list-inline-item mx-2">
								<svg
									xmlns="http://www.w3.org/2000/svg"
									width="16"
									height="16"
									fill="currentColor"
									class="bi bi-linkedin"
									viewBox="0 0 16 16"
								>
									<path
										d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"
									/>
								</svg>
							</li>

							<li class="list-inline-item mx-2">
								<svg
									xmlns="http://www.w3.org/2000/svg"
									width="16"
									height="16"
									fill="currentColor"
									class="bi bi-instagram"
									viewBox="0 0 16 16"
								>
									<path
										d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"
									/>
								</svg>
							</li>
							<li class="list-inline-item mx-2">
								<svg
									xmlns="http://www.w3.org/2000/svg"
									width="16"
									height="16"
									fill="currentColor"
									class="bi bi-twitter"
									viewBox="0 0 16 16"
								>
									<path
										d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"
									/>
								</svg>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</footer>
	</div>
</template>

<script>
export default {
	data() {
		return {
			value: 33.333333333,
			max: 50,
		};
	},
	name: "HelloWorld",
	props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* .portrait img {
	width: 400px;
} */
.gauche {
	display: flex;
	justify-content: start;
	padding-right: 0;
	padding-left: 0;
}
.droite {
	display: flex;
	justify-content: end;
	padding-right: 0;
	padding-left: 0;
}

.shadow {
	box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
</style>
