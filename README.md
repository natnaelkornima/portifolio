# John Doe - Frontend Developer Portfolio 👨‍💻

This is a modern, responsive, single-page portfolio website for a frontend developer. It's built with HTML, Tailwind CSS, and vanilla JavaScript, featuring a clean design, dark/light mode, and interactive UI elements.

**Live Demo:** [your-live-url.com](https://your-live-url.com)

![Portfolio Screenshot](https://via.placeholder.com/800x450.png?text=Your+Portfolio+Screenshot)
*(Replace the URL above with a screenshot of your portfolio)*

---

## ## Features ✨

* **Fully Responsive:** Looks great on desktops, tablets, and mobile devices.
* **Dark/Light Mode:** Theme toggling with user preference saved in `localStorage`.
* **Interactive UI:** Smooth scrolling, active navigation highlighting, hover effects, and animations.
* **Dynamic Sections:**
    * **Hero Section:** With an animated text gradient and floating profile picture.
    * **Projects Showcase:** Featuring 3D flip cards to display project details.
    * **Skills Section:** With animated progress bars that activate on scroll.
    * **Testimonials:** A section to display client or peer feedback.
* **Functional Contact Form:** Integrated with **EmailJS** to receive messages directly in your inbox.
* **Modern Tech Stack:** Built with pure HTML, CSS, and JavaScript, styled with Tailwind CSS, and using Lucide for icons.
* **SEO Friendly:** Includes meta tags for description and keywords.

---

## ## Built With 🛠️

* **HTML5**
* **CSS3** (Custom Properties & Animations)
* [**Tailwind CSS**](https://tailwindcss.com/) - A utility-first CSS framework.
* [**JavaScript**](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - For interactivity and dynamic features.
* [**Lucide Icons**](https://lucide.dev/) - For clean and beautiful icons.
* [**EmailJS**](https://www.emailjs.com/) - For handling the contact form submissions without a backend.

---

## ## Getting Started 🚀

This project is a single `index.html` file with no build step required.

### ### Prerequisites

You just need a modern web browser.

### ### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```
3.  **Open the file:**
    Simply open the `index.html` file in your web browser to view the portfolio.

---

## ## Configuration ⚙️

To make this portfolio your own, you'll need to customize a few things directly in the `index.html` file.

1.  **Personal Information:**
    * Search for "John Doe" and replace it with your name.
    * Update the bio, about section text, and social media links (`#`).
    * Replace the placeholder images with your own. The hero image and about image URLs can be found in the `#home` and `#about` sections.

2.  **Projects:**
    * In the `#projects` section, update the project titles, descriptions, technologies, live demo links, and code repository links for each project card.

3.  **Skills:**
    * In the `#skills` section, adjust the skill names and percentage values. The width of the progress bars is set via inline styles (e.g., `style="width: 95%"`).

4.  **Contact Form (EmailJS):**
    * Go to [EmailJS](https://www.emailjs.com/) and create a free account.
    * Find your **User ID**, **Service ID**, and **Template ID**.
    * In the `<script>` section at the bottom of the `index.html` file, find and replace the placeholder values:

    ```javascript
    // Initialize EmailJS
    emailjs.init('YOUR_USER_ID'); // Replace with your EmailJS user ID

    // ...

    // Send the email
    emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this) // Replace with your IDs
    ```

5.  **CV/Resume:**
    * Find the "Download CV" button in the `#home` section and update the `href` attribute to point to your resume file.

---

## ## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## ## Contact

John Doe - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your-username/your-repo-name](https://github.com/your-username/your-repo-name)
