# Module-1-Challenge
Code Refactor
# Website Code Refactor

This project demonstrates the refactoring an existing website. The client, a marketing company, requested that their website have several improvements made to improve accessibility features, SEO performance, and code readability.

# Objective 

The primary objective of this effort was to augment the site's accessibility which will allow people with disabilities to access the site and improve SEO performance. The secondary objective was to reorganize the codebase to improve readability and ease future development. This was achieved in the following steps:

* Adapting non-descriptive div elements into semantic HTML elements 
* Consolidating pre-existing CSS code into robust general purpose classes 
* Restructuring CSS code to follow site layout
* Creating alt text for all site images.

(starting code) Below is a representative of the original codebase making use of div elements:
```HTML
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
```
(Improve code) Semantic HTML was implemented to improve readability, accessibility, and functionality:
```HTML
    <header>
        <h1>Hori<span>seo</span>n</h1>        
        <nav>
            <a href="#search-engine-optimization">Search Engine Optimization</a>
            <a href="#online-reputation-management">Online Reputation Management</a>
            <a href="#social-media-marketing">Social Media Marketing</a>
        </nav>
    </header>
```

## How it should look:

![c8adef9543ceacc92eab4a4dbccf731e](https://user-images.githubusercontent.com/92896466/150401786-5b055180-ea55-452a-936c-b799b59d938f.png)

---

## Deployed Link

 https://debofafore.github.io/Module-1-Challenge/

---

## Author

 Adebowale Fafore

- [Link to Github](https://github.com/DeboFafore/Module-1-Challenge)
- [Link to LinkedIn](www.linkedin.com/in/adebowale-fafore-3a384732)

