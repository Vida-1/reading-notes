#### 04/11/2022: Read 06 - JS Object Literals; The DOM

#### JS Chapter 3: “Object Literals” (pp.100-105)
<code>
 var furkid = {
    name: 'Tippy',
    breed: 'Chiweenie Rat Terrier',
    dob: 4/24/2013,  //this may not be formatted correctly
    age: function () {
      return new Date().getFullYear() - this.dob;  //not sure yet if this will actually work
    }
}
</code>
    So if I've understood the text correctly, everything between the outer curly braces is the "object"
    name, breed, dob, and age are "properties"
    'Tippy', 'Chiweenie Rat Terrier', and 4/24/2013 are all "values"
    The age property is assigned a value concluded by the function which (because it is feeding a property) is referred to as a "method"

    Note that each value is separated from the next with a comma, the final value is closed with a semi-colon then curly brace

#### JS Chapter 5: “Document Object Model” (pp.183-242) 
* Document Object Model (DOM) aka Application Programming Interface (API)
* "When the browser loads a web page, it creates a model of the page in memory. The DOM specifies the way in which the browser should structure this model using a DOM tree." -pg 184
* "The DOM states what your script can ask the browser about the current page, and how to tell the browser to update what is being shown to the user." -pg 184
* DOM tree from pg 187 of the text:
[!Image](/img/Domtree.jpg)

#### [Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)
The author describes the dream situation of having a clear and detailed spec sheet at one point in his history as a programmer, unfortunately though understanding the problem completely from the beginning is important to being able to more efficiently generate code, it does not seem to be the case anymore. &#128532;

#### [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
No takeaways from this one.

#### `Why this topic matters`
* Web pages are generally constructed to convey information in an organized fashion. Object literals appear to be a very orderly way of collecting such information for presentation.
    
#### `Analogy `
* I don't think my understanding is complete enough to provide a terribly relevant analogy at this point.
        
#### `Things I want to know more about`
* I think for now I'd just like to play around with this basic structure for a few days (thank goodness it's the weekend!) to satisfy different scenarios and get comfortable with it before seeking additional details or expanding into additional concepts.