# Anastasia Smolina
## Contacts:
tel.: +79055010306 \
email: smolina.anastasia.14@gmail.com \
telegram: @Anastasia_Sml \
discord: @Anastasia#8750

## About me
soft-skills
## Hard-skills
1. JavaScript
2. GIT
3. HTML, CSS, SCSS
4. Bootstrap
5. Developing adaptive and responsive web pages using html and css
6. BEM metodology

## Code examples
```
function calcPrice() {
    let prices = document.querySelectorAll(".input");
    let sum = 0;
    for (let price of prices) {
        let currentPrice;
        if (price.type == "checkbox") {
            if (price.checked) {
                currentPrice = Number(price.value);
            } else {
                currentPrice = 0;
              }
            }
        else {
            currentPrice = Number(price.value);
        }
        sum = sum + currentPrice;
        }
    document.getElementById("price").innerHTML = `Стоимость данной модели: ${sum}`;
    }
