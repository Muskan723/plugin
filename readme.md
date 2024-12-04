Description
A custom plugin for managing logistics services, including shipment tracking, booking, and cost estimation.

Plugin Aim
The "Muskan Logistics" plugin is designed to manage logistics services. Its main features include:

Cost Estimation: The plugin calculates and provides estimated shipping costs for users based on input criteria.

How It Is Created: 

Steps Description
Plugin Overview: The plugin is created to be integrated into WordPress websites to provide logistics-related services. It is likely built using PHP, which is the primary language for WordPress plugin development, and it also uses HTML and CSS for the front-end interface.

Plugin Structure:

Main PHP File: The plugin would have a main PHP file, which defines its functionality and registers it with WordPress. This includes defining shortcodes (like [shipping_calculator]) that the user can place in a post or page.
Shortcode: The plugin uses a shortcode [shipping_calculator] to generate the user interface on the WordPress site. When users visit the page containing this shortcode, they can interact with the logistics service features.
Form for Input: The user interface (UI) is likely built using HTML forms where users enter shipping details (e.g., weight, dimensions, and destination). Based on this input, the plugin processes the data and shows relevant information such as cost estimation or booking options.
CSS Styling: The plugin includes simple CSS for styling the content, making the form and output easy to read and visually appealing.

Steps to Create the Plugin:
Step 1: Create the Plugin Folder & Files: First, the plugin is structured by creating a folder (e.g., muskan-logistics) in the wp-content/plugins directory. Inside this folder, the necessary PHP file is created (likely muskan-logistics.php), as well as any additional files like style.css for front-end design.
Step 2: Register the Plugin with WordPress: The main PHP file defines the plugin using WordPress hooks. These hooks allow WordPress to recognize and activate the plugin.
Step 3: Define the Shortcode Function: The functionality to create a shortcode [shipping_calculator] is defined in the PHP code. This shortcode generates a custom form and handles the submission data to perform calculations or trigger other actions like booking or tracking.
Step 4: Handle User Input: The plugin processes the user inputs submitted through the form. These inputs are likely used to calculate shipping costs or to query a logistics service for real-time data.
Step 5: Display Results: Based on the calculations or results from the logistics service, the plugin displays output (e.g., cost estimate, shipment tracking details, or booking confirmation).
Step 6: Test and Debug: Finally, the plugin is tested in a WordPress environment to ensure it functions correctly. This includes checking for accurate cost estimation, form validation, and shipment tracking.
Step 7: Packaging & Distribution: Once tested, the plugin is packaged as a .zip file (as seen in the provided download link) and can be distributed for installation on other WordPress websites.

Deployment:
Online Testing: The plugin can be tested and accessed online using a URL like the one provided: Muskan Logistics Plugin Running Online.
https://muskan-logistics.chandigarhitsolutions.com/calculator/
Zip File for Installation: The plugin can be downloaded as a zip file (provided in the link) and uploaded to a WordPress site for installation.
https://muskan-logistics.chandigarhitsolutions.com/wp-content/plugins/muskan-logistics.zip

Conclusion
This WordPress plugin is designed to streamline logistics-related tasks like shipment tracking, booking, and cost estimation. The plugin leverages WordPress's flexible structure, including PHP for functionality, HTML for the interface, and CSS for styling.

