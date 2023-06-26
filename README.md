# CS230
# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client was The Gaming Room, a company seeking to develop a cross-platform web-app. Their game, Draw It or Lose It, is limited to Android through an app. The OS's supported should include Windows, macOS, Linux, Android, and iOS. The app should function responsively on various browsers including, but not limited to: Safari, Chrome, Edge, and Firefox. The application needs to scale; supportiing multiple teams and players, unique names, and a single instance of the game. It will render images high definition stock images, with timed rounds, allowing each team to solve the puzzle.

# What did you do particularly well in developing this documentation?

I provided a readable and detailed document, with consideration given to specific development options. I am proud of the research and examples I provided for each Operating system, and the associated advantages/disadvantages. By the end of the document, I was consise with my recommendations, while still providing relavent solutions and supporting resources.


# What about the process of working through a design document did you find helpful when developing the code?

Writing the design constraints helped me conceptualize what the singleton pattern was exactly meant to do, in regards to the single game instance. It was also helpful, in additon to the Domain Model, to put into context what private and static methods mean. I was able to understand better the purpose of creating a superclass, and how that shared methods with it's subclasses.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would like to add some hyperlinks to the Evalaution Table for my sources. I'd also like to go over again tools like Docker, Kubernetes, a Droplet, a CDN etc. It was a good exercise to research all of these supporting tools that work together to deploy an application— I think I may have been able to add more relevant and detailed information.

# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I considered the users need for a cross-browser/device capable web-application. It was important to consider this, as one of the main systems that web servers run on is Linux. It was also important to consider, due to needing to consider responsive web-design principles, for mobile devices. This was one of the reason's I even researched image delivery and optimization. Without those needs being taken into account, I may have ignored the fact that many static images needed to be delivered— and not have researched a content delivery network. 

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I would first consider the tools that I have the most experience in, and work outward from there. In hindsight, I should have considered Windows OS more, due to the fact that the client had a previous Android App. However, as primarily a mac user, my knowledge of Windows hardware and associated technologies is shallow. I would also try to look for similar examples of what software I am trying to design. As an example, if I am designing a social media app, I may look at similar apps, and investigate what technologies were used in their creation. 
