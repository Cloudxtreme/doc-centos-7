---
layout: post
title: "LEMP Stack, CentOS 7"
date: 2017-03-07
---

<div class="wrapper">
		<div class="header header-filter" style="background-image: url('{{ site.github.url}}/img/bg2.jpeg');">
			<div class="container">
				<div class="row">
					<div class="col-md-8 col-md-offset-2">
						<div class="brand">
							<h1>{{ page.title }}</h1>
							<h3>- {{ post.date | date_to_string }} -</h3>
						</div>
					</div>
				</div>
			</div>
			<div class="main main-raised margin-top">
				<div class="section section-basic">
			    	<div class="container">
			            <div class="title">
							<h2>{{ post.title }}</h2>
			            </div>
				            <div class="row">
				                <div class="col-md-10 col-md-offset-1">
				                	<a href="{{ site.github.url }}{{ post.url }}" title="{{ post.title }}"><h2>{{ post.title }}</h2></a>
				                	<p>
				                		A "LAMP" stack is a group of open source software that is typically installed together to enable a server to host dynamic websites and web apps. This term is actually an acronym which represents the Linux operating system, with the Apache web server. The site data is stored in a MySQL database (using MariaDB), and dynamic content is processed by PHP...  <a href="{{ site.github.url }}{{ post.url }}" class="margin-left">Read More</a>
				                	</p>
				                	<p>by <strong>Kus Gautam</strong>, {{ post.date | date_to_string }}</p>	
				                </div>
				            </div>
			        </div>
			    </div>
			</div>
		</div>
</div>