# 01 Project - Online Shop 

## Assessment details

- [Level 5 Learning Outcomes](./docs/learning-outcomes-l5.md)
- [Level 6 Learning Outcomes](./docs/learning-outcomes-l6.md)
- Marking criteria is included with Google Classroom assignment

---

## Brief

A client has come to you with a list of products and needs you to build them an online shop. They have provided a rough idea of the layout they want, and the content in a Google Document. You will need to design and build a website from these requirements.

- [Online shop brief](https://docs.google.com/document/d/1kmVX2zJp8nHw_tvvPreD3XngkATWaUAg_npKg0gDzrw/edit?usp=sharing)

The website needs to work across multiple screen sizes and use design principles to make the content easy to read. It needs to use semantic HTML and CSS for the page design.

## Rationale

Taking requirements from a customer and turning them into a website is a common requirement in the software industry. Ensuring you can translate design and content into semantic HTML, and writing good quality CSS is a critical skill as a web developer.

## Instructions Part A - Home page

The approach you can take when building this site is to build page by page, starting with your mobile design and working your way upwards.

Make sure you commit to git very regularly throughout your development process. Write clear commit messages such as "Create HTML content for the product listing page". 

1. Read the brief, and make sure you understand all the requirements. Clarify with your instructor if anything is not clear.
2. Create a file in the Submission folder for your HTML, name it `index.html`, and add all the HTML content for the home page, including the header
3. Create a CSS file in your Submission folder names `style.css`, and link it to your `index.html` file
4. Start with your mobile design. Add all your base CSS such as heading font sizes, line heights, general colours of the text etc. Complete the design for mobile.
5. Add a media query for your next screen size, and add a CSS grid. Add any extra CSS you need in this media query for the medium screen.
6. Add another media query for your large screen size, and update the CSS grid properties if required. Add any extra CSS you need in this media query for the medium screen.

## Instructions Part B - Single product page

1. Choose a single product from the brief, and build the page for that product first.
2. Create a file in the Submission folder for your HTML, name it `product1.html` (or something appropriate), and add all the HTML content for the product, including the header
3. Following the process outlined in Part A to complete the design for the product page. You might need a different grid for the product page, you can achieve this by using a different class name for the grid container. 
4. Start with the mobile design first, then add the next screen size, and then the largest screen size. 
5. Once complete, you can create the other two product pages, and update the HTML content for them without changing the CSS. Link to these product pages from the home page. 

## Instructions Part C - Contact page

1. Choose a single product from the brief, and build the page for that product first.
2. Create a file in the Submission folder for your HTML, name it `contact.html`, and add all the HTML content for the contact page, including the header
3. Following the process outlined in Part A to complete the design for the contact page.
4. Start with the mobile design first, then add the next screen size, and then the largest screen size. 
5. Once complete, make sure all the navigation links to the contact page throughout the site.

--- 

# Submit your Project

- [ ] [Feedback](feedback.md) has been completed, and committed to git
- [ ] Commits are pushed to GitHub

---

<details>
  <summary>
    Git CLI Refresher
  </summary>

If you need help remembering what commands to type with `git`, use the following as a reference, or watch the [git walkthrough tutorial video](https://vimeo.com/433825571/bc1830fb90)

```shell
# when ready to commit and push
git add .

git commit -m "Added product HTML to the product listing page"

git push origin main
```

</details>
