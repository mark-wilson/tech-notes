# Other Stuff
This is the place for all the unfiled notes... the ones that didn't fit under the other transformation categories and sit here until I find they are big enough to need their own place in the structure.

## On new technologies
(In the context of AI, but also more broadly)

"There are two principal and immediate risks with any new technology: the first is to fetishise it and the second is to demonise it - and i think both are problematic. The issue for me is - and will always be -  where is it being used, by whom to what effect, and with what level of accountability?" \[[Professor Fraser Sampson, UK Commissioner for the Retention and Use of Biometric Material and Surveillance Camera Commissioner][1], [BBC Tech Life 19/9/23][2]\]

## On selling products and services

Look at business issues - what are we going to do over the next 12, 15, 18m?

Selling is a process:
1. Build relationships
2. Understand client needs
3. Fill the gap

Success is not just about achieving a number but more about how we can see:
- Pipeline growth
- Product attachment
- Average deal size increase
- Utilisation up and at right run rate
- Feedback from teams - feeling empowered, having fun, feeling successful
- Developing skill sets and working on a wider knowledge set to take to clients

## Architecture points

### High and Low-Level Designs (borrowed from Ben Curtis)
You'll often hear talk about high-level designs (HLDs) and low-level designs (LLDs) - but how are they different? Well, it comes down to Big Plans vs. Detailed Layouts

Imagine designing and building a house. Like architects plan every aspect of a building, IT architects do the same for IT systems. They balance two kinds of designs: big-picture plans (HLD) and detailed layouts (LLD).

High-level design is like drawing the big picture of a house. It sets the main structure and ideas for the IT system, similar to a sketch of a house's layout. Here, IT architects decide on things like how systems connect, what technologies to use, and how it all fits business goals like low-cost or availability.

Low-level design zooms in on specifics, just like making detailed plans for each part of a house. It covers things like what materials to use, how wires connect, and what software settings are needed. IT architects dive into LLD to make sure every technical detail is clear and efficient.

Balancing high-level and low-level design means blending the big ideas with the small details, much like mixing a house's style with its sturdy construction. While HLD gives the main plan and direction, LLD fills in the technical bits to make sure the IT system works well - now and in the future.

And just like a house gets checked and adjusted during building, IT design needs to be flexible. IT architects may need to go back and tweak both HLD and LLD as technology changes and business needs shift. With this flexible approach, they can create IT systems that are solid and stand the test of time, just like a well-built house.

_I like Ben's "big plans vs. detailed layouts" analogy. I always describe it as the HLD is the what we will do and the LLD is the how. I'd also add that all designs should be requirements-led - I've lost count of the number of times I've seen projects fail because someone got distracted by the shiny things and forgot the why we're doing this._

_One of the last things I managed to do when I was working for a large SI was to get the HLD and LLD templates merged. Sounds like madness, right? Bear with me._

_What I'd found was that the early sections of the HLD and LLD repeated each other - the same background, requirements, etc. That led to lots of context-switching to go back and edit the HLD as the LLD was developed._

_By combining the documents into one design and having a part 1 and part 2 (each with their own sign-offs), we could keep everything in one document and only had to update the common content once._

_What I really wanted to do (and wanted to do at my next company too but never found a way) was to get away from individual documents and to hold everything in one web-based system, which could auto-generate the documentation when required. I can dream..._

### Perception and Perspective (borrowed from Ben Curtis)
It can be helpful to highlight the importance of perception and perspective, and their differences in the context of IT and Enterprise Architecture.

- Perception: What Meets the Eye. Imagine you're walking through a forest and come across a single tree. Your first impression of that tree—its size, shape, colour, and surroundings—is your perception. You can liken this to an impression of a single application in a client's environment.
- Perspective: Seeing the Forest and the Trees. Now, let's say you climb to the top of a hill and look down at the entire forest. Suddenly, you see how all the trees are connected, how the sunlight filters through the leaves, and how animals move through the undergrowth. This bigger view—the perspective—gives you a deeper understanding of the forest as a whole. You can liken this to a complete view of a client's environment and how users, devices, applications and networks interact.

You can now see why it's important that we have a similar perspective on how technology fits into the bigger picture of a business.

Example:
- Let's say a client wants to implement a new application to streamline their operations. From a technical perspective, the IT team might focus on the system's functionality and security. However, from a business perspective, stakeholders might be more concerned about the system's impact on productivity, cost savings, and customer satisfaction. By integrating these perspectives, Enterprise Architects can design a solution that meets both technical requirements and business needs.

It's not just about having the right perspective; it's about communicating it effectively. Without clear communication of technical requirements and business needs to all stakeholders, the holistic view may remain obscured. In essence, if we don't share the broader forest view, stakeholders might continue to focus solely on individual trees.

It's crucial to appreciate the forest as much as the trees. By integrating technical and business perspectives and communicating effectively, we can ensure that our solutions align seamlessly with overarching business goals.

### MoSCoW (borrowed from Ben Curtis)
We're not talking about Russia's capital city but rather we wanted to discuss one of the frameworks we use to make informed decisions in the world of IT and Enterprise Architecture: the MoSCoW method.

