---
title: Formation AngularJS
template: index.html
---

<div class="js-sticky">
	<header class="header" role="banner" id="top">
		<div class="wrap cf">
			<div class="logo">
				<img src="img/logo.png" alt="{{ site }}" />
			</div>
			<nav class="wrapper-nav-main">
				<ul class="nav nav-main">
					<li class="lnk-home"><a href="index.html"><span>Accueil</span></a></li>
				<li class="current">
						<a href="services.html">Services</a>
						<ul class="nav nav-sub">
							<li><a href="services.html#conseil">Conseil</a></li>
							<li><a href="services.html#developpement">Développement</a></li>
							<li><a href="formationNodeJS.html">Formation Node.js</a></li>
							<li><a href="formationAngularJS.html">Formation AngularJS</a></li>
							<li><a href="bootcamp.html">BootCamp</a></li>
						</ul>
					</li>
					<li>
						<a href="technologies.html">Technologies</a>
						<ul class="nav nav-sub">
							<li><a href="#nodejs">Node.js</a></li>
							<li><a href="#angularjs">AngularJS</a></li>
						</ul>
					</li>
					<li><a href="references.html">Références</a></li>
					<li>
						<a href="societe.html">Société</a>
						<ul class="nav nav-sub">
							<li><a href="#equipe">Équipe</a></li>
							<li><a href="#philosophie">Philosophie</a></li>
						</ul>
					</li>
					<li><a href="contact.html">Contact</a></li>
				</ul>
			</nav>
		</div>
	</header>
</div>

<section class="banner">
	<div class="wrap cf">
		<div class="inner">
			<h1 class="page-title">Formation AngularJS</h1>
			<div class="banner-text">
				<p>3 jours pour découvrir et comprendre le framework AngularJS.<br>
				Stage pratique, magistral et didactique, pour devenir autonome.</p>
			</div>
		</div>
	</div>
</section>

<div class="techno-logo">
	<div class="wrap cf">
		<div class="inner">
			<h3 style="font-size:2em;">
				<img src="img/logo-angularjs.png" alt="Node.js" style="width:100px;float:right;">
				Présentation
			</h3>
		</div>
	</div>
</div>

<section class="section">
	<div class="wrap cf">
		<div class="inner">
			<div class="techno-col content cf">
				<h3 class="title-second">Objectifs :</h3>
				<p>À l'issue de cette formation AngularJS, les participants seront en mesure de :</p>
				<ul><li>Appréhender la philosophie et le fonctionnement du framework AngularJS,</li>
					<li>Développer une application Web avec AngularJS,</li>
					<li>Maîtriser les impacts du choix d'une architecture incluant une application web riche.</li>
					</ul>
				<h3 class="title-second">Méthode pédagogique :</h3>
				<p>Alternance (50-50%) de cours magistraux et de travaux pratiques (live coding) sur machine individuelle. Le stage se déroule autour de la réalisation d'une application simple et fonctionnelle, permettant la mise en application concrète des concepts abordés. Un support de cours est remis à chaque participant au format papier et PDF.</p>
				<h3 class="title-second">Public :</h3>
				<ul><li>Chefs de projet Web,</li>
					<li>Architectes techniques,</li>
					<li>Développeurs front-end.</li>
					</ul>
				<p>Connaissance de HTML, CSS et bon niveau JavaScript. Les notions fondamentales seront abordées en rappels.</p>
			</div>

			<div class="techno-col content last cf">
				<h3 class="title-second"> Au sommaire :</h3>
				<ul><li>1<sup>er</sup> jour : Rappels & mise en route - Une application web sans manipuler le DOM - Travaux Pratiques - Tests et debug.</li>
					<li>2<sup>ème</sup> jour : Design Patterns - Travaux Pratiques - Refactoring - Test d'un service AngularJS.</li>
					<li>3<sup>ème</sup> jour : Directives - Travaux Pratiques - Trucs & astuces, Bonnes pratiques, Perspectives.</li>
					</ul>
				<h3 class="title-second">Tarifs :</h3>
				<ul>Formule <strong>Inter-entreprises :</strong>
					<li>1665 € HT / stagiaire,</li>
					<li>Prestation réalisée par nos soins en partenariat avec</li>
					<a href="http://clever-institut.com/formation/formation-angular-js"><img src="img/logCleverInstitut180x80.png"/></a>
				</ul>
				<ul>Formule <strong>Intra-entreprise :</strong>
					<li>Devis personnalisé sur demande,</li>
					<li>6 stagiaires maximum / session,</li>
					<li>Accueil possible dans vos locaux.</li>
				</ul>
				<a href="contact.html" class="btn">Contactez-nous</a>
			</div>
		</div>
	</div>
</section>

<div class="techno-logo">
	<div class="wrap cf">
		<div class="inner">
			<h3 style="font-size:2em;">
				<img src="img/logo-angularjs.png" alt="Node.js" style="width:100px;float:right;">
				Programme de la 1<sup>ère</sup> journée :
			</h3>
		</div>
	</div>
