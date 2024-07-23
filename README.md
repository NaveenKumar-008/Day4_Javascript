# ES6 Javascript Assignment

## One

```
let age=30;
const name="Alice";
 name="bob";
 console.log(name)

```

## Output

![Screenshot (64)](https://github.com/user-attachments/assets/e2e05faf-fdf4-4f5c-a4e4-0628b65654ef)

## Two

```
const add=(a,b)=>{
    console.log(a+b) ;
}
add(9,11);


```

## Output

![Screenshot (63)](https://github.com/user-attachments/assets/aafc46ff-8541-4d6c-980f-d4f0af67cc44)

## Three

```
let name="Alice";
let age=30;
let txt=`Hello,${name} Your age is ${age}.`;
console.log(txt);

```

## Output

![Screenshot (65)](https://github.com/user-attachments/assets/5db94852-075a-4e8b-b744-faf9c0aed4ee)

## Four

```
const person={
    firstName: "Alice",
    lastName: "Johnson"
}
const{firstName,lastName}=person;
console.log(firstName);
console.log(lastName)

```

## Output

![Screenshot (66)](https://github.com/user-attachments/assets/02b319ef-f051-465a-b37f-920aec8f2ae2)

## Five

```
const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

console.log(first);
console.log(second);

```

## Output

![Screenshot (67)](https://github.com/user-attachments/assets/734329c4-0567-4083-8efb-e8188ace53cc)

## Six

```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

console.log(combined);

```

## Output

![Screenshot (68)](https://github.com/user-attachments/assets/4b5e4633-3868-4e66-b6f5-872ed3108412)

## Seven

```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

console.log(sum(1, 2, 3, 4, 5));
console.log(sum(50, 40));
console.log(sum());

```

## Output

![Screenshot (69)](https://github.com/user-attachments/assets/61abb40b-0b12-46e2-b664-a40876fea417)

## Eight

```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;

console.log(greet("Alice"));
console.log(greet("Bob", "Hi"));
console.log(greet("Charlie", "Hey"));

```

## Output

![Screenshot (70)](https://github.com/user-attachments/assets/6dc0a3f1-f924-487a-aded-363ea82eeee9)

## Nine

```

class Animal {
    constructor(name) {
      this.name = name;
    }
  }

  class Dog extends Animal {
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }

  const myDog = new Dog('Julie');
  console.log(myDog.bark());


```

## Output

![Screenshot (71)](https://github.com/user-attachments/assets/d518e8b3-3356-4937-969a-bbef8082ff26)

## Ten

```
const waitAndReturn = () =>
    new Promise(resolve => setTimeout(() => resolve("Done"), 2000));

  async function run() {
    const result = await waitAndReturn();
    console.log(result);
  }

  run();

```

## Output

![Screenshot (72)](https://github.com/user-attachments/assets/746499b5-8b0b-4510-b7e8-02a840e947f9)
