# Hewwwo ^^

## I have noe idea what I am doing but im doing it.

> Daniel is extraordinary weird.

This project
: just testing markdown and git.

```javascript
let groceries = arr => {
  let string = "";
  for(let i = 0; i < arr.length; i++)
  {
    if(i === arr.length - 2) {
      string = string + arr[i].item + " and " + arr[i+1].item;
      break;
    }
    string = string + arr[i].item + ', ';
  }
  if(arr.length === 1)
  {
    string = arr[0].item;
  }

  return string;
}
groceries( [{item: 'Carrots'}, {item: 'Hummus'}, {item: 'Pesto'}, {item: 'Rigatoni'}] );
// returns 'Carrots, Hummus, Pesto and Rigatoni'
 
groceries( [{item: 'Bread'}, {item: 'Butter'}] );
// returns 'Bread and Butter'
 
groceries( [{item: 'Cheese Balls'}] );
// returns 'Cheese Balls'
```