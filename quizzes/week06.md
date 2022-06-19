# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
  The entry point is the first part of an application that is exposed to the user. It is how the user will be able to access different portions of the app.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
  A component is a portion of code that can be injected anywhere the programmer wants to. They are reuseable and can be injected inside of other components. Even though Single Page Applications only have 1 html page/document, many different things can be injected into it. Pages are unique and cover all of the html document, save the header, footer, and any other navbar type things on the page. Pages are composed of some hard coded info but also contain components to be able to display different data and remain reactive.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
  You can use Vue's v-for method that loops over and array of data and injects it into a component that will in pre-specified ways to create repetitions of something while have it automatically filled with data for you. 
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
  The 3 tags that make up a Vue file are the style, script, and template. 
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
  The L in SOLID stands for the Liskov Substitution Principle. Which states roughly that parent functions/objects/things must be able to use things created by its children without having its meaning/functions changed.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
  It used the loadPage component to mount pages.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
  The AppState is a global component while the state object within a component is local to that component.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
To preform CRUD method requests and to help separate out the functionality of components and pages so that the application is more secure from external tampering and internal errors.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```

```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```

```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```

```