</div>
<section class="section">
	<div class="wrap cf">
		<div class="inner">
			<div class="techno-col content cf">
				<ul><strong>Rappels & mise en route :</strong>
					<li>Rappels sur JavaScript : prototype, portée des variables, fonctions, contextes.</li>
					<li>Rappels HTML5 : balises sémantiques, forms.</li>
					<li>Présentation du design pattern MVVM.</li>
					<li>Définition d'une application "single page".</li>
					<li>Déclaratif vs impératif.</li>
					<li>Installation d'un environnement de travail : node.js, éditeur, navigateur.</li>
					</ul>
				<ul><strong>Une application web sans manipuler le DOM :</strong>
					<li>Data binding bi-directionnel.</li>
					<li>La gestion des vues et le moteur de template.</li>
					<li>Qu'est-ce qu'une expression AngularJS  ?</li>
					<li>Définition d'un contrôleur.</li>
					<li>Association vue et contrôleur.</li>
					<li>Comprendre les contextes AngularJS ($scope).</li>
					<li>Appréhender les événements utilisateurs.</li>
					<li>Formulaire : interaction et validation.</li>
					<li>Utilisation des filtres (dans la vue, dans le contrôleur et combinaison).</li>
					<li>Écriture d'un filtre.</li>
			</div>
			<div class="techno-col content last cf">
				<ul><strong>Travaux Pratiques :</strong>
					<li>Présentation de l'application fil rouge : ngDoodle.</li>
					<li>Création d'un évenement.</li>
					<li>Noter ses disponibilités.</li>
					</ul>
				<ul><strong>Test et debug d'une application AngularJS :</strong>
					<li>Environnement de test.</li>
					<li>Choix d'un framework de test.</li>
					<li>Tests unitaires et karma.</li>
					<li>Batarang : voir fonctionner AngularJS depuis le navigateur.</li>
					</ul>
			</div>
		</div>
	</div>
</section>

<div class="techno-logo">
	<div class="wrap cf">
		<div class="inner">
			<h3 style="font-size:2em;">
				<img src="img/logo-angularjs.png" alt="Node.js" style="width:100px;float:right;">
				Programme de la 2<sup>ème</sup> journée :
			</h3>
		</div>
	</div>
</div>
<section class="section">
	<div class="wrap cf">
		<div class="inner">
			<div class="techno-col content cf">
				<ul><strong>Design Patterns appliqués à une application web :</strong>
					<li>Notion de routing.</li>
					<li>Configuration avec $routeProvider.</li>
					<li>Route et gestion de l'historique de navigation.</li>
					<li>Initialisation avant routage.</li>
					<li>Découplage grâce aux services.</li>
					<li>Injection de dépendances.</li>
					<li>Présentation ou rappel sur les promesses.</li>
					<li>Les promesses avec AngularJS.</li>
					<li>Des services "standard" $http $resource : utilisation d'une API REST.</li>
					<li>Créer ses propres services : plusieurs façon d'y arriver.</li>
					</ul>
			</div>
			<div class="techno-col content last cf">
				<ul><strong>Travaux Pratiques :</strong>
					<li>Re-Organisation de notre application (Refactoring time).</li>
					<li>Création, utilisation et affichage.</li>
					<li>Création d'un service.</li>
					<li>Communication avec un serveur via une API REST.</li>
					</ul>
				<ul><strong>Découpler pour mieux tester :</strong>
					<li>Test d'un service AngularJS.</li>
					<li>Simuler le résultat d'une requête http.</li>
					</ul>
			</div>
		</div>
	</div>
</section>

<div class="techno-logo">
	<div class="wrap cf">
		<div class="inner">
			<h3 style="font-size:2em;">
				<img src="img/logo-angularjs.png" alt="Node.js" style="width:100px;float:right;">
				Programme de la 3<sup>ème</sup> journée :
			</h3>
		</div>
	</div>
</div>

<section class="section">
	<div class="wrap cf">
		<div class="inner">
			<div class="techno-col content cf">
				<ul><strong>Étendre et augmenter HTML pour qu'il réponde à vos besoins :</strong>
					<li>Plongée dans le coeur de AngularJS : fonctionnement interne.</li>
					<li>AngularJS pour les pros : les directives.</li>
					<li>Fonctionnement des directives.</li>
					<li>Directive et évenements utilisateurs.</li>
					<li>Intégration d'un contrôleur dans une directive.</li>
					</ul>
				<ul><strong>Travaux Pratiques :</strong>
					<li>Création d'un fiche récapitulative.</li>
					<li>Affichage calendaire.</li>
					</ul>
			</div>
			<div class="techno-col content last cf">
				<ul><strong>Communication inter-process en temps réel :</strong>
					<li>LPerspectives, trucs & astuces.</li>
					<li>Organisation du code selon la taille de votre application.</li>
					<li>Bonnes pratiques.</li>
					<li>Automatisation avec Grunt.</li>
					<li>Perspectives.</li>
					</ul>
				<a href="contact.html" class="btn">Contactez-nous</a>
			</div>
		</div>
	</div>
</section>