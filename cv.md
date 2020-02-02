# Andrey Niahrou

## Contact Info:

* __mobile:__ +375445948450
* __skype:__ strateg.dev03

## Summary

﻿Award-winning web developer and instructor with 10+ years
of well-rounded experience in LAMP development, object-oriented 
and user-centered design, seeks a position with a top technology firm.

## Skills

* __backend:__
    * php
    * sql 
    * symfony
* __frontend:__
    * js
    * html
    * css
    
## Code examples

```javascript
        xhr.onreadystatechange = function () {

            if (xhr.readyState !== 4) return;

            if (xhr.status === 200) {
                document.body.innerHTML = xhr.responseText;

                const script = document.createElement('script');
                script.src = "/trainings/' + name + '/script.js";
                document.head.append(script);

                script.remove();

                const link = document.createElement('link');
                link.rel = 'stylesheet';
                link.href = '/trainings/' + name + '/style.css';
                document.head.append(link);
            }
        };
```