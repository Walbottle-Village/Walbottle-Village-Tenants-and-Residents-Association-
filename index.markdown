---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---
	
<div class="container-fluid">
	<div class="row">
<div class="mastImg">
<img src="assets/images/mastheadImg-home.jpg" class="img-responsive" alt="aerial view of Walbottle Village"/>
		</div>

<div class="container-fluid welcome">
	<div class="row">
		<div class="col-lg-1 col-md-1"></div>
		<div class="welcomePanel col-lg-10 col-md-10 row-eq-height">
			<div class="col-lg-7 col-md-7">
			  <h2>Welcome</h2>
			  <p><strong>The Walbottle Village Tenants and Residents Association was founded in 2020 during Covid lockdown to bring relief to residents of Walbottle Village by encouraging a community spirit and assisting the most vulnerable members of the community.</strong></p>
			  <p>The remit is expanding post lockdown to include a gardening club, a history group a food bank collection and organising social events which are open to all. We pride ourselves in being fully inclusive, having minority groups on the committee.</p>
			  <h5>Creating a more neighbourly village and a safe, beautiful place to live</h5>
			</div>
			<div class="col-lg-5 col-md-5 hidden-sm hidden-xs">
		    <<img src="assets/images/Wallbottle-May-23-10.jpg" class="img-responsive" alt="Walbottle Village Institute"/>
			</div>
		</div>
		<div class="col-lg-1 col-md-1"></div>
		</div>
</div>

<div class="container-fluid redPanel">
	<div class="row">
		<div class="col-lg-1"></div>
		<div class="col-lg-10 gallerySlider">
			<h2>What's On</h2>
			<!-- feature slider -->
		<div class="row gallery-slider">
			<div class="col-xs-12 col-sm-12"><button type="button" class="slideLeft" id="goToPrevSlide"></button>
			<ul id="lightSlider">

			{% for event in site.data.events %}
				<li class="featurePane col-xs-4">
					<a href="about-choristers.html" title="visit the Walbottle Choisters group page">
					<img src="{{event.image}}" class="img-responsive" alt="walbottle choristers"/>
					<h3>{{event.name}}</h3>
					<p>{{event.about}}</p>
					<button class="more">Find out more <span class="glyphicon glyphicon-triangle-right"></span></button>
					</a>
				</li>
				{% endfor %}

	        </ul>
				<button type="button" class="slideRight" id="goToNextSlide"></button>
			</div>
		</div>
	<!-- end art gallery light Slider -->
		</div>
	</div>
	</div>
	
	<div class="container-fluid whitePanel">
	<div class="row">
		<div class="col-lg-1 col-md-1 col-sm-1 col-xs-1"></div>
		<div class="activity-contactPanel col-lg-10 col-md-10 col-sm-10 col-xs-10 row-eq-height">
			<div class="col-md-4 col-xs-12 activity">
					<h2>Activity Groups</h2>
					<p>We have a wide variety of local groups in Walbottle, for more information please select a link below. If you would like more information or would like to start a group please contact us using one of the Get In Touch forms on the website.</p>
					<ul>
						<li><a href="#" title="access Group" target="_self" class="ag-access" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Access Group</a></li>
						<li><a href="#" title="gardening group" target="_self" class="ag-garden" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Gardening Group</a></li>
						<li><a href="#" title="kids corner" target="_self" class="ag-kids" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Kids Corner</a></li>
						<li><a href="#" title="neighbourhood watch" target="_self" class="activity" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Neighbourhood Watch</a></li>
						<li><a href="#" title="photography group" target="_self" class="ag-photo" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Photography Group</a></li>
						<li><a href="#" title="Walbottle choristers group" target="_self" class="ag-choir" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Walbottle Choristers</a></li>
						<li><a href="#" title="Walbottle walks group" target="_self" class="ag-walks" accessKey=""><span class="glyphicon glyphicon-triangle-right"></span> Walbottle Walks</a></li>
					</ul>
			</div>
			<div class="col-xs-1"></div>
			<div class="col-md-7 col-xs-12 form">
				<h2>Get in Touch</h2>
				<p>We would love to hear from our residents. Whether you would like to volunteer, suggest a Group, help create a neighbourly village or would like more information about anything you have read in our newsletter or website please contact us using the form below.</p>
			</div>
		</div>
	</div>
	</div>
			
	<div class="container-fluid photoPanel">
	<div class="row">
		<div class="col-lg-1 col-md-1 col-sm-1 col-xs-1"></div>
		<div class="basePhoto01 col-xs-3">
	    <img src="img/basePic01.jpg" class="img-responsive" alt="Walbottle Dene"/>
		</div>
		
		<div class="basePhoto02 col-xs-3">
	    <img src="img/basePic02.jpg" class="img-responsive" alt="A brick from Walbottle brickworks"/>
		</div>
		
		<div class="basePhoto03 col-xs-3">
	    <img src="img/basePic03.jpg" class="img-responsive" alt="Walbottle Village Institute"/>
		</div>
		<div class="col-lg-1 col-md-1 col-sm-1 col-xs-1"></div>
	</div>
	</div>
