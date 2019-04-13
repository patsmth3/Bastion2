# Bastion2

Summary:

Bastion is a user-friendly app designed to help active duty and veterans and their families find simple resources based on their location. The categories they can choose from are Deals/Discounts, Financial Planning, Personal Growth, Small Business Support, and Housing Information. Likewise, a business may sign up to be included in the Bastion database to be listed as being veteran-owned and/or list any miltary specialty or discount service they offer.

Technical:

Bastion keeps all services and businesses who apply to be a part of the community in a database. By filling out their specific application, the business will receive a response that Bastion will go over their application. A post request is sent to admin who will verify the specilaty and service provided to veterans. Once added, the business is a part of the databse.

The user will be prompted to choose what service they would like to partake in, by choosing from the five categories: Deals/Discounts, Financial Planning, Personal Growth, Small Business Support, and Housing Information. Once chosen, there may be an additional parameter(s) needed to help locate and find what the user is looking for. A get request is sent to the database which will post a new page listing all of the businesses that meet the chosen paramater(s). The business will list its name, address, specialty/discount, and whether it is veteran owned or not.
