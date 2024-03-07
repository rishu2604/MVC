# What's MVC
It's all about separation of concerns, so making sure that different parts of your code do different things and you clearly know which part is responsible for what.
<br/>

## Model
- Models are basically objects or is a part of your code that is responsible for representing your data and allow you to work with your data
- So things like saving data, fetching data to or from a file or even if it's just in memory, this should be handled by models.

<br/>

## Views
- The views are responsible for what the user sees in the end, they are responsible for rendering the right content in our html documents and sending that back to the users.
- So they are decoupled from your application code and are just having some light or minor integrations regarding the data we inject into our templating engine to generate these views.

<br/>

## Controller
- It is a connection point between the model and the views, contains the "in-between" logic.
- Because since the views shouldn't care about the application logic and the models do care about how to save and fetch data.
- The controllers are the thing working with the models, saving the data and triggering that save process and also the part where they then pass the data that was fetched to the views.
- Routes are also fit into these.
- Routes are basically the things which define upon which path for which http methodwhich controller code should execute.
