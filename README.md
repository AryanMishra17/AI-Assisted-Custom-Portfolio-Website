# AI-Assisted-Custom-Portfolio-Website

This is a portfolio website for showcasing the work and skills of a Web Developer named Aryan Mishra. The website includes sections for home, about, resume, projects, and contact.

## Features

- Home section with an introduction and contact button.
- About section with a brief description and image.
- Resume section with a carousel showcasing experience, certifications, and skills.
- Projects section with a grid of project images and links to detailed project pages.
- Contact section with a feedback form to send messages via EmailJS.
- Responsive design using Tailwind CSS and Bootstrap.
- Vertical navigation menu for easy access to different sections.

## Technologies Used

- HTML
- CSS (Tailwind CSS, Bootstrap)
- JavaScript
- EmailJS
- Font Awesome
- Animate.css

## Setup Instructions

1. Clone the repository to your local machine.
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory.
    ```sh
    cd finalportfolio
    ```
3. Open the `index.html` file in your preferred web browser.

## Usage

1. Navigate through the different sections using the navigation menu.
2. Click on project images in the Projects section to view detailed project pages.
3. Use the contact form in the Contact section to send messages.

## EmailJS Setup

The contact form uses EmailJS to send messages. You need to provide your own EmailJS public key and service/template IDs.

1. Sign up at [EmailJS](https://www.emailjs.com/) to get your public key and service/template IDs.
2. Replace the placeholders in the `index.html` file with your EmailJS public key and service/template IDs.
    ```html
    <script type="text/javascript">
    (function(){
      emailjs.init({
        publicKey: "Your_public_key",
      });
    })();
    </script>
    <!-- ...existing code... -->
    emailjs.send("Service_id", "template_ID", formData)
    ```

