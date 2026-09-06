#  Piano


This project is a simple piano design created using **HTML and CSS**. I built it as part of my learning journey with **freeCodeCamp** to practice CSS layouts, positioning, and responsive design.

## About the Project

The project creates a visual piano keyboard using HTML elements and CSS. It includes:

* White piano keys
* Black piano keys
* A freeCodeCamp logo
* Responsive design using CSS media queries
* Different piano sizes for different screen widths

##  Technologies Used

* HTML5
* CSS3
* CSS Media Queries

##  Project Structure

```text
piano/
├── index.html
├── styles.css
└── README.md
```

##  What I Learned

While working on this project, I practiced:

* Using `div` elements to create the piano keys
* CSS `box-sizing`
* `position: relative` and `position: absolute`
* Using `float` for layout
* Creating black keys using the `::after` pseudo-element
* Using `@media` queries for responsive design
* Adjusting the piano size for different screen widths

##  Responsive Design

I used media queries to make the piano fit different screen sizes.

For screens **768px and below**, the piano becomes smaller:

```css
@media (max-width: 768px) {
  #piano {
    width: 358px;
  }

  .keys {
    width: 318px;
  }

  .logo {
    width: 150px;
  }
}
```

For screens between **769px and 1199px**, another size is applied:

```css
@media (max-width: 1199px) and (min-width: 769px) {
  #piano {
    width: 675px;
  }

  .keys {
    width: 633px;
  }
}
```

##  Purpose

The main purpose of this project was to improve my understanding of **CSS styling and responsive web design** while following a freeCodeCamp exercise.



Software Engineering Student
