# Collective Intelligence Course

Welcome to the **Collective Intelligence** Course! 🎓 This is the central hub for managing and sharing projects related to our course. Each topic is divided into separate repositories, providing a structured environment for collaboration and development.

## Repository Structure

Each repository within this organization represents a different **topic** in the course. Projects are organized in a specific way to ensure consistency across semesters:

- **Branches are divided by semesters**: For example, `2024/25/1` for the first semester of the `2024/25` academic year.
- The **main branch mirrors the latest semester**. You should always start by reviewing this branch.
- Branches from **previous semesters are locked** and read-only for reference.

## How to Get Started

To begin working on a project, follow these steps:

1. ✅ **Review last semester's code** (optional). You are encouraged to improve upon the existing codebase, but you may also choose to start fresh.
   
2. ✅ **Clone the repository**:
   - Use one of the following methods:
     - **SSH**: `git clone git@github.com:your-org/repo-name.git`
     - **HTTPS**: `git clone https://github.com/your-org/repo-name.git`
     - **GitHub CLI**: `gh repo clone your-org/repo-name`

3. ✅ **Create a new branch for the current semester**:
   ```bash
   git checkout -b 2024/25/1
   ```
   This is where you'll work on modifying, improving, or removing existing code.

4. ✅ **Push your branch to GitHub**:
   ```bash
   git push --set-upstream origin 2024/25/1
   ```

5. ✅ **Work on the project**: As you make progress, keep the following in mind:
   - **Maintain the code** throughout the semester.
   - **Document your work**: Update the `README.md` with detailed information about the project.
   - **Use the GitHub Wiki** to track bugs, implementation details, and important notes.

## Responsibilities

- **Code Maintenance**: Ensure the project runs smoothly throughout the semester.
- **Detailed Documentation**: Keep the `README.md` file updated with the project's current status, usage instructions, and any other relevant information.
- **GitHub Wiki**: Each group is responsible for maintaining a Wiki page to track bugs, implementation progress, and other technical details.

## Merging Your Branch at the End of the Semester

Once you've completed your work for the semester, you'll need to merge your branch into the main branch. Please follow these steps carefully:

1. **Ensure your local `main` branch is up to date** with the origin `main` branch:
   ```bash
   git checkout main
   git pull origin main
   ```

2. **Resolve any merge conflicts** if they arise. Ensure all conflicts are resolved before proceeding.

3. **Merge your branch into the main branch**:
   ```bash
   git merge 2024/25/1
   ```

4. **Push the updated main branch to GitHub**:
   ```bash
   git push origin main
   ```

Once the merge is complete, your changes will be part of the main branch and locked for future reference.
  
## Permissions and Restrictions

- Each person is assigned to a **specific group** within the organization, and only that group has write access to the associated repository.
- The **main branch is protected** and can only be merged at the end of the semester.
- **Previous semester branches are locked** and read-only for reference.
- You **do not have permission** to:
  - ❌ Create new teams inside the organization.
  - ❌ Create new repositories.
  - ❌ Modify repository settings.
  - ❌ Add new members to the organization.
  - ❌ Change repositories that are not assigned to your group.

## Final Notes

At the end of the semester, your work will be reviewed, and code from your branch may be merged into the main branch after evaluation. Be sure to follow all best practices, write clean code, and collaborate effectively within your assigned group.

If any issues arise with GitHub, Git, or the Organization, contact me at [tamastheactual@inf.elte.hu](mailto:tamastheactual@inf.elte.hu).

Good luck, and happy coding! 🚀
