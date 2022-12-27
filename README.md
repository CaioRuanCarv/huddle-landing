
![](src/images/screenshot.jpeg)

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

```html
<div class="about">
                <h3>Build The Community Your Fans Will Love</h3>
                <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience.
                    Create connections with your users as you engage in genuine discussion. </p>
                <div>
                    <a href="/">Register</a>
                </div>
            </div>
```
```css
.about{
    color: white;
    align-content: center;
    display: flex;
    flex-direction: column;
    padding: 50px;
}
.about h3{
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
    font-size: 35px;
    margin-bottom: 15px;
}

.about p{
    font-family: 'Poppins', sans-serif;
    margin-bottom: 20px;
}

.about a{
    color:hsl(228, 45%, 44%) ;
    background-color: white;
    font-size: 18px;
    padding: 10px 50px;
    border-radius: 50px;
    box-shadow: 3px 2px 3px black;
    transition: 0.2s ease-in-out;
}

.about a:hover{
    color: white;
    background-color: var(--color-btn);
}
```
- Frontend Mentor - [@CaioRuanCarv](https://www.frontendmentor.io/profile/CaioRuanCarv)

