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


<a name="setting-up-the-project"></a>
# Setting up the Project

To setup the project locally follow the steps:

1. Fork and Star the project.

2. Clone your forked repository.
   ```bash
   git clone https://github.com/YOUR-USERNAME/wanderlust.git
   ```

3. Download the required dependencies
   ```bash
   cd wanderlust
   npm run installer
   ```

4. Set up your databases
   - Make sure you install [ mongodb](https://www.mongodb.com/docs/manual/installation/) and run it on port `27017`

     **Option 1: mongoimport**
     ```bash
     mongoimport --db wanderlust --collection posts --file ./data/sample_posts.json --jsonArray
     ```

     **Option 2: Manual insertion using mongodb compass**
     - Create `wanderlust` db
     - Create a new collection named `posts` in the `wanderlust` db
     - Use **ADD DATA** option in the `posts` collection and use the content from `backend/data/sample_posts.json` file

5. Set up Redis
   - Make sure you [install redis](https://redis.io/docs/latest/operate/oss_and_stack/install/install-redis/) and run it in `redis://127.0.0.1:6379`

6. Set up env variables
   ```bash
   cp backend/.env.sample backend/.env && cp frontend/.env.sample frontend/.env.local
   ```

7. Launch the development server with `npm start` in the root directory of the repository.

<a name="request-for-changes-pull-requests"></a>

## Request for Changes/Pull Requests

To contribute to this project, you need to create a fork of the repository and then commit your changes to it. Follow these steps:

1. Fork the repository if haven't done already from [wanderlust](https://github.com/krishnaacharyaa/wanderlust/)
2. Add your fork as a local project:

   ```sh
   # Using HTTPS
   git clone https://github.com/YOUR-USERNAME/wanderlust.git
   ```

   ```sh
   # Using SSH
   git clone git@github.com:YOUR-USERNAME/wanderlust.git
   ```

3. Add git remote controls:

   ```sh
   # Using HTTPS
   git remote add fork https://github.com/YOUR-USERNAME/wanderlust.git
   git remote add upstream https://github.com/krishnaacharyaa/wanderlust.git
   ```

   ```sh
   # Using SSH
   git remote add fork git@github.com:YOUR-USERNAME/wanderlust.git
   git remote add upstream git@github.com:krishnaacharyaa/wanderlust.git
   ```

4. Verify that you have your two git remotes:

   ```sh
   git remote -v
   ```

5. **For every individual PR follow these 2 steps:**

   - To stay up to date with the central repository:

     ```sh
     git pull upstream main
     ```

   - Checkout a private from your main Branch

     ```sh
     # Switch to the main branch
     git switch main

     # Pull down any upstream changes
     git pull

     # Create a new branch to work on
     git switch --create bugfix/1234-name-of-the-issue
     ```

Commit your changes, then push the branch to your fork with `git push -u fork`

