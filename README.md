<div>
  <h1>Wanderlust</h1>
  <h2>The Ultimate Travel Blog 🌍✈️ for You </h2>
</div>

![Preview Image](https://github.com/krishnaacharyaa/wanderlust/assets/116620586/17ba9da6-225f-481d-87c0-5d5a010a9538)

<hr>

<div>
  <h2><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/4a07b161-b8d6-4803-804a-3b0db699023e" width="35" height="35"> Goal of this project </h2>
</div>

At its core, this project embodies two important aims:

1. **Start Your Open Source Journey**: It's aimed to kickstart your open-source journey. Here, you'll learn the basics of Git and get a solid grip on the MERN stack and I strongly believe that learning and building should go hand in hand.
2. **React Mastery**: Once you've got the basics down, a whole new adventure begins of mastering React. This project covers everything, from simple form validation to advanced performance enhancements. And I've planned much more cool stuff to add in the near future if the project hits more number of contributors.

_We want you to get the most out of this project—it's all about learning, contributing, and growing in the open-source community._
<hr>

<div>
  <h2><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/1ee5934a-27be-4502-a7bf-e6a8c78fe5a3" width="35" height="35"> Features</h2>
</div>

- **Featured Posts :** Highlight top travel stories and destinations on the homepage to showcase the best content and inspire readers with exciting travel experiences.
- **User-Friendly Interface:** Navigate effortlessly through captivating travel content with our intuitive design.
- **Discover By topic categories:** **Discover by Topic Categories**: Explore diverse travel experiences categorized by travel, nature, city, Adventure and Beaches..


<hr>

In our project, we believe in creating an open and inclusive space for everyone. To ensure a respectful and positive community, follow these key guidelines:

Respect Each Other: Treat all participants kindly and respectfully.
Use Inclusive Language: Keep your language welcoming and inclusive when communicating.
Accept Constructive Feedback: Be open to constructive criticism and focus on what's best for the community.
No Unacceptable Behavior: Avoid behaviors like harassment, trolling, insults, or anything that's inappropriate in a professional setting.
We're committed to maintaining a positive and inclusive community, and your cooperation is crucial for making this a safe and enjoyable space for everyone.


Setting up the Project
To setup the project locally follow the steps:

Fork and Star the project.

Clone your forked repository.

git clone https://github.com/YOUR-USERNAME/wanderlust.git
Download the required dependencies

cd wanderlust
npm run installer
Set up your databases

Make sure you install mongodb and run it on port 27017

Option 1: mongoimport

mongoimport --db wanderlust --collection posts --file ./data/sample_posts.json --jsonArray
Option 2: Manual insertion using mongodb compass

Create wanderlust db
Create a new collection named posts in the wanderlust db
Use ADD DATA option in the posts collection and use the content from backend/data/sample_posts.json file
Set up Redis

Make sure you install redis and run it in redis://127.0.0.1:6379
Set up env variables

cp backend/.env.sample backend/.env && cp frontend/.env.sample frontend/.env.local
Launch the development server with npm start in the root directory of the repository.


Request for Changes/Pull Requests
To contribute to this project, you need to create a fork of the repository and then commit your changes to it. Follow these steps:

Fork the repository if haven't done already from wanderlust

Add your fork as a local project:

# Using HTTPS
git clone https://github.com/YOUR-USERNAME/wanderlust.git
# Using SSH
git clone git@github.com:YOUR-USERNAME/wanderlust.git
Add git remote controls:

# Using HTTPS
git remote add fork https://github.com/YOUR-USERNAME/wanderlust.git
git remote add upstream https://github.com/krishnaacharyaa/wanderlust.git
# Using SSH
git remote add fork git@github.com:YOUR-USERNAME/wanderlust.git
git remote add upstream git@github.com:krishnaacharyaa/wanderlust.git
Verify that you have your two git remotes:

git remote -v
For every individual PR follow these 2 steps:

To stay up to date with the central repository:

git pull upstream main
Checkout a private from your main Branch

# Switch to the main branch
git switch main

# Pull down any upstream changes
git pull

# Create a new branch to work on
git switch --create bugfix/1234-name-of-the-issue
Commit your changes, then push the branch to your fork with git push -u fork and open a pull request on the Wanderlust repository following the template provided.


Guidelines for Contributions
Claiming an Issue: Before you start working on an issue, make sure it's assigned to you. We do this to avoid overlapping efforts and to ensure your hard work doesn't go to waste. Please avoid raising a PR for an issue assigned to someone else.
Commit Format: When making commits, follow this format: tag-#issue-number: <commit-message>. The tag should be one of these: fix, feat, docs, chore, refactor.
PR Title: When creating a Pull Request, the title should be in this format: tag-#issue-number: <Title-of-PR>. Again, use the same tags: fix, feat, docs, chore, refactor.
Coding Standards: Ensure that your code aligns with our coding standards and guidelines. For example, use naming conventions like file-name.ts, not fileName.ts.
Selective Staging: Make sure you stage only the necessary commits when raising a PR.
Rebasing: Check if your PR is rebased to the latest main/development branch. More details can be found in Request for Changes/Pull Requests.
Use Default PR Template: Make sure your PR follows our default PR template.
These guidelines help maintain a smooth and organized contribution process. I appreciate your attention to these details, and your contributions are valued. Thanks for being part of our open-source community!! Lets all help each other for mutual growth!!
Commit Format: When making commits, follow this format: tag-#issue-number: <commit-message>. The tag should be one of these: fix, feat, docs, chore, refactor.
PR Title: When creating a Pull Request, the title should be in this format: tag-#issue-number: <Title-of-PR>. Again, use the same tags: fix, feat, docs, chore, refactor.
Coding Standards: Ensure that your code aligns with our coding standards and guidelines. For example, use naming conventions like file-name.ts, not fileName.ts.
Selective Staging: Make sure you stage only the necessary commits when raising a PR.
Rebasing: Check if your PR is rebased to the latest main/development branch. More details can be found in Request for Changes/Pull Requests.
Use Default PR Template: Make sure your PR follows our default PR template.
These guidelines help maintain a smooth and organized contribution process. I appreciate your attention to these details, and your contributions are valued. Thanks for being part of our open-source community!! Lets all help each other for mutual growth!!
  
