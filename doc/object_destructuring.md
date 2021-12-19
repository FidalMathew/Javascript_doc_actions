# Object Destructuring

## Object Example 
```Javascript
const person = {
    name: 'Jiren',
    age: 30,
    anime: 'Dragon Ball Super'
}
````

We have to write person.name to access name, person.age to access age and person.anime to access anime name

## Destructuring Person Object

```Javascript
const { name, age, anime } = person;
```

Now we can access properties by just writing name, age and anime
