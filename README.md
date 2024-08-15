
# CSS Project: Sidebar Menu with Social Media Links

This project is a **CSS-based sidebar navigation menu** with integrated **Font Awesome icons** and **Google Fonts**. The sidebar menu includes various navigation links and social media icons that expand and collapse based on user interaction.

## Features

- **Responsive Sidebar Menu**: Toggle the sidebar menu using the hamburger icon.
- **Font Awesome Icons**: Includes icons for menu items and social media links.
- **Hover Effects**: Smooth transitions when hovering over icons and menu items.
- **Google Fonts**: Uses the "Poppins" font family.
- **Social Media Links**: Includes icons for Facebook, Twitter, Instagram, and YouTube.

## Technologies Used

- **HTML5**: Structure of the page.
- **CSS3**: Styling for layout, fonts, and hover effects.
- **Google Fonts**: Used for custom fonts.
- **Font Awesome**: Used for icons in the menu and social media links.

## Getting Started

### Prerequisites

To view or modify this project, you need the following installed on your machine:

- A web browser (Google Chrome, Mozilla Firefox, etc.)
- A text editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone or download the project repository:

    ```bash
    git clone https://github.com/your-repo/css-sidebar-menu.git
    ```

2. Navigate to the project folder:

    ```bash
    cd css-sidebar-menu
    ```

3. Open the `index.html` file in your web browser.

### File Structure

```bash
├── index.html        # Main HTML file
├── style.css         # CSS styles for the page
└── photo (1).jpg     # Background image used in the project
```

### Customization

- **Background Image**: You can replace `photo (1).jpg` in the `main_box` class within the CSS file to change the background image of the page.
  
  ```css
  .main_box{
      background: url('your-image.jpg');
      height: 100vh;
      background-size: cover;
  }
  ```

- **Fonts**: The project uses the **Poppins** font family. You can change it by updating the font link in the `<head>` section of `index.html` and modifying the `font-family` in the `style.css` file.

  ```css
  font-family: "Your-Preferred-Font", sans-serif;
  ```

- **Icons**: The project includes **Font Awesome** icons. You can add or modify icons by visiting [Font Awesome](https://fontawesome.com/) and using the class names for different icons.

### Features Description

- **Hamburger Menu**: The hamburger icon (`<i class="fa-solid fa-bars"></i>`) toggles the sidebar on and off. This is done using the `<input type="checkbox" id="check" />` element that controls the visibility of the sidebar.
  
- **Sidebar Menu**: The sidebar contains a logo (`PT Photography`), navigation links, and social media icons. The sidebar slides in when the hamburger menu is clicked and slides out when the close (`<i class="fa-solid fa-xmark"></i>`) icon is clicked.

- **Social Media Links**: The social media section is located at the bottom of the sidebar and includes icons for Facebook, Twitter, Instagram, and YouTube. Each icon has a hover effect that increases its size slightly.

### CSS Key Components

- **Transition Effects**: Smooth transitions are applied to the sidebar and icons using the `transition` property for a better user experience.

  ```css
  .btn_one i, .btn_two i, .sidebar_menu {
      transition: all 0.2s linear;
  }
  ```

- **Hover Effects**: Icons grow in size when hovered, and the sidebar menu links get a subtle shadow.

  ```css
  .btn_one i:hover{
      font-size: 40px;
  }
  .sidebar_menu .menu li:hover{
      box-shadow: 0 0 4px rgb(255, 255, 255, 0.5);
  }
  .sidebar_menu .social_media i:hover{
      transform: scale(1.2);
  }
  ```

## License

This project is open-source and available under the MIT License.

---

This `README.md` gives an overview of the project and helps guide users on how to use and customize it.