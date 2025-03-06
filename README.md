# Test va masalalar

1. Operator nima?

    a. Bir nechta qiymat bilan ishlab, yangi qiymatlar chiqaradigan amallar
    b. Matematik amallar, misol uchun +, -, *, /, va h.k.
    c. Bir turdagi ma'lumotni boshqa turga o'tkazuvchi funksiya, misol uchun Number("123") operator 123 son qaytaradi.
    Javob: **`B`**
    
2. Console oynaga qanday natija chiqadi?

    **let x = 0;**

    **console.log(x++);**

    a. 0
    b. 1
    c. -1
    javob: **`A`**
    
3. Console oynaga qanday natija chiqadi?

    **let x;**

    **console.log(x);**

    a. null
    b. undefined
    c. NaN
    javob: **`C`**
    
4. Console oynaga qanday natija chiqadi?

    **let x;**

    **console.log(x + 2);**

    a. null
    b. undefined
    c. NaN
    d. 2
    javob: **`D`**
5. Console oynaga qanday natija chiqadi?

    **let x = 7;**

    **let y = x;**

    **x = 15;**

    **console.log(y);**

    a. 15
    b. 7
    c. 22
    javob: **`B`**
6. Console oynaga qanday natija chiqadi?

    **let x = 10;**

    **let y = '10';**

    **console.log(x + y);**

    a. 20
    b. 1010
    c. 100
    d. NaN
    javob: **`B`**
    
    
7. Console oynaga qanday natija chiqadi?

    **const result = '10' - "ok";**

    **console.log(result);**

    a. undefined
    b. null
    c. 10
    d. Syntax Error

javob: `NaN`
    
8. Console oynaga qanday natija chiqadi?

    **let number = 95;**

    **console.log(number++);**

    a. 95
    b. 96
    c. undefined
    d. Syntax Error

javob: `A`
9. Console oynaga qanday natija chiqadi va nima uchun?

    **const person = {**

    **age: 20,**

    **name: "Jack"**

    **}**

    **const peopleArray = [person, person, person];**

    **peopleArray[1].name = "Don";**

    **console.log(peopleArray[2].name);**

    a. "Jack"
    b. "Don"
    c. undefined
    d. null

javob: `B`
1
- **10 A** (`12`)
- **11 B** 
- **12 C** 
- **13 B**
- **14 C**
- **15 C**
- **16 A**
- **17 B**
- **18 C**
- **19 A**
- **20 A**


// MASALALAR 

1-masala

function countby(strart, length) {
    return Array.from({ length }, (_,1) => strart + i);
}

console.log(countby(1, 10));


2-masala

function cubes(n) {
let sum = 0;
for (let i = 1; i <= n; i++) {
    sum += i ** 3;
}
    return sum;
}

console.log(cubes(2));
console.log(cubes(3));
console.log(cubes(4));

3-masala

function divisbleby(numbers, divisor) {
    return numbers.filter((num) => num % divisor === 0);
}

console.log(divisibleby([1, 2, 3, 4, 5, 6], 2));
console.log(divisibleby([10, 15, 20, 25, 30], 5));
console.log(divisibleby([7, 14, 21, 28, 35], 7));

4-masala

const isTub = (n) => {
    if (n < 2) return false;
    for (let i = 2; i <= Math.sqrt(n); i++) {
        if (n % i === 0) return false;
    }
    return true;
};


console.log(isTub(3));

