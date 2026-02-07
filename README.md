<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
	<title>www.TonyBrownlee.net</title>

	<meta http-equiv="content-type" content="text/html;charset=utf-8" />
	<meta name="viewport" content="width=970,user-scalable=yes" />

	<link rel="stylesheet" type="text/css" media="all" href="css/style.css" />

	<!-- Including Puritan font from Google Web Fonts -->
	<link  href="http://fonts.googleapis.com/css?family=Puritan:regular,italic,bold,bolditalic" rel="stylesheet" type="text/css" />

	<!-- Including jQuery -->
	<script src="http://code.jquery.com/jquery-latest.js" type="text/javascript"></script>
	<script src="http://code.jquery.com/jquery-migrate-1.0.0.js" type="text/javascript"></script>

	<!-- Custom functions -->
	<script src="lib/js/jquery.custom.minimalme.js" type="text/javascript"></script>

	<!-- Including & Initializing tipsy (nicer tooltips) -->
	<link rel="stylesheet" type="text/css" href="lib/js/tipsy/stylesheets/tipsy.css" />
	<script type="text/javascript" src="lib/js/tipsy/javascripts/jquery.tipsy.js"></script>
	<script type="text/javascript">
	/* <![CDATA[ */
	jQuery(document).ready(function($){
		$('#social_media a').tipsy({gravity: 's', opacity: 0.9, fade: true});
		$('#nav a').tipsy({gravity: 's', opacity: 0.9, fade: true});
		$('.cv_options a').tipsy({gravity: 's', opacity: 0.9, fade: true});
	});
	/* ]]> */
	</script>

	<!-- Including & Initializing Fancybox (gallery & contact form) -->
	<link rel="stylesheet" type="text/css" href="lib/js/fancybox/jquery.fancybox-1.3.4.css" media="screen" />
	<script type="text/javascript" src="lib/js/fancybox/jquery.mousewheel-3.0.4.pack.js"></script>
	<script type="text/javascript" src="lib/js/fancybox/jquery.fancybox-1.3.4.pack.js"></script>

	<script type="text/javascript">
	/* <![CDATA[ */
	jQuery(document).ready(function($){
		// Defining Fancybox for the work samples section. You can remove it if you do not plan to include such a section:
		// Start Fancybox gallery
		$(".portfolio a").fancybox({
			'padding'			: 10,
			'titlePosition' 	: 'over',
			'titleFormat'       : function(title, currentArray, currentIndex, currentOpts) { return '<span id="fancybox-title-over"><strong>' +  (currentIndex + 1) + ' / ' + currentArray.length + '</strong> ' + title + '</span>'; },
			'transitionIn'		: 'fade',
			'transitionOut'		: 'fade',
			'overlayColor'		: '#000',
			'overlayOpacity'	: 0.8
		});
		// End Fancybox gallery
	});
	/* ]]> */
	</script> 
</head>

