# ChennaiReact

## [Arun Kumar](https://www.linkedin.com/in/arunkumarvallal/)

## ​**Talk #1:** Augmented Reality with React Native using Viro SDK

What is Augmented Reality?
Augmented reality (AR) seamlessly blends virtual elements with the real world, enhancing the physical environment with digital overlays like images or objects.

Examples of A.R Given : [IKEA  using the A.R](https://www.wareable.com/ar/ikea-place-ar-arms-race-modiface-arkit-827)

### Fundamental Concepts

- Motion tracking : To track the motion
- Environmental understanding : to keep a check on environments
- Depth understanding : The objects mustn't cross each other i.e each object has certain depth function associated to it which must be taken into consideration.
- Light estimation : Accurate Light measure is important for correct colors ,exposure and shape.
- Occulsion : As told by the author of the talk **Occlusion** is the implementation of the depth concept.
- Anchors

### Viro React for AR

Why use Viro React?

- Easy integration
- FOSS (Free and Open-Source Software)
- Supports ARCore for Android and ARKit for iOS
- Auto linking simplifies setup
- Scene Navigator for seamless scene navigation
- Plane Navigator ensures accurate scene placement.
- [Link to Viro Documentation](https://viro-community.readme.io/)

## [Shanthi P](https://www.linkedin.com/in/shanthi-palani-0500a9100/)

## **Talk #2**: Exploring the World of Microfrontend Architecture with React

What is Microfrontend Architechture?
Microfrontend architechture allows the architecture to be broken down into separate modules that have low coupling between them and can function as separate unit.

### Major points noted from the talk

- **Microfrontend in frontend** is similar to **Microservices in backend**
- Another strategy against monolith architecture: As we know in monolith we place all the code together at one place,so to avoid that we can use this architecture for better scalability.
- No team dependency between modules(low coupling): Different teams can work on separate modules without any affect.
- Deployablity : The separate modules can be separately deployed at different places.
- Customisation: We can use different tech stacks like react,vue or any other frontend in the modules.

### Challenges

- Data passing
- Testing
- Styling
- Deploying

### Integration Strategies

- SPA : Making the website look like it is being run from single page by use of compentisation concept (Example: React)
- Module Federation: Module Federation allows us to implement Microfrontend architecture.
- Web Components : Web Components are the new addition to web that allows us to create components using native web.
- Server Side : There are many new frameworks today that allow us to create Server side rendered components (Example: NextJS)
- Iframes: Iframes although mentioned is not recommended approach to integrate the modules as it only allows links of modules to be added not allowing any customisation over the modules.
- Package approach: To bundle the code into one module we can use several package managers.

After this **Shanthi P**,showed us how module federation can be utilised to implement micro-frontend architecture.
[`Create-mf-app`](https://www.npmjs.com/package/create-mf-app)  : To create module federations between several web-apps

### Data passing techniques

- Event Driven communication
- State management
- Context API
- Web Storage
- Query String (!Not recommended much)

## Quizzizz react

A Fun Quiz based on React and frontend concepts was held.

## [Dani Akash](https://www.linkedin.com/in/daniakash/)

## ​Talk #3: Building web components with React

### Web components

With the rise of frontend technologies embracing componentization principles, users have had the option to utilize native components. However, when native web APIs are necessary for component creation, web components enter the spotlight.

- Shadow dom : Web Component uses something called as a shadow dom to encapsulate the DOM and CSS under a scoped subtree.

### Combination of react and web components

After general explaination of basic concepts related to web components, Dani showed us a demo of how we can incorporate any **frontend framework code into web components** by using web components as a layer above that code.

- Frameworks that are already using web components : Lit.dev , Stencil.js ,Polymer

## Networking Session

During the networking session, I had the pleasure of engaging with professionals from diverse fields. One standout encounter was with [Shaul Hameed](https://www.linkedin.com/in/shaulhameed/), who provided a comprehensive explanation on the distinction between Shadow DOM and Virtual DOM.

### Other People I met in the talk

- [Karthik R: A Frontend Dev from Cisco](https://www.linkedin.com/in/karthik-r-a70001194/)
- [Abhijith Konnayil: A Fullstack Dev](https://www.linkedin.com/in/abhijithkonnayil/)
- [Abinandan G: A Frontend Dev](https://www.linkedin.com/in/abinandan-g-b39971113/)
- [Praveen : MERN stack Dev](https://www.linkedin.com/in/praveen-pandi/)
- [Mohan Raj](https://www.linkedin.com/in/mohan-raj-3a180a1b0/)
