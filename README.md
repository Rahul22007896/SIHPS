# Smart India Hackathon Workshop
# Date:17.05.2024
## Register Number:212221043006
## Name:Rahul.K
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
This website aims to simplify e-waste disposal and educate users about its importance. It will combine a facility locator with educational pop-ups and a potential reward system.


## Proposed Solution / Architecture Diagram
Frontend:

User Interface (UI): A user-friendly website with a map displaying nearby e-waste collection centers.
Search Bar: Users can search for specific facilities by location or zip code.
Educational Pop-Ups: Informative messages explaining the dangers of improper e-waste disposal and highlighting harmful components.
Device Input Option: (Optional) Users input their device model for potential reward calculation.
Backend:

Database: Stores facility locations, e-waste information (harmful components), and (optional) device model data with associated points for recovered materials.
Geolocation API: Integrates with the map to display user location and nearby facilities.
Reward System API: (Optional) Calculates points based on device model data (precious metal content).
Content Management System (CMS): Allows for easy updates to educational pop-up content.

![Workflow-of-E-Waste-Recycling-through-Third-Party-Recycler](https://github.com/Rahul22007896/SIHPS/assets/121565560/b45dacfa-ca7f-47d7-8239-02ebdc7e001a)


## Use Cases
User: Locates the nearest e-waste collection center using the map or search bar. Learns about the dangers of improper e-waste disposal through pop-ups. (Optional) Earns points for responsible disposal based on the device model.
Administrator: Manages the database (facility locations, e-waste info) and CMS for educational content. Oversees (optional) reward system configuration.
![Use-case-diagram-of-the-plastics-paper-waste-management-system-Source-Authors-Design](https://github.com/Rahul22007896/SIHPS/assets/121565560/9246749f-683e-4eb0-8388-74922ec62446)

## Technology Stack
Frontend: HTML, CSS, JavaScript (e.g., ReactJS)
Backend: Python (with Django framework) or NodeJS (with Express framework)
Database: PostgreSQL or MongoDB
Geolocation API: Google Maps Platform or OpenStreetMap
Reward System API: (Optional) Custom API or integration with a third-party points system provider

## Dependencies
Internet access for website functionality and map display.
User location sharing for automatic facility recommendation (optional).
