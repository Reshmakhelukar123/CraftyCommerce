# CraftyCommerce

CraftyCommerce is an online marketplace for handmade goods. The platform allows artisans to list their products, manage customer reviews, and provide a seamless shopping experience. This project simulates a real-world software development process using Git and GitHub for effective version control and collaboration.

## Project Overview

The project is divided into several key features, each managed through separate branches in Git. These features include:

1. **Product Listing**: Enables sellers to list handmade products on the platform.
2. **Shopping Cart**: Allows customers to add products to a cart and proceed with a purchase.
3. **Customer Reviews**: Provides a feature for customers to leave reviews on products.

## Development Team

- Jane Doe
- John Smith
- Alex Johnson

## Branch Structure

- `master`: The main branch containing the stable, production-ready code.
- `feature-product-listing`: A branch dedicated to developing the product listing functionality.
- `feature-shopping-cart`: A branch focused on implementing the shopping cart feature.
- `feature-customer-reviews`: A branch aimed at adding customer review capabilities.

## Development Process

1. **Branching**: Each feature is developed in its own branch to ensure isolation and easy integration. Branches are named using the convention `feature-{feature-name}`.
   
2. **Committing Changes**: Changes are committed with descriptive messages to ensure clarity and traceability. Example commit message: `git commit -m "Added initial product listing functionality"`.

3. **Merging**: Once a feature is complete, a pull request is opened on GitHub to merge the feature branch into the `master` branch. The developer acts as both the author and reviewer, ensuring code quality before merging.

4. **Syncing Branches**: Regular updates from the `master` branch are pulled into feature branches to avoid conflicts: `git pull origin master`.

## Git Commands Overview

- **List Branches**: `git branch --list`
- **Create Branch**: `git checkout -b feature-branch-name`
- **Switch Branch**: `git checkout branch-name`
- **Commit Changes**: `git add .` followed by `git commit -m "commit message"`
- **Push Branch to GitHub**: `git push origin feature-branch-name`
- **Pull Latest from Master**: `git pull origin master`
- **View Commit History**: `git log`
- **Check Status**: `git status`

## Challenges Faced

- **Merge Conflicts**: Encountered conflicts while merging branches. Resolved by carefully reviewing changes and merging the correct code.
- **Branch Synchronization**: Ensuring that all branches were up to date with the latest changes from the master branch.

## Lessons Learned

- The importance of regular commits and descriptive commit messages to maintain a clear history of changes.
- The need for proper branching strategies to isolate feature development and avoid conflicts.
- How to manage and resolve merge conflicts effectively.

## Conclusion

This project provided hands-on experience with Git and GitHub, simulating a real-world development environment. It emphasized the importance of version control and collaboration in software development, preparing us for working in a team-based setting.


