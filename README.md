## Project Overview
<pre>
<b>Project:</b> Killapinas
<b>Role:</b>    Brand Identity Designer, UI/UX Designer, & Lead Web Developer
<b>Tools:</b>   Photoshop, HTML, CSS, JS/jQuery, Foundation, Tumblr
</pre>

&nbsp;<strong><a href="https://killapinas.com/">View project</a></strong>

<p><a href="https://killapinas.com/"><img src="https://doylesee.github.io/killapinas/thumbnail.jpg" /></a></p>
<br />

## The Challenge
Killapinas initially launched its operations through Facebook Marketplace. While this supported their early growth, the lack of a central hub limited their brand identity and forced them to manage transactions manually. They needed an official web destination that reflected their raw aesthetic without the burden of expensive enterprise web hosting or complex backend databases.

The challenge was to engineer a fully functional e-commerce storefront on Tumblr, a platform built for blogging, not retail. I needed to bypass these rigid platform limitations to build a structured shopping experience from scratch, while translating their distinct visual style into a unique desktop layout.

<br />

## Core Objectives
**Social-to-Web Migration**<br />
Transition a grassroots social media sales workflow into a centralized, automated digital storefront.

**High-Impact Minimalist Design**<br />
Architect a bare-bones, content-first user interface that leverages striking, screen-dominant imagery.

**Custom State Management**<br />
Program a serverless frontend cart / checkout system directly into Tumblr’s theme files.

<br />

## My Approach & Implementation
### 1. Stripped-Back, Bold UI Design
Referencing the brand's raw, horror, and street ethos, I leaned heavily into this, plus a minimalist, product-first aesthetic in Photoshop. The structural goal was to remove all unnecessary digital noise and focus entirely on the apparel.

The layout features a clean, focused header housing only the logo, essential navigation represented by icons, and their social media links. Directly below, the product listing dominates the entire interface. On desktop, I engineered a bold layout where each product takes up exactly half the width of the screen and the entire height of the viewport. On mobile, the code seamlessly adapts, shifting the products into full-width content blocks optimized for vertical scrolling.

### 2. Engineering the Serverless Checkout System
Since Tumblr has no native checkout feature or database infrastructure, I deployed a lightweight, client-side data architecture using JavaScript, jQuery, and LocalStorage to process transactions safely and efficiently:

**Cart State Preservation**<br />
I wrote a custom event listener attached to product action states. When a customer adds an item, the script captures the attributes, appends a dynamic timestamp to keep orders distinct, and saves the data straight into the user's browser storage.

**Dynamic Checkout Compilation**<br />
On the dedicated checkout directory page, the script actively reads the LocalStorage array, dynamically loops through and renders individual cart rows, updates pricing strings, and injects the formatted text block into hidden form fields.

**Pipeline Order Routing**<br />
To process orders with zero server costs, I funneled the submission form through Formspree. When an order is placed, the data bundle maps directly to the client's intake system, clears the user's browser storage, and triggers a clean redirect to the home screen.

<br />

## Results & Impact
**Seamless Platform Evolution**<br />
Successfully moved the client from manual Facebook Marketplace interactions to an automated web platform, greatly professionalizing their retail presence.

**Innovative Engineering Under Constraints**<br />
Proved that complex backend software isn't always required to build effective e-commerce by executing a robust, database-free checkout system inside a free blogging platform.

**Striking Brand Presentation**<br />
Created a memorable, visually aggressive interface that perfectly balanced large-scale imagery with lightweight performance metrics.

**Zero Overhead Infrastructure**<br />
Shipped a highly stylized web presence that requires completely zero monthly hosting costs or backend engineering upkeep for the client.

<br /><strong><a href="https://killapinas.com/">View project</a></strong>
