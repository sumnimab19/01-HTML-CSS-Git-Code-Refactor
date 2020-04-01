# 01-HTML-CSS-Git-Code-Refactor

# Horiseon

Horiseon provides services such as Search Engine Optimization, Online Reputation Management, Social Media Marketing.

## Description

User can click on the navigator links at the top right hand corner of the page to get to the detail or can scroll down to see the detail.  

## Technology Used
1. Semantic HTML
2. CSS


## Code

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" >
    <!-- Added meta tags for accessibility and searchablility -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="search engine optimization, online reputation management, social media marketing">
    <link rel="stylesheet" href="./assets/css/style.css">
    <!-- Title changed to company's name -->
    <title>Horiseon Social Solution Services</title>
</head>

<body>
    <!-- Header and Navigator -->
    <!-- Replaced <div> with <header> and <nav> tags -->
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
    
    <!-- Replaced <div> with <section> tag -->
    <!-- Digital Marketing Meeting image -->
    <section class="hero"></section>


    <!-- Services Section -->
    <!-- Added 'alt' to all the <img> tags -->
    <!-- Made the Search Engine Optimization link work from the navigator by adding id -->
    <!-- Replaced div tags with section and article tags for services area and benefits area -->
    <!-- Renamed 'content' class to 'services' to be more specific of the content for this section. -->
    <!-- Consolidated search-engine-optimization, online-reputation-management, social-media-marketing classes 
        into single 'services-article' class as the styling for all are same.-->
    <section class="services">
        <article id="search-engine-optimization" class="services-article"> 
            <img src="./assets/images/search-engine-optimization.jpg" alt="Search Engine Optimization" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>
        <article id="online-reputation-management" class="services-article">
            <img src="./assets/images/online-reputation-management.jpg" alt="Online Reputation Management" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </article>
        <article id="social-media-marketing" class="services-article">
            <img src="./assets/images/social-media-marketing.jpg" alt="Social Media Marketing" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </article>
    </section>

    <!-- Benefit Section -->
    <!--Consolidated benefit-lead, benefit-brand, benefit-cost classes into single 'benefits-article' class 
        as the styling for all are same. Added id for each of them so that styling can be done for each if needed later. -->
    <section class="benefits">
        <article id="benefit-lead" class="benefits-article">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="Lead Generation"/>
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </article>
        <article id="benefit-brand" class="benefits-article">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Brand Awareness"/>
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </article>
        <article id="benefit-cost" class="benefits-article">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="Cost Management"/>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </article>
    </section>

    <!-- Footer -->
    <!-- Replaced <div> with <footer> tag -->
    <footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>

</body>

</html>
