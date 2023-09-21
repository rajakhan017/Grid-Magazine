# Grid-Magazine

## [Live Website Link!] https://rajakhan017.github.io/Grid-Magazine/

### Structure of the web page
img src="./webpage.jpg" width="700px" alt="structure of the webpage"  />

#### \* (Universal Selector)

| Property     | Value        | Description                                                                                                                                          |
| ------------ | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| `padding`    | `0`          | Reset padding for all elements to 0.                                                                                                                 |
| `margin`     | `0`          | Reset margin for all elements to 0.                                                                                                                  |
| `box-sizing` | `border-box` | Set the box-sizing property for all elements to "border-box," ensuring that padding and border are included in the element's total width and height. |

**Selector Explanation:** The `*` selector targets all elements in the HTML document.
![image](https://github.com/rajakhan017/Grid-Magazine/assets/135150598/a4e3106a-f720-4942-81f9-61ffe08bb952)

#### ::before and ::after Pseudo-Elements

| Property  | Value | Description                                                |
| --------- | ----- | ---------------------------------------------------------- |
| `content` | `" "` | Add empty content to ::before and ::after pseudo-elements. |

**Selector Explanation:** The `::before` and `::after` pseudo-elements are used to insert content before and after the content of elements.

#### html

| Property    | Value   | Description                                                                                                                                                     |
| ----------- | ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `font-size` | `62.5%` | Set the base font size for the HTML document to 62.5% (10px when the default font size is 16px), making it easier to work with rem units for responsive design. |

**Selector Explanation:** The `html` selector targets the root HTML element.
![image](https://github.com/rajakhan017/Grid-Magazine/assets/135150598/c81c3b30-ac53-453f-ba18-f7c0c2ee8429)

#### body

| Property           | Value                   | Description                                                                                     |
| ------------------ | ----------------------- | ----------------------------------------------------------------------------------------------- |
| `font-family`      | `'Baskervville', serif` | Set the font family for the entire body of the document to 'Baskervville' and use a serif font. |
| `color`            | `linen`                 | Set the text color for the body to "linen."                                                     |
| `background-color` | `rgb(20, 30, 40)`       | Set the background color of the body to a dark blueish-gray color (rgb(20, 30, 40)).            |

**Selector Explanation:** The `body` selector targets the entire body of the HTML document.
![image](https://github.com/rajakhan017/Grid-Magazine/assets/135150598/3bb8e1fe-69dc-41b5-bb1d-e469ac3e8bac)

#### h1, h2, h3, h4, h5, h6

| Property      | Value                   | Description                                                     |
| ------------- | ----------------------- | --------------------------------------------------------------- |
| `font-family` | `'Anton', sans-serif`   | Set specific font families for heading elements (`h1` to `h6`). |
|               | `'Raleway', sans-serif` |                                                                 |

**Selector Explanation:** The `h1`, `h2`, `h3`, `h4`, `h5`, and `h6` selectors target heading elements and set specific font families for each.

#### a

| Property          | Value   | Description                                                       |
| ----------------- | ------- | ----------------------------------------------------------------- |
| `text-decoration` | `none`  | Remove text decoration (underlines) from anchor (`<a>`) elements. |
| `color`           | `linen` | Set the text color of anchor (`<a>`) elements to "linen."         |

**Selector Explanation:** The `a` selector targets anchor (`<a>`) elements and sets their text decoration and color.

#### main

| Property                | Value                                                            | Description                                                                                                                                            |
| ----------------------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `display`               | `grid`                                                           | Set the element with the class "main" to use a grid layout.                                                                                            |
| `grid-template-columns` | `minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr)` | Define three columns for the grid layout, with the middle column adapting to the content size and the other columns having minimum and maximum widths. |
| `row-gap`               | `3rem`                                                           | Set the gap (spacing) between rows in the grid to 3rem.                                                                                                |

**Selector Explanation:** The `.main` selector targets elements with the class "main."

#### img

| Property     | Value   | Description                                                                               |
| ------------ | ------- | ----------------------------------------------------------------------------------------- |
| `width`      | `100%`  | Set the width of all `<img>` elements to 100% to ensure they scale with their containers. |
| `object-fit` | `cover` | Scale and crop images to cover the entire container while maintaining their aspect ratio. |

**Selector Explanation:** The `img` selector targets all `<img>` elements.

#### hr

| Property | Value                                | Description                                                                    |
| -------- | ------------------------------------ | ------------------------------------------------------------------------------ |
| `margin` | `1.5rem 0`                           | Add margin to the top and bottom of all `<hr>` elements.                       |
| `border` | `1px solid rgba(120, 120, 120, 0.6)` | Set the border properties for all `<hr>` elements to create a horizontal line. |

**Selector Explanation:** The `hr` selector targets all `<hr>` elements.

#### .heading

| Property                | Value            | Description                                                                            |
| ----------------------- | ---------------- | -------------------------------------------------------------------------------------- |
| `grid-column`           | `2 / 3`          | Place elements with the class "heading" in the second column of the grid.              |
| `display`               | `grid`           | Set the elements with the class "heading" to use a grid layout.                        |
| `grid-template-columns` | `repeat(2, 1fr)` | Define two equally sized columns within elements with the class "heading."             |
| `row-gap`               | `1.5rem`         | Set the gap (spacing) between rows within elements with the class "heading" to 1.5rem. |

**Selector Explanation:** The `.heading` selector targets elements with the class "heading."

#### .text

| Property         | Value     | Description                                                                                           |
| ---------------- | --------- | ----------------------------------------------------------------------------------------------------- |
| `grid-column`    | `2 / 3`   | Place elements with the class "text" in the second column of the grid.                                |
| `font-size`      | `1.8rem`  | Set the font size for elements with the class "text" to 1.8rem.                                       |
| `letter-spacing` | `0.6px`   | Add letter spacing to elements with the class "text" for improved readability.                        |
| `column-width`   | `25rem`   | Set the column width for elements with the class "text" to 25rem, allowing text to flow into columns. |
| `text-align`     | `justify` | Justify the text alignment within elements with the class "text."                                     |

**Selector Explanation:** The `.text` selector targets elements with the class "text."

#### .hero

| Property      | Value      | Description                                                                   |
| ------------- | ---------- | ----------------------------------------------------------------------------- |
| `grid-column` | `1 / -1`   | Span elements with the class "hero" across all columns of the grid.           |
| `position`    | `relative` | Position elements with the class "hero" as relative within the document flow. |

**Selector Explanation:** The `.hero` selector targets elements with the class "hero."

#### .hero-title

| Property     | Value       | Description                                                              |
| ------------ | ----------- | ------------------------------------------------------------------------ |
| `text-align` | `center`    | Center-align text within elements with the class "hero-title."           |
| `color`      | `orangered` | Set the text color of elements with the class "hero-title" to orangered. |
| `font-size`  | `8rem`      | Set the font size for elements with the class "hero-title" to 8rem.      |

**Selector Explanation:** The `.hero-title` selector targets elements with the class "hero-title."

#### .hero-subtitle

| Property     | Value       | Description                                                                 |
| ------------ | ----------- | --------------------------------------------------------------------------- |
| `font-size`  | `2.4rem`    | Set the font size for elements with the class "hero-subtitle" to 2.4rem.    |
| `color`      | `orangered` | Set the text color of elements with the class "hero-subtitle" to orangered. |
| `text-align` | `center`    | Center-align text within elements with the class "hero-subtitle."           |

**Selector Explanation:** The `.hero-subtitle` selector targets elements with the class "hero-subtitle."

#### .author

| Property      | Value                   | Description                                                            |
| ------------- | ----------------------- | ---------------------------------------------------------------------- |
| `font-size`   | `2rem`                  | Set the font size for elements with the class "author" to 2rem.        |
| `font-family` | `'Raleway', sans-serif` | Set the font family for elements with the class "author" to 'Raleway'. |

**Selector Explanation:** The `.author` selector targets elements with the class "author."

#### .author-name a:hover

| Property           | Value     | Description                                                                                                                                     |
| ------------------ | --------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| `background-color` | `#306203` | Change the background color of anchor (`<a>`) elements within elements with the class "author-name" when hovering over them to #306203 (green). |

**Selector Explanation:** The `.author-name a:hover` selector targets anchor (`<a>`) elements within elements with the class "author-name" when hovered over.

#### .publish-date

| Property | Value                      | Description                                                                               |
| -------- | -------------------------- | ----------------------------------------------------------------------------------------- |
| `color`  | `rgba(255, 255, 255, 0.5)` | Set the text color of elements with the class "publish-date" to a semi-transparent white. |

**Selector Explanation:** The `.publish-date` selector targets elements with the class "publish-date."

#### .social-icons

| Property                | Value            | Description                                                                      |
| ----------------------- | ---------------- | -------------------------------------------------------------------------------- |
| `display`               | `grid`           | Set the elements with the class "social-icons" to use a grid layout.             |
| `font-size`             | `3rem`           | Set the font size for elements with the class "social-icons" to 3rem.            |
| `grid-template-columns` | `repeat(5, 1fr)` | Define five equally sized columns within elements with the class "social-icons." |
| `grid-auto-flow`        | `column`         | Automatically place grid items in columns.                                       |
| `grid-auto-columns`     | `1fr`            | Define each column's width as 1fr (equal width).                                 |
| `align-items`           | `center`         | Vertically center-align items within elements with the class "social-icons."     |

**Selector Explanation:** The `.social-icons` selector targets elements with the class "social-icons."

#### .first-paragraph::first-letter

| Property       | Value       | Description                                                            |
| -------------- | ----------- | ---------------------------------------------------------------------- |
| `font-size`    | `6rem`      | Set the font size for the first letter of the first paragraph to 6rem. |
| `color`        | `orangered` | Set the color of the first letter to orangered.                        |
| `float`        | `left`      | Float the first letter to the left of the text.                        |
| `margin-right` | `1rem`      | Add right margin to the first letter for spacing.                      |

**Selector Explanation:** The `.first-paragraph::first-letter` selector targets the first letter of the first paragraph.

#### .quote

| Property      | Value                   | Description                                                                     |
| ------------- | ----------------------- | ------------------------------------------------------------------------------- |
| `color`       | `#00beef`               | Set the text color of elements with the class "quote" to #00beef (bright blue). |
| `font-size`   | `2.4rem`                | Set the font size for elements with the class "quote" to 2.4rem.                |
| `text-align`  | `center`                | Center-align text within elements with the class "quote."                       |
| `font-family` | `'Raleway', sans-serif` | Set the font family for elements with the class "quote" to 'Raleway'.           |

**Selector Explanation:** The `.quote` selector targets elements with the class "quote."

#### .quote::before and .quote::after Pseudo-Elements

| Property  | Value | Description                                                                                           |
| --------- | ----- | ----------------------------------------------------------------------------------------------------- |
| `content` | `" "` | Add empty content to the ::before and ::after pseudo-elements within elements with the class "quote." |

**Selector Explanation:** The `.quote::before` and `.quote::after` pseudo-elements are used to insert empty content before and after elements with the class "quote."

#### .text-with-images

| Property                | Value     | Description                                                                                                                                       |
| ----------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| `display`               | `grid`    | Set elements with the class "text-with-images" to use a grid layout.                                                                              |
| `grid-template-columns` | `1fr 2fr` | Define a grid with two columns, where the first column occupies one fraction of the available space and the second column occupies two fractions. |
| `column-gap`            | `3rem`    | Set the gap (spacing) between columns within elements with the class "text-with-images" to 3rem.                                                  |
| `margin-bottom`         | `3rem`    | Add margin to the bottom of elements with the class "text-with-images" for spacing.                                                               |

**Selector Explanation:** The `.text-with-images` selector targets elements with the class "text-with-images."

#### .lists

| Property          | Value  | Description                                                                                             |
| ----------------- | ------ | ------------------------------------------------------------------------------------------------------- |
| `list-style-type` | `none` | Remove the default list-style type (bullet or number) for lists within elements with the class "lists." |
| `margin-top`      | `2rem` | Add margin to the top of lists within elements with the class "lists" for spacing.                      |

**Selector Explanation:** The `.lists` selector targets lists within elements with the class "lists."

#### .lists li

| Property        | Value    | Description                                                                                |
| --------------- | -------- | ------------------------------------------------------------------------------------------ |
| `margin-bottom` | `1.5rem` | Add margin to the bottom of list items within elements with the class "lists" for spacing. |

**Selector Explanation:** The `.lists li` selector targets list items within elements with the class "lists."

#### .list-title and .list-subtitle

| Property | Value     | Description                                                                                              |
| -------- | --------- | -------------------------------------------------------------------------------------------------------- |
| `color`  | `#00beef` | Set the text color of elements with the class "list-title" and "list-subtitle" to #00beef (bright blue). |

**Selector Explanation:** The `.list-title` and `.list-subtitle` selectors target elements with the classes "list-title" and "list-subtitle."
![image](https://github.com/rajakhan017/Grid-Magazine/assets/135150598/07df5190-0de8-4e87-83d5-7774934e916f)

#### .image-wrapper

| Property                | Value                    | Description                                                                                                                                       |
| ----------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| `display`               | `grid`                   | Set elements with the class "image-wrapper" to use a grid layout.                                                                                 |
| `grid-template-columns` | `2fr 1fr`                | Define a grid with two columns, where the first column occupies two fractions of the available space and the second column occupies one fraction. |
| `grid-template-rows`    | `repeat(3, min-content)` | Define three rows with minimum content height for elements with the class "image-wrapper."                                                        |
| `gap`                   | `2rem`                   | Set the gap (spacing) between grid items within elements with the class "image-wrapper" to 2rem.                                                  |
| `place-items`           | `center`                 | Center-align grid items both horizontally and vertically within elements with the class "image-wrapper."                                          |

**Selector Explanation:** The `.image-wrapper` selector targets elements with the class "image-wrapper."

#### .image-1 and .image-3

| Property      | Value    | Description                                                                            |
| ------------- | -------- | -------------------------------------------------------------------------------------- |
| `grid-column` | `1 / -1` | Span elements with the classes "image-1" and "image-3" across all columns of the grid. |

**Selector Explanation:** The `.image-1` and `.image-3` selectors target elements with the classes "image-1" and "image-3" respectively and span them across all columns of the grid.

#### Media Queries (Responsive Styling)

The provided CSS includes media queries for responsive design, adapting styles for different screen sizes.

##### @media only screen and (max-width: 720px)

| Property         | Value                         | Description                                                                                                                   |
| ---------------- | ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| `.image-wrapper` | `grid-template-columns: 1fr;` | Change the grid layout to a single column for elements with the class "image-wrapper" when the screen width is 720px or less. |

**Media Query Explanation:** This media query modifies the grid layout for elements with the class "image-wrapper" when the screen width is 720px or less.

##### @media only screen and (max-width: 600px)

| Property            | Value                         | Description                                                                                                                      |
| ------------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `.text-with-images` | `grid-template-columns: 1fr;` | Change the grid layout to a single column for elements with the class "text-with-images" when the screen width is 600px or less. |

**Media Query Explanation:** This media query modifies the grid layout for elements with the class "text-with-images" when the screen width is 600px or less.

##### @media only screen and (max-width: 550px)

| Property                                             | Value                | Description                                                                                                    |
| ---------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------------------------------------- |
| `.hero-title`                                        | `font-size: 6rem;`   | Reduce the font size of elements with the class "hero-title" to 6rem when the screen width is 550px or less.   |
| `.hero-subtitle`, `.author`, `.quote`, `.list-title` | `font-size: 1.8rem;` | Reduce the font size for various elements to 1.8rem when the screen width is 550px or less.                    |
| `.social-icons`                                      | `font-size: 2rem;`   | Reduce the font size of elements with the class "social-icons" to 2rem when the screen width is 550px or less. |
| `.text`                                              | `font-size: 1.6rem;` | Reduce the font size of elements with the class "text" to 1.6rem when the screen width is 550px or less.       |

**Media Query Explanation:** This media query adjusts font sizes and styles for various elements when the screen width is 550px or less.

##### @media only screen and (max-width: 420px)

| Property      | Value                | Description                                                                                                    |
| ------------- | -------------------- | -------------------------------------------------------------------------------------------------------------- |
| `.hero-title` | `font-size: 4.5rem;` | Reduce the font size of elements with the class "hero-title" to 4.5rem when the screen width is 420px or less. |

**Media Query Explanation:** This media query further reduces the font size of elements with the class "hero-title" when the screen width is 420px or less.

These media queries help ensure that the styles adapt to different screen sizes, providing a responsive user experience.
