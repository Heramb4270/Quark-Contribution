# Git and Github

This repository serves as a hub for Git & GitHub activities, including **Generating Pull Requests** and mastering essential Git commands.
---
Website:- https://heramb4270.github.io/Quark-Contribution/
---
## Pull Requests
### Overview
A **pull request** (PR) is a way to propose changes to a repository on GitHub. It allows developers to collaborate, review code, and merge contributions into the main branch of a project.

---

### 📝 Steps to Generate a Pull Request

#### 1. **Fork the Repository**

- Go to the GitHub repository you want to contribute to.
- Click on the **Fork** button in the top-right corner.
- This will create a copy of the repository under your GitHub account.

#### 2. **Clone the Repository**

- Copy the repository’s URL from your forked repository.
- Run the following command in your terminal to clone the repository locally:
  ```bash
  git clone https://github.com/Heramb4270/Quark-Contribution.git
  cd Quark-Contribution
  ```

#### 3. **Create a New Branch**

- Create and switch to a new branch for your changes:
  ```bash
  git checkout -b <branch-name>
  ```
  Example:
  ```bash
  git checkout -b feature/add-new-functionality
  ```

#### 4. Update the **colaborators.json** file

- Open the colaborators.json file in any text editor or IDE.
- Add your details in the following format under the "colaborators" array:
  ```bash
  {
    "collaborators":[
        {
          "name": "Your Name",
          "year": "First Year",
          "dept": "Your Department",
          "funfact": "A short and engaging fact about yourself or something related to your interests.",
          "feedback": "Your feedback"
        }
    ]
   }
  ```
- Example Entry:
  ```bash
  {
    "collaborators":[
        {
            "name": "John Doe",
            "year": "TY",
            "dept": "CS",
            "funfact": "The first computer game was made in 1962! 🎮",
            "feedback": "Got to know how to generate pull requests on Github"
        }
    ]
   }
  ```
-  After making the changes, check the status of modified files:
  ```bash
  git status
  ```

#### 5. **Commit Your Changes**

- Stage the modified files:
  ```bash
  git add .
  ```
- Commit the changes with a descriptive message:
  ```bash
  git commit -m "<Your commit message>"
  ```
  Example:
  ```bash
  git commit -m "Added functionality to handle user authentication"
  ```

#### 6. **Push the Changes to Your Fork**

- Push your branch to your forked repository:
  ```bash
  git push origin <branch-name>
  ```
  Example:
  ```bash
  git push origin feature/add-new-functionality
  ```

#### 7. **Open a Pull Request**

- Go to your forked repository on GitHub.
- Navigate to the branch you pushed changes to.
- Click the **Compare & pull request** button.
- Fill out the pull request form.
- Click **Create pull request.**

---

## ⭐ Tips for a Good Pull Request

- **Keep it Focused:** Limit your pull request to a single feature or fix.
- **Write a Clear Description:** Explain why your changes are necessary and what they do.
- **Follow Coding Standards:** Adhere to the coding conventions of the repository.
- **Test Your Changes:** Ensure your code works as intended and doesn’t break existing functionality.
- **Be Responsive:** Address feedback from reviewers promptly.

---

## Additional Resources

- [GitHub Documentation on Pull Requests](https://docs.github.com/en/pull-requests)
- [Git Basics](https://git-scm.com/book/en/v2)

---

## Feedback & Support

If you face any issues or have questions, feel free to reach out.

Happy Coding! 🚀

