
Tapescript:

Men's well-known desire to simplify working process and avoid reinventing the wheel has been bringing its results
enriching mankind with new technologies. IT sphere just cannot be an exeption here and as a result js coders 
can use lots of frameworks that serve as fine-tuning tools. One of these frameworks is REACT.
React, also known as  React.js or ReactJS (all the three options of the name are possible and usable) is only 6 years old. 
Its official birthday is considered to be the 29th of May 2013,
Facebook software engineer Jordan Walke  initially tried using it on facebook newsfeed in 2011, then on instagram,
and only after those tests he revealved the framework to the whole world.

One of the most important React advantages is the speed it provides due to its special feature virtual DOM by name.
DOM was never meant to work with UI creation which is its main problem. 
We could try to work with DOM using javascript itself or jQuery but that would take some time which can be uneccaptable.
For instance scrolling down social media newsfeed activates thousands of DOM-elements which can take more than a second
 - so terribly long for modern web.
 Solution to this issue came with Virtual DOM. This is a light copy of DOM, its clone which we can modernify the way we need.
 Virtual DOM compares its components with DOM and then implements all the changes if there are any.
All the implemention go much quicker since the heaviest parts of DOM don't participate.

Another special feature of React is its components. Before we get deeper into this, let's recall
why exactly  React appeared?  What was the reason and how come it has so many links with HTML, CSS and javascript?
The thing is, the classical website structure usually includes:
- HTML as its frame;
- CSS as its decoration and functionality;
- and finally javascript to make things wirk properly.
Keeping all the 3 spheres apart was supposed to be logical and save, 
but with time it became clear and obvious that component approach is more effective.

Components are the building blocks of React, a typical React app would have lots of them.
If you take a look at a popular website you'll notice a lot of components it consists of (assuming it was built on React):
- search box
- menu
- profile picture
- list of repositories
- edit area
- and some other options.
A component is a javascript function or a class which can accept inputs 
and returns a React element that describes the way UI section should appear.
Components in React can be refreshed and reused.
There are several ways of creating React components:
- via fucntions;
- via ES6 classes;
- via arrow functions.
Components usage simplifies and structures coding process, it shortens code and also makes it more readable and beautiful.
Each component has all the 3 main tools of a typical website.

React has brought another special tool to web developers which is JSX.
JSX is a syntax which has a lot of similarities with HTML and is used in React to enrich Javascript.
JSX made it possible to use HTML in js. 
Even thought it's possible to work in React without JSX, usage of it is strongly recommended
since that's an ideal tool to work with components. 
At first sight JSX could be taken as a weird mix of HTML and javascript (and even CSS) but it wouldn't be an acurate description.
That's still javascript.
You can still use it in JSX whenever you need, don't forget to put the code inside curly brakets.
 For example we have a function that retuns a greeting and all we need to add is a person's name.
 We already have a variable called "name" hense we can use it inside the function , adding it in curly brackets.
 We can use variables, arithmetic operations and even functions in these cirly brackets.
JXS has some picularities:
1.All the tags should have the closing one or a self-closing slash at the end. No auto closings.
2. You cannot use dash-case while naming attributes, only CamelCase!
3.Attributes can be described either with the help of typical inline CSS or using curly brackets with js code.
4. Since "class" is way too popular,you need to use "className" instead. WIth a CamelCase of course.
5. Attributes "value" and "checked" turn into "defaultValue" and "defaultChecked" 

Clean Abstraction is another important feature of React. Providing a good abstraction means that a user
wouldn't be bothered with complex internals. In other words it helps us concentrate on the process we should work at, 
putting aside all the unneccessary details. 
React doesn't force you to use particular patterns, you are free  to design your layers the way you want.

To understand the way React works I suggest obsurving its component lifecycle from the very beginning.
THis lifecycle helps us to interact with other libraries in a more effective way.
There are 3 main stages of this cycle:
1.Initialization.
2. Update
3.Destruction
Each of the stages has its own events and methods.
Let's start with moutung events. This group contains events that occur while mounting an element into DOM.
The methods of this group are:
1 componentWillMount() {}
2 componentDidMount() {}
The first one calls out an even before an element is created, the second one calls out an even after an element is created.

The second group of events is updating. They occur if an element is updated. Tis group consists of 4 methods:
1.componentWillRecieveProps() {} which occurs when a component is ready to receive properties from its parent
2. shouldComponent Update() {}  which checkes whether components should be updates and help optimization.
3. componentWillUpdate() {} which occurs right before the element update.
4. componentDidUpdate() {} which implements right after the element update.

the third group of events consists of just one method which is componentWIllUnmount() {} 
It lets us manipulate any events before the component is deleted.


Code reusage not only helps to create websites but also  transform it into a web application in no time.
The reason is the code you wrote during making that website could be reused for making an application.


Nowadays React is one of the most spread and popular frameworks used all over the world. 
Its aim was to simplify coding process and it managed to do so. 
According to the Dutch programmer and soft engineer Edsger W. Dijkstra,  Э́дсгер Ви́бе Де́йкстра
"Simplicity is prerequisite for reliability". Couldnt agree more.
