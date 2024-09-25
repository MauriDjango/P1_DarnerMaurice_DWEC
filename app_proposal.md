# Adeptus Nexus

###### Tabletop Game Community Application

---

### Application Proposal

---

# Table of Contents

1. [Description](#description)
2. [Target Audience](#target-audience)
3. [Market Analysis](#market-analysis)
4. [Key Features](#key-features)
5. [Selected Technologies for Development](#selected-technologies-for-development)
6. [Conclusion](#conclusion)

---

## Description

Connecting an army of loyal fans, hobbyists, artists, vendors, and newcomers all in one App. Whilst not having to manage
multiple communities and platforms at once the app, adeptly named **Adeptus Nexus**,  aims to be the one-stop-shop for 
all things Warhammer 40k. Providing a marketplace for players to sell and trade their miniatures, painters and craftsman
to offer their services, and a forum for players to discuss tactics, lore, and share their latest creations.

---

## Target Audience

The focus of this app is on the everyday player and hobbyist. Whilst still providing a space for professional stores
and vendors. Vendors already have their own dedicated space to sell their products and services which is something the 
players are currently lacking, at least in a consolidated and easy to manage fashion. Players see themselves having to
navigate several platforms and communities to find the product or information  that they are looking for and a majority
of the time these platform are not solely dedicated to the world of Warhammer 40k and thus can be found lacking in detail
or specifics needed to provide players with everything they need.

---

## Market Analysis

The market for Warhammer 40k is a niche market, but it is a market that is growing and has an incredibly loyal and dedicated 
player and fan base. With the release of the 10th edition and various celebrities such as Henry Cavill, Trey Parker, and
Ed Sheeran just to name a few, being open about their love for the game, the market is only going to continue to grow. - 
[SpikeyBits Article](https://spikeybits.com/warhammer-40k/celebrities/). However, the issue for most current players and 
others who would like to join in on the fun is the price of new models as well as paints and other hobby supplies. So at
any point where a player wants to add to or modify their army of miniatures they are looking at a hefty price tag. This
leads to many players looking for second hand models or trading with other players to get what they need. This is where 
the app comes in, providing a platform for players to sell and trade their models and other hobby supplies.

### Currently Available Platforms
As of now players look to platforms such as Facebook Marketplace, Wallapop, Ebay, and even self created Whatsapp groups to
find what they are looking for. However, these platforms are not solely dedicated to Warhammer 40k and thus can be found 
lacking in details or information that players need to make an informed decisions or for new players to get a foot into 
the doorway of the world of Warhammer 40k and make their first purchase.

### What the App Provides
As you can imagine this leaves a void between official stores and online marketplaces where the Warhammer community is 
not being  catered to. This is where Adeptus Nexus comes in, a place where all things Warhammer can be found. A place 
where players can find opportunities to mold their part of the universe as they see fit. Where they can research and learn 
about where their Warhammer journey is heading. And where they can be kept up to date on community evens and tournaments.

---

## Key Features

---

### The Forge
- **Marketplace Functionality**: Players can create listings to sell and trade miniatures, paints, books, and other hobby supplies.
    - **User-Generated Listings**: Users can add detailed descriptions, photos, and prices to their listings.
    - **Search and Filter Options**: Users can easily search for specific items and filter results based on categories, 
  price range, or condition.

- **Service Offerings**: In addition to physical products, users can offer services such as painting, terrain building, 
or hosting gaming sessions.
    - **Profile Creation**: Service providers can create profiles highlighting their skills, past works, and customer reviews.

### The Librarius
- **Lore Repository**: A comprehensive database for Warhammer lore, including access to summaries, character bios, and historical contexts.
    - **Discussion Forums**: Dedicated sections for players to engage in discussions, share theories, and ask questions about the lore.
    - **Resource Sharing**: Users can contribute articles, fan fiction, or homebrew lore expansions.

### The Strategium
- **Rules and Tactics Hub**: A centralized location for the latest rules, strategies, and updates relevant to gameplay.
    - **Event Calendar**: Users can view and add local tournaments and events, with options for RSVPing and sharing details.
    - **Tactical Guides**: A collection of articles and videos that provide strategies for gameplay, unit comparisons, 
  and effective army compositions.

### The Front Line
- **News Aggregation**: A feed for the latest news, product releases, and lore updates related to the Warhammer universe.
    - **Personalized Alerts**: Users can opt-in for notifications about new releases or updates relevant to their interests.

### The Citadel
- **Community Forum**: A space for users to create threads on any Warhammer-related topic, from hobby tips to game experiences.
    - **Networking Opportunities**: Users can find allies for collaborations, share project ideas, or even recruit players for games.
    - **Showcase Gallery**: Members can post images of their creations, receive feedback, and participate in themed contests.

---

## Selected Technologies for Development

1. HTML (Hypertext Markup Language)

Justification: HTML is the standard markup language for creating web pages. It provides the structure for the application,
allowing developers to define the content and layout effectively. As a foundational technology, HTML is crucial for 
building a user interface that is both accessible and easy to navigate for users of all backgrounds.

2. CSS (Cascading Style Sheets)

Justification: CSS is essential for styling the web application, enhancing the visual presentation and user experience. 
By separating content (HTML) from design (CSS), the application can be more maintainable and adaptable. CSS frameworks 
such as Bootstrap or Tailwind can be used to accelerate development and ensure responsive design across various devices, 
which is vital for reaching a broader audience.

3. JavaScript

Justification: JavaScript is a dynamic programming language that enables interactivity on the client side. It allows 
developers to create responsive user interfaces, handle user input, and manipulate the Document Object Model (DOM) in 
real time.

4. React

Justification: React is a powerful JavaScript library for building user interfaces, particularly single-page applications 
(SPAs). It enables developers to create reusable UI components, which improves code maintainability and scalability. 
React’s virtual DOM optimizes rendering performance, ensuring a smooth user experience, even as the application grows in
complexity. Additionally, its component-based architecture fits well with the needs of a community-driven platform like 
Adeptus Nexus, allowing for dynamic updates and interactions without page reloads.

5. Spring Framework

Justification: The Spring Framework is a powerful Java-based framework that simplifies the development of enterprise 
applications. It promotes best practices such as dependency injection, aspect-oriented programming, and MVC 
(Model-View-Controller) architecture. Using Spring Boot, developers can quickly set up RESTful APIs to communicate between
the client and server, which is crucial for building a responsive and efficient application. The built-in security features 
of Spring also provide an additional layer of protection for user data.

6. Java Persistence API (JPA)

Justification: JPA is a specification that facilitates object-relational mapping (ORM) in Java applications. It simplifies
database interactions by allowing developers to work with Java objects rather than SQL queries directly. This abstraction
improves code readability and maintainability. In the context of your application, JPA will be used to manage the persistence
of user data, marketplace listings, and other essential entities, ensuring data integrity and seamless communication with
the underlying database.

### Conclusion

The selected technologies for the Adeptus Nexus application are strategically chosen to support the goals of providing a robust, user-friendly, and scalable platform for the Warhammer 40k community. By utilizing a combination of HTML, CSS, JavaScript, React, Spring, and JPA, the application will be well-equipped to handle user needs and provide a rich experience for its target audience.

---