<body id="top" class="wood">
	<div id="resume">
		<!-- Start: Header section -->
		<div class="section head_section">
			<div class="section_content">
				<div class="my_info">
					<h1 class="my_name" title="">Anthony Brownlee</h1>
					<div class="my_profession">Project Manager | Scuba Instructor</div>
				</div>

				<div class="text_ruler"><span>Let's Connect</span></div>

				<div class="two_thirds">
					<img src="img/my-photo.jpg" title="" alt="" class="my_photo" />A United States Marine Corps veteran, Anthony has over 20 years of IT experience ranging from help desk to his current position as an IT Infrastructure Project Manager.
					<ul class="cv_options">
						<!--<li><a href="#letsmeet" title="Get in touch" class="cv_email">Let's meet!</a></li>-->
						<li><a href="Anthony Brownlee.pdf" title="Download my resume" class="cv_download">Download my resume</a></li>
					</ul>
				</div>

				<div class="one_third last_column">
					<ul class="simple_list">
						<li><strong>Email:</strong> <a href="mailto:brownleeanthony@gmail.com">brownleeanthony@gmail.com</a><br />
						<li><strong>Website:</strong> <a href="http://tonybrownlee.net">tonybrownlee.net</a></li>
						<li><strong>Phone:</strong>+1 816-661-3045</li>
						<li><strong>Address:</strong>Lees Summit, MO USA</li>
					</ul>
				</div>
			</div>
		</div>
		<!-- End: Header section -->

		<!-- Start: Navigation -->
		<div id="nav">
			<ul>
				<li><a href="#section1" title="Who is Anthony Brownlee?">About</a></li><li><a href="#section3" title="Experience">Experience</a></li><li><a href="#section4" title="Certifications">Certifications</a></li><li><a href="#section6" title="Portfolio">Portfolio</a></li><li><a href="#footer" title="Contact me">Contact</a></li>
			</ul>
		</div>
		<!-- End: Navigation -->

		<!-- Start: Section -->
		<div class="section" id="section1">
			<h2 class="section_title">About</h2>
			<div class="section_content">
				<div class="two_thirds"><p>With a wide breadth of life experience, Anthony has skills in the following areas.</p><p><strong>Military (1988-1992):</strong> Martial Arts. Firearms. Vehicle Maintenance.  Maintenance Management.</p><p><strong>Police &amp; Security (1993-1998):</strong> Conflict resolution. Incident Documentation.</p><p><strong>Help Desk (1998-Present):</strong> Troubleshooting.  Technical Documentation. Windows 2000. Windows XP. Windows 7. Windows 8.  Microsoft Office.  Google Apps.</p><p><strong>Systems Administration (2002-Present):</strong> Windows 2000. Windows Server 2003. CentOS. RedHat Linux. Microsoft Exchange.  SMTP. TCP/IP. Cisco Firewalls.  Routers. Wireless Networking.</p><p><strong>Project Management (2009-Present):</strong> Project Planning. Resource Management. Scheduling. Budgeting. Logistics. </p><p><strong>SCUBA: (2010-Present):</strong> Dive Physics. Dive Physiology. Underwater Navigation. Search and Recovery. Dive planning. CPR. First Aid. Oxygen Provider. In-water rescue. Diver training.</p></div>
				<div class="one_third last_column">
					<div class="skill">
						<h4>Project Management</h4>
						<div class="skillbar"><div class="skillbarfill skill100">Excellent</div></div>
					</div>
					<div class="skill">
						<h4>Networking</h4>
						<div class="skillbar"><div class="skillbarfill skill90">Excellent</div></div>
					</div>
					<div class="skill">
						<h4>Leadership</h4>
						<div class="skillbar"><div class="skillbarfill skill90">Excellent</div></div>
					</div>
				</div>
			</div>
			<div class="section_footer"><a href="#top" class="go_top">Back to top</a></div>
		</div>
		<!-- End: Section -->
		
		<!-- Start: Section -->
		<div class="section" id="section3">
			<h2 class="section_title">Experience</h2>
			<div class="section_content">
				<div class="job">
					<div class="one_third">
						<h3 class="mt0">Practice Architect</h3>
						<h4>TEKsystems Global Services</h4>

						<ul class="simple_list mt20">
							<li><strong>Period:</strong> March 2022 - Present</li>
							<li><strong>Job type:</strong> Full-Time</li>
						</ul>
					</div>
					<div class="two_thirds last_column">
						<p>Project Architect on Enterprise Operations Team.</p>
						<ul>
							<li>Assisted with scope creation and pricing of opportunities with new customers.</li>
							<li>Supported a team of 60 Service Delivery Managers and their leadership with engagement startup, best practices, and transition of processes from new customers.</li>
							<li>Acted as Scrum Master when starting projects that required large numbers of contractors or an accelerated timeline.</li>
							<li>Engaged with client technical teams to complete knowledge and process transition.</li>	
						</ul>
					</div>
				</div>
				
				<div class="ruler"></div>	
				
				<div class="job">
					<div class="one_third">
						<h3 class="mt0">Global Delivery Manager</h3>
						<h4>TEKsystems Global Services</h4>

						<ul class="simple_list mt20">
							<li><strong>Period:</strong> January 2019 - March 2022</li>
							<li><strong>Job type:</strong> Full-Time</li>
						</ul>
					</div>
					<div class="two_thirds last_column">
						<p>Project Portfolio Manager on Managed Workplace Services Team.</p>
						<ul>
							<li>Supported a team of 8 Service Delivery Managers with a portfolio of 9-12 infrastructure deployment projects.</li>
							<li>Assisted Project Managers with remediating struggling projects.</li>
                            <li>Closely monitored financial and customer satisfaction metrics of all projects in portfolio.</li>
							<li>Trained new Delivery Managers and guided existing in corporate PMLC and methodology practices.</li>
						</ul>
					</div>
				</div>

				<div class="ruler"></div>				
				
				<div class="job">
					<div class="one_third">
						<h3 class="mt0">Delivery Manager</h3>
						<h4>TEKsystems Global Services</h4>

						<ul class="simple_list mt20">
							<li><strong>Period:</strong> May 2014 - January 2019</li>
							<li><strong>Job type:</strong> Full-Time</li>
						</ul>
					</div>
					<div class="two_thirds last_column">
						<p>Service Delivery Manager on Technology Deployment team.</p>
						<ul>
							<li>Assisted in delivering a $1.3 Million project to install updated credit card devices at 1100 retail locations.</li>
							<li>Managed project to eliminate Windows XP from the enterprise of a large energy company.</li>
                            <li>Managed $9 Million program to survey and implement security best practices on IoT devices at financial institutions.</li>
							<li>Assisted other Project Managers with various issues and vacation coverage.</li>
						</ul>
					</div>
				</div>

				<div class="ruler"></div>

				<div class="job">
					<div class="one_third">
						<h3 class="mt0">Instructor &amp; Divemaster</h3>
						<h4>Sam's Skin n Scuba</h4>

						<ul class="simple_list mt20">
							<li><strong>Period:</strong> July 2014 - Present</li>
							<li><strong>Job type:</strong> Contractor</li>
						</ul>
					</div>
					<div class="two_thirds last_column">
						<p>Teach and certify students in recreational scuba diving according to PADI standards.</p>
						<ul>
							<li>Trained and certified in adult learning to present complex theories and keep students engaged.</li>
							<li>Conduct classes in classroom, pool and open water.</li>
							<li>Evaluate student skills in water.</li>
							<li>Provide one-on-one assistance for students.</li>
						</ul>
					</div>
				</div>
				
				<div class="ruler"></div>

				<div class="job">
					<div class="one_third">
						<h3 class="mt0">Project Manager</h3>
						<h4>Central Technology Consulting Group</h4>

						<ul class="simple_list mt20">
							<li><strong>Period:</strong> July 2013 - May 2014</li>
							<li><strong>Job type:</strong> Consultant/Contractor</li>
						</ul>
					</div>
					<div class="two_thirds last_column">
						<p>Project Management consultant outsourced to clients.</p>
						<ul>
							<li>Successfully managed project to image and deliver over 150 new laptops to trucking fleet.</li>
							<li>Gathered and documented requirements for implementation of new IT Service Desk software.</li>
							<li>Built relationships with several business units, gathering information about their processes and wish lists of projects.</li>
							<li>Led Project to upgrade terminal automation software at product loading facilities.</li>
						</ul>
					</div>
				</div>
				
				<div class="ruler"></div>

				<div class="job">
					<div class="one_third">
						<h3 class="mt0">Data Center Manager</h3>
						<h4>Celeritas Technologies</h4>

						<ul class="simple_list mt20">
							<li><strong>Period:</strong> April 2007 - July 2013</li>
							<li><strong>Job type:</strong> Full Time</li>
						</ul>
					</div>
					<div class="two_thirds last_column">
						<p>Responsible for management of software development company's network infrastructure.</p>
						<ul>
							<li>Administered over 40 Windows (2000/2003), RedHat and CentOS servers.</li>
							<li>Reconfigured network to improve performance of load balancers, increase security and simplify network.</li>
							<li>Assisted executive leadership with office relocation including design and construction of new data center.</li>
							<li>Provided technical sales support on possible infrastructure projects.</li>
							<li>Consulted with various clients on data center moves and server migrations.</li>
						</ul>
					</div>
				</div>
				
			</div>
			<div class="section_footer"><a href="#top" class="go_top">Back to top</a></div>
		</div>
		<!-- End: Section -->
		
		<!-- Start: Section -->
		<div class="section" id="section4">
			<h2 class="section_title">Certifications</h2>
			<div class="section_content">
				<div class="studies">
					<h3>Project Management Professional #1619100</h3>
					<h4 class="mt10">Project Management Institute</h4>
				</div>

				<div class="ruler"></div>

				<div class="studies">
					<h3>IDC Staff Instructor  #349017</h3>
				<h4 class="mt10">Professional Association of Diving Instructors (PADI)</h4>
				</div>
				
				<div class="ruler"></div>

				<div class="studies">
					<h3>Certified Scrum Master</h3>
				<h4 class="mt10">Scrum Alliance</h4>
				</div>
				
				<div class="ruler"></div>
				
				<div class="studies">
					<h3>Certified Cloud Practitioner</h3>
				<h4 class="mt10">Amazon Web Services</h4>
				</div>
				
				<div class="ruler"></div>
				
				<div class="studies">
					<h3>Various Technical Certifications</h3>
				<h4 class="mt10">Microsoft/CompTIA</h4>
				</div>
							
			</div>
			<div class="section_footer"><a href="#top" class="go_top">Back to top</a></div>
		</div>
		<!-- End: Section -->
		
		<!-- Start: Section -->
		<div class="section" id="section6">
			<h2 class="section_title">Portfolio</h2>
			<div class="section_content">
				<div class="half"><b><center>EMV Credit Card Pad Upgrade<center></b></p><b>Situation</b></p><p>A Major U.S. retailer had not experienced any significant security breaches, yet they realized that their outdated credit card kiosks put them at greater risk. New kiosks would help them avoid those risks, but also enable them to accept EMV-chip enabled cards and, in the future, newer payment technologies that had been introduced into the market (e.g., Google Pay).</p><p><b>Challenges</b></p><p>It was important to the client to minimize store downtime and to complete the project before the holiday shopping season, when they undergo a technology freeze.  Additionally, the equipment vendor was unable to keep pace with the deployment, requiring numerous schedule changes and communication with the technicians, the sites and the clients project team.</p><p><b>Solution</b></p><p>Anthony joined the $1.3 Million project early in execution and worked to improve the processes crucial to project success including how stores were scheduled, how on-site technicians were trained and provided much needed leadership to the project team.</p><p><b>Results</b></p><p>The team successfully completed the installation of over 19,000 kiosks at 1,100 sites prior to the beginning of the holiday season and the client's technology freeze. During this 26-week period, they deployed 589 unique on-site technicians, averaging a 97.3 percent on-time arrival, exceeding the required 94 percent target set by the client.</p><p><b>Added Value</b></p><p>Following deployment, the client reengaged the project team to swap out kiosks at 50 stores that were completed as part of their internal pilot because the original hardware was missing a key piece of technology. They also provided telephone support during the installation of longer cables at some stores that were upgraded before the longer cables were available.</div>
				<div class="half last_column"><b><center>Windows 7 Deployment<center></b></p><b>Situation</b></p><p>An energy company with a fleet of crude oil gathering trucks had developed new software for dispatching and recording the loads they gathered.  Additionally, the laptops and printers in the trucks needed to be replaced and the drivers needed training on Windows 7 and the new software.  Every hour that the trucks were idle the business estimated that it cost them $600 therefore maintaining a tight schedule was critical to the customers success criteria.</p><p><b>Challenges</b></p><p>It was expected that most of the drivers would have a lot of questions about the new software and would require one-on-one training to ensure the proper comfort level.  The geographical area that this fleet covered included many rural areas causing one part of the Windows 7 upgrade that had to be completed over the cellular network to run very slowly in some areas and there was increased risk of maintaining the schedule with unexpected breakdowns and other factors.  Finally, the software SME and expected trainer was not able to meet the deployment techs early in the project and train the trainers as planned.</p><p><b>Solution</b></p><p>Anthony was assigned the project shortly after software development was completed and tasked with working with hiring deployment techs, working with the business to develop a schedule that would minimize downtime and closely track the completion rate and account for all assets.</p><p><b>Result</b></p><p>Drivers were scheduled to meet the deployment team at truck stops and restaurants, allowing for a break while the new laptops and printers were installed.  Drivers then returned to their trucks, trained on the software and provided detailed instructions for their most common tasks.  Anthony and the assisting PM arranged their schedules to be at deployment sites or dispatch centers during most of the deployments, giving the business instant access to IT resources for any questions.  The project was completed ahead of schedule and within the $385,000 budget.</p><p><b>Added Value</b></p><p>Following deployment, some performance issues were discovered with the software.  Due to Anthony’s relationships with the business, he was tasked with resolving the issues and became the single point of contact for the users.  While on site working with the users to observe their issues, he was able to identify other areas where IT could assist with streamlining processes.</p></div>
			</div>
			<div class="section_footer"><a href="#top" class="go_top">Back to top</a></div>
		</div>
		<!-- End: Section -->

		<div class="clear"></div> <!-- Do not remove -->
	</div>

	<!-- Start: Footer -->
	<div id="footer">
		<div class="section">
			<div class="section_content">
				<div class="one_third">
					<h3 class="footer_title"><span>Sites I Love</span></h3>

					<ul>
						<li><a href="https://www.pmi.org/">Project Management Institute - Project Management Standards and Certification.</a></li>
						<li><a href="http://www.skinnscuba.com">Sam's Skin-n-Scuba - Where Kansas City learns to dive.</a></li>
						<li><a href="https://www.home-assistant.io/">Home Assistant - Awaken your home.</a></li>
						<li><a href="http://north6.net/">North6 - Business and Technology Consulting.</a></li>
					</ul>
				</div>
				
				<div class="one_third">
					<h3 class="footer_title"><span>Social Media</span></h3>

					<ul>
						<li><a href="https://twitter.com/AnthonyBLSMO"><strong>Twitter</strong></a></li>
						<li><a href="https://www.linkedin.com/in/anthonybrownlee/"><strong>LinkedIn</strong></a></li>
					</ul>
				</div>
				
				<div id="letsmeet" class="one_third last_column">
					<h3 class="footer_title"><span>Where I am</span></h3>

					<iframe width="270" height="200" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d88503.90595557644!2d-94.43859117378234!3d38.91378176775525!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x87c0dff6a8b596fd%3A0x8d2c2e9a007b187!2sLee&#39;s%20Summit%2C%20MO!5e0!3m2!1sen!2sus!4v1687521941733!5m2!1sen!2sus" width="270" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

				</div>
			</div>
		</div>
	</div>
	<!-- End: Footer -->

</body>
</html>
