# Reza Maliki Akbar - Personal Portfolio

![Portfolio Screenshot](https://placehold.co/800x400/1E293B/93C5FD?text=Portfolio+Preview)
*(Replace the placeholder above with a screenshot of your actual portfolio)*

This repository hosts the source code for my personal portfolio website, showcasing my skills, projects, experience, and educational background as a Mechatronics & Automation Engineer with a growing expertise in Data Analytics.

**View Live Portfolio:** [**your-username.github.io/your-repository-name/**](https://your-username.github.io/your-repository-name/)
*(Replace with your actual GitHub Pages URL, e.g., `https://malikiborneo.github.io/portfolio/` or your custom domain if you have one)*

---

## About Me

I'm Reza Maliki Akbar, a Mechatronics and Automation Engineer, hands-on maker, and versatile problem-solver with a deep passion for innovation. As a lifelong learner, I thrive on exploring new technologies and tackling fresh challenges to create impactful solutions. 🛠️🚀

My expertise spans programming, software engineering, robotics, autonomous systems, AI, and electronics, built upon a Bachelor's in Engineering Physics (ITS) and an Associate's in Mechatronics (Polman Bandung). This foundation is now enhanced by a comprehensive, scholarship-backed Full Stack Data Analytics program at RevoU. My career includes leading university robotics teams and significant experience in the defence and aerospace sector, where I've honed skills in cutting-edge technologies. I'm eager to leverage this unique blend of deep engineering knowledge and advanced data science capabilities.

---

## Features

This portfolio is a single-page application designed to be:
* **Responsive:** Adapts to various screen sizes (desktops, tablets, mobiles).
* **Interactive:** Includes hover effects, scroll-reveal animations, and interactive elements.
* **Modern & Elegant:** Utilizes a "metal carbon, blue, and silver" theme with a clean layout.

### Sections Included:

* **Home:** A hero section with a brief introduction and call-to-action buttons.
* **About:** A detailed summary of my background, passion, and core competencies.
* **Experience:** A timeline of my professional roles and responsibilities.
* **Projects:** A showcase of my key projects, including descriptions, technologies used, and relevant links.
* **Skills:** Categorized overview of my technical skills.
* **Education:** My academic qualifications and significant training programs.
* **Contact:** Ways to get in touch with me, including links to my professional profiles.

---

## Technologies Used

* **HTML5:** For the basic structure and content.
* **Tailwind CSS v3:** For styling and layout (via CDN).
* **JavaScript (Vanilla JS):** For mobile menu toggle and scroll-reveal animations.
* **Font Awesome:** For icons.
* **Google Fonts (Inter):** For typography.
* **GitHub Pages:** For hosting.

---

## Setup & Customization

This portfolio is designed to be easily customizable. To use this template for your own portfolio:

1.  **Fork this Repository (Optional):** If you're viewing this on GitHub.
2.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```
3.  **Customize `index.html`:**
    * **Personal Information:** Update the "About Me" section, experience, project details, skills, education, and contact information with your own.
    * **Images:** Replace placeholder images (profile picture, project screenshots) with your actual images. Place your images in an `assets` or `img` folder (you might need to create one) and update the `src` attributes in the HTML.
    * **Links:** Update all placeholder links (`#`, social media links, project links) to point to your resources.
    * **Color Theme (Optional):** The theme is defined using Tailwind CSS utility classes directly in the HTML and within the `<style>` block in the `<head>`. You can modify these classes to change colors, fonts, etc. Refer to the [Tailwind CSS Documentation](https://tailwindcss.com/docs) for class references.
4.  **Deploy to GitHub Pages:**
    * If your repository is named `your-username.github.io`, the site will be available at `https://your-username.github.io`.
    * If it's another repository name (e.g., `my-portfolio`), go to your repository settings on GitHub, navigate to the "Pages" section, select the branch to deploy from (usually `main` or `master`), choose the `/ (root)` folder, and save. Your site will be available at `https://your-username.github.io/my-portfolio/`.

---

## How to Replace Placeholder Images

* **Hero Profile Picture:**
    Search for:
    ```html
    <img src="[https://placehold.co/150x150/FFFFFF/4299E1?text=RMA](https://placehold.co/150x150/FFFFFF/4299E1?text=RMA)" alt="Reza Maliki Akbar" ...>
    ```
    Replace `https://placehold.co/150x150/FFFFFF/4299E1?text=RMA` with the path to your profile picture.

* **Project Card Images:**
    Search for image tags within the `project-card` divs, for example:
    ```html
    <img src="[https://placehold.co/600x400/1E293B/93C5FD?text=IoT+CyberSec](https://placehold.co/600x400/1E293B/93C5FD?text=IoT+CyberSec)" alt="IoT Cybersecurity Project" ...>
    ```
    Replace the `src` with the path to your project screenshot. Ensure your images are appropriately sized or use CSS/Tailwind classes to manage their display.

---

## License

This project is open source. You are free to use and modify the code for your own portfolio. If you wish to include a specific license, you can add it here (e.g., MIT License).