Making decisions in IT is all about understanding the needs, prioritising effectively, and selecting the options that align with the business goals. It's a requirement to have some requirements!

The MoSCoW Method, originating from the acronym for "Must-have, Should-have, Could-have, and Won't-have," is a powerful technique for requirements prioritisation. It helps us sift through the multitude of options and focus on what truly matters. Let's break down each category:

- Must-have: These are essential elements critical for achieving goals. They form the backbone of the architecture and cannot be compromised.
- Should-have: Important, but not crucial. They enhance functionality and effectiveness but can be deferred if necessary.
- Could-have: Desirable features that are not essential. They offer opportunities for enhancement but can be sacrificed if resources are constrained.
- Won't-have: Options deliberately excluded from consideration. They may not align with current objectives or may be unnecessary at the moment.

Imagine you're planning a kitchen renovation. Your categories would look like this:

- Must-have: Functional appliances and adequate storage space are essential for usability.
- Should-have: Aesthetically pleasing design elements to enhance the overall look and feel.
- Could-have: Smart home features for added convenience, if budget allows.
- Won't-have: Luxury additions like a built-in wine fridge, which may exceed budget constraints, but could be added in the future.

Now imagine you're tasked with selecting a cloud service provider and change your categories accordingly:

- Must-have: High availability and reliability are essential for uninterrupted access to applications.
- Should-have: Scalability to accommodate future growth without disruptions.
- Could-have: Easy integration with existing tools for improved operational efficiency.
- Won't-have: Advanced AI capabilities, which might not align with current strategic goals, and may be added in the future.

The MoSCoW Method offers a systematic framework for prioritising options based on business objectives and requirements. It allows us as Architects to cut through the noise and consider what matters. (There are other frameworks and methods available, such as using a SWOT Analysis or a Weighted Decision Matrix.)

### Functional and Non-Functional Requirements (borrowed from Ben Curtis)
Have you ever wondered how products like cars, kitchen appliances, or even your favorite gadgets are designed to meet your needs? Well, it all starts with two important types of requirements: functional and non-functional. Let's explore them using examples that everyone can relate to.

Functional requirements are like the basic functions or tasks a product needs to perform. They're the blueprint that outlines what the product should do.

Let's consider a car. Some functional requirements for a car may include:

- Acceleration: The car should be able to speed up smoothly when you press the accelerator pedal.
- Braking: It should come to a complete stop when you apply the brakes, ensuring safety.
Steering: The car should respond accurately to steering wheel movements, allowing you to navigate turns easily.
- Climate Control: It should have air conditioning and heating systems to maintain a comfortable interior temperature.
- Entertainment System: The car should have a radio or media player for music and audio entertainment during the drive.

These functional requirements ensure that the car performs the essential tasks needed for driving comfortably and safely.

Now let's consider a technical example like a web-based email application. Some functional requirements might include:

- User Authentication: Users should be able to log in securely using their username, password and MFA.
- Send Email: Users should be able to compose and send emails to other recipients.
- Receive Email: The application should receive and display incoming emails in the user's inbox.
- Attachment Support: Users should be able to attach files (e.g., documents, images) to their emails.
- Search Functionality: Users should be able to search for specific emails using keywords or filters.

These functional requirements outline the essential tasks the email application must perform to be considered functional.

Non-functional requirements focus more on the quality aspects of the product rather than its specific functions. They define how well the product performs those functions and the overall user experience it delivers.

Driving forward with our car example (😉), some non-functional requirements may include:

1. Fuel Efficiency: The car should use fuel efficiently to minimise trips to the petrol station and reduce expenses.
2. Safety Features: It should have airbags, anti-lock braking systems (ABS), and traction control for enhanced safety.
3. Comfort: The seats should be ergonomic and supportive, providing a comfortable ride even on long journeys.
4. Durability: The car's components should be durable and long-lasting, requiring minimal maintenance over time.
5. Noise Reduction: It should be designed to minimise external noise, providing a quieter and more relaxing driving experience.

These non-functional requirements ensure that the car not only performs its functions but also delivers a high-quality driving experience that meets user expectations.

With the email application, some non-functional requirements might include:

- Performance: The application should load within two seconds, even under high user traffic.
- Security: User data should be encrypted both in transit and at rest to prevent unauthorised access.
- Scalability: The application should handle a growing number of users without significant degradation in performance.
- Reliability: It should be available 99.9% of the time, with minimal downtime for maintenance or updates.
- Usability: The interface should be intuitive, with clear navigation and responsive design across devices.

These non-functional requirements ensure that the email application not only functions but also provides a seamless and reliable user experience.

To summarise:
- Functional Requirements: Define what the product does—its specific tasks or functionalities.
- Non-Functional Requirements: Define how well the product performs those tasks and the overall quality of the user experience.
 
So next time you're using Netflix, driving in your car, or even sitting on your toilet - take a moment to appreciate the carefully drafted set of requirements that put the product in your hands (or under your bottom!).

[Go home](README.md)

[1}: <https://www.gov.uk/government/people/fraser-sampson>
{2]: <https://www.bbc.co.uk/sounds/play/w3ct4tqd>
