# Learning_MAT
JS_MATH_BUSINESSLOGIC

# Week 1 — React Fundamentals

# Day 1 — JavaScript Essentials for React

    Focus on modern JavaScript.

        Learn

        ## let, const
        ## Arrow functions (let funname = (params1, params2) =>{ //code; return value;};)
        ## Template literals ( backticks ` `)
        Destructuring
        Spread/rest operators
        Array methods:
        map()
        filter()
        find()
        Promises
        Async/Await
        ES Modules
        Practice
        const users = ["A", "B", "C"];

        users.map(user => console.log(user));

# Day 2 — React Basics

    Learn
    ## What is React
    ==> React is an open-source JavaScript library for building user interfaces or UI components, developed by Facebook.

    ## SPA concept
    ==> A Single Page Application (SPA) is a web application where the entire website loads only once, and further page changes happen without reloading the browser. (Browser → React updates only changed components)

    ## Components
    ==> A Component is a reusable piece of UI in React. (Component Naming Rules: Start with capital letter)

    ## JSX
    ==> JSX (JavaScript XML) is a syntax extension for JavaScript that allows developers to write HTML-like code inside JavaScript in React applications.

    ## Functional components
    ==> Functional Components are simple JavaScript functions that return JSX, most commonly used way to create components in React

    ## Props
    ===> Props are used to pass data from a parent component to a child component. (Properties)

    Practice

    Create:

    Navbar
    Card
    Button components

Example:

function Welcome(props) {
  return <h1>Hello {props.name}</h1>;
}


# Day 3 — State & Events
    Learn
    useState
    Event handling
    Controlled inputs
    Practice

    Build:

    Counter App
    Todo Input
    Toggle Button

Example:

const [count, setCount] = useState(0);


# Day 4 — Lists & Conditional Rendering
    Learn
    map()
    Keys
    Conditional rendering
    Ternary operator
    Practice

    Build:

    Todo List
    Product List

Example:

{isLoggedIn ? <Home /> : <Login />}


# Day 5 — Hooks Deep Dive
    Learn
    useEffect
    API calling
    Cleanup
    Dependency array

    Practice

    Fetch users from API:

useEffect(() => {
 fetch("https://jsonplaceholder.typicode.com/users")
}, []);


# Day 6 — Forms & Validation
    Learn
    Form handling
    Validation
    Multiple inputs
    Practice

    Build:

    Login Form
    Registration Form

    Optional:

    Learn Formik


# Day 7 — Mini Project
    Build

    Choose one:

    Weather App
    Todo App
    Notes App
    Include
    Components
    State
    API
    Forms
    Conditional rendering

# Week 2 — Advanced React + Interview Prep

# Day 8 — Routing

    Learn React Router

    Topics
    BrowserRouter
    Routes
    Route
    Link
    useNavigate
    useParams

    Practice

    Create:

    Home page
    About page
    Product details page

# Day 9 — State Management
    Learn
    Prop drilling
    Context API
    Practice

    Build:

    Theme switcher
    Auth context

    Optional:

    Basic Redux Toolkit


# Day 10 — Performance Optimization

    Learn
    useMemo
    useCallback
    React.memo
    Understand
    Re-rendering
    Optimization

# Day 11 — Custom Hooks

    Learn

    Create reusable hooks.

Example:

function useFetch(url) {

}
Practice
useToggle
useFetch


# Day 12 — React Interview Topics
    Important Questions
    Virtual DOM
    Difference between state & props
    Lifecycle methods
    Hooks rules
    Controlled vs uncontrolled components
    useEffect lifecycle
    Key prop
    Coding Practice
    Todo CRUD
    Search filter
    Pagination


# Day 13 — Project Day

    Build one strong project.

    Recommended
    E-commerce frontend
    Admin dashboard
    Movie search app
    Use
    Routing
    API
    Hooks
    Context
    Responsive UI

# Day 14 — Revision + Mock Interview
    Revise
    Hooks
    Routing
    State management
    API calls
    Practice
    Build small components without watching tutorials
    Explain concepts aloud
    Best Resources
    Documentation
    React Official Docs
    YouTube
    Codevolution
    Hitesh Choudhary
    Net Ninja
    Practice
    LeetCode
    Frontend Mentor


# Recommended Daily Schedule

Time	Task
1 hour	Learn concepts
2 hours	Build
1 hour	Practice interview questions
30 mins	Revision


# Final Goal After 2 Weeks

You should be able to:

Build React apps
Use hooks confidently
Call APIs
Handle routing
Create reusable components
Answer React interview questions
Build portfolio projects
