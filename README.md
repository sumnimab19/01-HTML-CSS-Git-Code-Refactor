# 01-HTML-CSS-Git-Code-Refactor

# Horiseon

Horiseon is a marketing agency that provides services such as Search Engine Optimization, Online Reputation Management, Social Media Marketing.

## Description

User can click on the navigator links at the top right hand corner of the page to get to the detail or can scroll down to see the detail.  

## Technology Used
1. Semantic HTML
2. CSS


## Code / Screenshot

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
    
   
</html>
