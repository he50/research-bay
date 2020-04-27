# Research Bay

## DSC Solution Challenge Submission Questions and Answers

#### Please clearly describe the challenge you are looking to solve with technology and how this solution addresses the challenge at hand. 
(max 500 chars)

Our university offers thousands of research opportunities, however, many students are unaware that these opportunities exist. Currently, there is no standardized way of discovering and pursuing research with professors. Research Bay aims to provide a platform for UIUC students to discover research opportunities and for professors to discover talent. It offers a streamlined, one-stop-shop solution for students and professors through personalized profiles, research postings coupled with a search/recommendation system. 

---

#### Walk us through the steps you took to test your solution.

---

#### Please share the outcome of your testing strategy. What specific feedback did you receive from users? What specifically did you maintain or iterate based on that feedback? 
(Think about the UI or the actual solution design or maybe did you have to go back to the idea and refine it further)

---

#### How will or has your solution improved the lives of people in your community? 
(Please include specific use cases of how users can use this solution. Do not worry about the technical components here)

---

#### Please walk us through the steps you took to build your solution. Include which products or platforms you used and why. Please include guidance on how to run your code.



Details for running our code are found here: https://github.com/DSC-UIUC/research-bay#getting-started

---

#### What do you see as the future / next steps for your project? What will take your project to the next level?

With much of Research Bay's core features largely complete, the team has started planning for Research Bay's eventual public release to the University of Illinois population. Once all features and sufficiently refined, tested, and finalized, the team expects to begin a limited release of Research Bay to groups of selected students and professors at UIUC sometime in fall 2020 to gather more user feedback, make any necessary updates, and gradually prepare for a full release farther in the future. Ideally, Research Bay could expand to other universities to continue its mission in new regions.

The Research Bay team also plans to continue development and maintenance of this project. Current plans are briefly described below, listed in order of short-term to long-term goals. Future development will continue to emphasize scalability, clean design, and better user experience.

1. UI Additions / Improvements
    * Local filtering for search and recommendation results
    * View and edit requirements for postings
    * Faster loading times for actions
    * Style / theme changes
2. Backend Code Optimizations / Speedups
    * Improve function code to reduce latency between client and server
    * Remove redundant DB queries
3. Recommendation / Search System Improvements
    * Larger, more generalized training data
    * Test with more user profiles and postings
4. Mobile app 
    * Would be a new frontend interface to expand Research Bay's availability and reach
    * Easy integration with existing backend
    * Develop in Flutter

---

#### What specific support do you need to achieve that?
*What has to happen to implement this solution to new regions and new users?*

To complete Research Bay into a production-ready user-facing public platform, the Research bay team is not only concerned with adding/improving website performance and functionality. To ensure better security for its users and their personal data, Research Bay will need the support of the University of Illinois and its Technology Services department to be further examined to make sure it meets all University standards. It will also be helpful to integrate Research Bay's user authentication with UIUC's Shibboleth system to better connect online users to their real-life identity.

The Research Bay team would also need support from both UIUC and Google with advertising and providing legitimacy for the website before and during its limited and public release stages. The University's assistance would be valuable when reaching out to professors to join the platform, and Google's support for Research Bay could provide increased exposure, trust, and willingness to join the platform by potential students.

In terms of effectively continuing development with new and existing features, Google's wide array of available technical expertise would be immensely helpful to take Research Bay to the next level. For example, learning from subject matter experts in Firebase would be really useful to the team to improve our backend codebase. Additional training for GCP and/or Firebase would give us a better, more comprehensive understanding of the in-depth details of the services that make up our product.

---

#### Describe your favorite component (s) /feature (s) of your technical infrastructure and why you chose it/them for your solution.

My favorite part of our tech stack for Research Bay is the Serverless Firebase backend and its REST HTTP API because it is modular, efficient, and responsible for seamlessly connecting all of the other components into Research Bay. For example, the React.js frontend communicates with the backend over HTTP using a well-defined API that follows REST principles. Due to this modular design, the backend can be used with any UI that follows the API standards. When the Research Bay mobile app is being developed, it will be able to easily integrate with the current backend just like the website.

Compared to typical servers (ex. using Node.js or Apache), our Serverless backend also has the following advantages:

1. Lower costs: the pay-as-you-go (or use) model: For Research Bay, it is important to us as students to keep resource costs low and efficient. With Firebase, our costs are kept minimal because the backend runs its Cloud Functions and spends compute time only when invoked by the frontend web app. Likewise, the Firestore database also only charges for direct W/R transactions. Additionally, thanks to Firebase's free usage limits, Research Bay's infrastructure costs will remain low even with many more users. 

2. Increased scalability: Given that our plan is to eventually release Research Bay to the UIUC population of students and professors, we emphasized futureproofing and scalability during development. All of the Firebase services we use for Research Bay (Authentication, Firestore, Storage, Hosting, Cloud Functions) are all automatically scalable to thousands of users with minimal changes in our code. All infrastructure maintenance and scaling is internally handled by Firebase.

3. Easier development with multiple languages for different features: To develop Research Bay's recommendation system, which matches professors with students for research opportunities, we opted use Python for its extensive collection of NLP libraries. Because our backend is written in Cloud Functions, which can be used with multiple languages, it was very easy to integrate our Python code into the rest of the API, which is mainly written in JavaScript.
