Explanation:
Header: Contains the title and navigation bar.
Navigation Bar: Allows the user to navigate between different sections of the website.
Sections: Each section (Home, About Me, Projects, and Contact) is identified by an ID for easy navigation and reference.
CSS: Styles the website, including the layout, colors, and fonts.
Form in Contact Section: Allows visitors to send a message or inquiry.
About Me Section: In the "About Me" section, the img element is used to display your photo. Replace "path_to_your_photo.jpg" with the path to your photo file.
CSS Styling: The profile-pic class styles the image to appear as a circle. It sets the border-radius to 50% to create a circular shape, and object-fit is set to cover to ensure the image fills the space properly.
Hover Effect on Profile Picture: An event listener is added for mouseover and mouseout events on the profile picture (profile-pic). When the mouse hovers over the picture, it scales up slightly (scale(1.1)), and when the mouse leaves, it returns to its normal size (scale(1)).
Reveal Sections on Scroll: The revealSections function adds a CSS class (show) to each section as it comes into view while scrolling. This triggers a transition effect to fade in and slide each section up.
Event Listener for Scroll: An event listener is attached to the window object to call revealSections whenever a scroll event occurs.
