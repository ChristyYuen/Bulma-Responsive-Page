# Bulma-Responsive-Page

## Description
This project is a webpage layout implemented using **Bulma CSS**. The page contains a header, an article section, and a bottom section for advertisements. No custom CSS is used; the entire layout adheres to the Bulma CSS framework. The page is designed to be responsive, rearranging the layout elements when the browser window is resized.

## Overview

The following criteria were followed to build the page:

1. **Bulma CSS Usage**
   - The page is styled using only **Bulma CSS**. No custom CSS was added.

2. **Page Structure**
   - The page consists of three main sections: 
     - **Header**: Contains the page title, a logo on the left, and the date on the right. The logo and title are centered vertically.
     - **Articles**: The main content is divided into three columns (except for the "Mountain Lions Sighted on Campus" title, which spans two columns).
     - **Bottom Section**: Contains ad tiles arranged into three columns.

3. **Header Layout**
   - The title has the **logo on the left** and the **date on the right**.
   - Both the title and the logo are **centered vertically**.

4. **Article Section Layout**
   - The middle section is divided into **3 columns** using Bulma's `columns` class.
   - The article titled **"Mountain Lions Sighted on Campus"** spans the two leftmost columns.
   - The article titles **"Mountain Lions Sighted on Campus"** and **"Professor de Alfaro..."** are aligned horizontally, with the **same font size** and their tops starting from the same vertical line.
   - **Subtitles** are larger than the main text for better readability.
   - Images are placed in appropriate Bulma boxes and fit within the width of the left column.

5. **Advertisement Section Layout**
   - The ad section is divided into **three columns** vertically:
     - **Ad1** and **Ad2** are in the left column.
     - **Ad3** and **Ad4** are in the central column.
     - **Ad5** is in the right column.
     - **Ad6** spans both the middle and right columns.
   - Ads are arranged with proper height and spacing: 
     - Ad1 and Ad2 take up half the vertical space of their column each.
     - Ad3, Ad4, and Ad6 each occupy one-third vertical space.
     - Ad5 takes two-thirds vertical space.
   - Ads are styled with **correct colors** based on the design specification.

6. **Responsive Design**
   - The layout is responsive:
     - When the page is narrowed, the **three columns** stack vertically.
     - The **ad tiles** also rearrange themselves to fit in a single column as the page shrinks.

7. **HTML Code Quality**
   - The HTML is structured in a **readable** format, with proper indentation and logical element organization. The code avoids being compressed into a single line.

## Instructions to Run

1. Clone the repository.
2. Open the `index.html` file in your preferred web browser.
3. Resize the browser window to see how the layout adapts to different screen sizes.

## Technologies Used
- **HTML**
- **Bulma CSS**
