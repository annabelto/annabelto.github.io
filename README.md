<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">

    <!-- 
      TODO

      Upload your Unemployable (or whatever photo you like) to the assets/images folder
      and change the name of the image below to match the uploaded one

      Change the title in the <title> tag to whatever you would like the title of your portfolio to be

      This should be the same across all pages.
     -->
    <link rel="icon" href="./assets/images/1311.png" />
		<title>Unemployables Portfolio</title>
    <meta name="description" content="A portfolio template for the Unemployables community.">
    <meta name="viewport" content="width=device-width, initial-scale=1" />

		<link rel="stylesheet" href="./css/layout.css">
    <link rel="stylesheet" href="./css/typography.css">
    <link rel="stylesheet" href="./css/utilities.css">

		<script defer src="./js/script.js"></script>
	</head>
	<body>
    <!-- NAVBAR -->
    <div class="navbar">
      <a class="nav-title-link" href="./index.html">
        <!-- TODO - Change the "Portfolio Title" to whatever you want displayed in the top left -->
        <span class="nav-title">Portfolio Title</span>
         <!-- TODO - Change the email after 'mailto:' to your email address for contact -->
        <a class="button" href="mailto:whitevans.eth@gmail.com">
          <span class="button-text">Contact Me</span>
        </a>
      </a>
    </div>

    <!-- MAIN PAGE CONTENT -->
    <div id="main-content">

      <!-- PORTFOLIO HEADER -->
      <div id="portfolio-header">
        <div id="portfolio-header-image-container">
          <!-- 
            TODO

            - Change the img "src" attribute to point to the Unemployable image you uploaded (or whatever image).
            - Change the number to point to your Unemployable & replace the OpenSea link with your own
            - If you aren't using an Unemployable as your image, remove the entire "a" element
          -->
          <img src="./assets/images/1311.png" class="portfolio-header-image">
          <a class="no-underline" target="_blank" href="https://opensea.io/assets/0xe0be388ab81c47b0f098d2030a1c9ef190691a8a/1311">
            <span class="image-caption">Unemployables #1311</span>
          </a>
        </div>

          <!-- 
            TODO

            - Change the main-title to whatver you want
            - Change the body-text after that to a quick introduction to what you do
            - Edit the button text if you feel like it. It will link to the projects section below.
          -->
        <div id="portfolio-header-text-container">
            <div class="header-text">
              <span class="main-title">Hey, I'm @ndoherty_eth.</span>
              <div class="body-text">I’m a freelance designer and developer who aims to help other creatives build out their portfolios, skillset, and businesses.</div>
            </div>
            <a class="button" id="my-work-link">
              <span class="button-text">Check out my projects</span> 
              <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
            </a>
        </div>
      </div>

      <!-- ABOUT SECTION -->
      <!-- 
        TODO

        - Change the subheader-text to whatever header you want
        - Add paragraphs using the <div class="body-text"></div> elements in the "about-section-content"
      -->
      <div id="about-section">
        <span class="subheader-text">My Background / About Me</span>
        <div class="about-section-content">
          <div class="body-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tristique risus nec feugiat in fermentum. Sed id semper risus in hendrerit gravida. Placerat duis ultricies lacus sed. Id neque aliquam vestibulum morbi blandit cursus risus. Elit pellentesque habitant morbi tristique senectus et netus et. Elementum tempus egestas sed sed risus pretium quam. Nibh ipsum consequat nisl vel pretium lectus quam id leo. Vitae congue mauris rhoncus aenean vel elit.</div>
          <div class="body-text">Vitae justo eget magna fermentum. Imperdiet nulla malesuada pellentesque elit eget gravida. Aliquet nec ullamcorper sit amet. Aliquet sagittis id consectetur purus. Ac tortor dignissim convallis aenean. Enim neque volutpat ac tincidunt vitae. Lobortis feugiat vivamus at augue. Platea dictumst vestibulum rhoncus est pellentesque elit ullamcorper. Viverra orci sagittis eu volutpat. Massa tincidunt nunc pulvinar sapien et ligula. Donec enim diam vulputate ut.</div>
        </div>
      </div>

      <!-- PROJECTS / MY WORK SECTION -->
      <div id="my-work-section">
        <!-- TODO - Change the subheader-text to whatever you want the Projects section header to say -->
        <span class="subheader-text">My Work / My Projects</span>

        <div class="projects-container">
          <!-- 
            TODO

            This is where the project cards live. Here's a base level project card for you to copy:
            <div class="project-card">
              <img src="./assets/images/IMAGE_NAME" class="project-image">
              <div class="project-card-text-container">
                <div class="subheader-text project-title">PROJECT_NAME</div>
                <div class="body-text project-card-text">SMALL_PROJECT_DESCRIPTION</div>
              </div>
              <a class="button" href="./project-pages/PROJECT_PAGE_NAME.html">
                <span class="button-text">Read More</span>
                <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
              </a>
            </div>

            - To add a project to the this area, copy the above, paste it below this comment, and change the following:
                - IMAGE_NAME: the name of the image file in assets/images
                - PROJECT_NAME: the name of the project (keep it short, it only shows 1 line)
                - SMALL_PROJECT_DESCRIPTION: a quick project description (max 4 lines)
                - PROJECT_PAGE_NAME.html: the html filename for the project (must be in project-pages folder)
          -->
          <div class="project-card">
            <img src="./assets/images/desktop.jpeg" class="project-image">
            <div class="project-card-text-container">
              <div class="subheader-text project-title">Project Name</div>
              <div class="body-text project-card-text">Elit pellentesque habitant morbi tristique senectus et netus et. Elementum tempus egestas sed sed risus pretium quam. Nibh ipsum consequat nisl vel pretium</div>
            </div>
            <a class="button" href="./project-pages/project-template.html">
              <span class="button-text">Read More</span>
              <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
            </a>
          </div>
          <div class="project-card">
            <img src="./assets/images/code.jpeg" class="project-image">
            <div class="project-card-text-container">
              <div class="subheader-text project-title">Project Name</div>
              <div class="body-text project-card-text">Elit pellentesque habitant morbi tristique senectus et netus et. Elementum tempus egestas sed sed risus pretium quam. Nibh ipsum consequat nisl vel pretium</div>
            </div>
            <a class="button" href="./project-pages/project-template.html">
              <span class="button-text">Read More</span>
              <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
            </a>
          </div>
          <div class="project-card">
            <img src="./assets/images/sketchbook.jpeg" class="project-image">
            <div class="project-card-text-container">
              <div class="subheader-text project-title">Super Long Project Name That Should be Hidden</div>
              <div class="body-text project-card-text">Elit pellentesque habitant morbi tristique senectus et netus et. Elementum tempus egestas sed sed risus pretium quam. Nibh ipsum consequat nisl vel pretium</div>
            </div>
            <a class="button" href="./project-pages/project-template.html">
              <span class="button-text">Read More</span>
              <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
            </a>
          </div>
        </div>
      </div>
    </div>

    <!-- FOOTER -->
    <div id="footer">
      <!-- 
        TODO - Change href to your Instagram account (can also delete entire "a" element if no Instagram) 

        This should be the same across all pages.
      -->
      <a class="icon-link" target="_blank" href="https://twitter.com/whitevans_eth">
        <image src="./assets/icons/instagram.svg" class="footer-icon"/>
      </a>
      <!-- 
        TODO - Change href to your Twitter account (can also delete entire "a" element if no Twitter) 
      
        This should be the same across all pages.
      -->
      <a class="icon-link" target="_blank" href="https://twitter.com/whitevans_eth">
        <image src="./assets/icons/twitter.svg" class="footer-icon"/>
      </a>
      <!-- 
        TODO - Change the email after "mailto" to your contact email 
      
        This should be the same across all pages.
      -->
      <a class="icon-link" href="mailto:whitevans.eth@gmail.com">
        <image src="./assets/icons/mail.svg" class="footer-icon"/>
      </a>
    </div>

	</body>
</html>
