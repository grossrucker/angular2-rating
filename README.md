# angular2-rating

This project adds a simple 5-Star-Rating typescript component to your Angular2 Application.


``` bash
import {StarRating} from grossrucker/angular2-rating

directive [StarRating]

let rating:number = 5;
let disabled:boolean = true; // true|false
let size:number = 15; //fontsizte of stars in pt

<star-rating [(rate)]="rating" [disabled]="false" [size]="size"></star-rating>
```

