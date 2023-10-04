# NextJS_Assessment - Frontend

This is a Next.js, TypeScript, and Tailwind CSS project.

## Getting Started

This project uses yarn workspaces as the default monorepo architecture.

1. First, clone the repo:

   ```bash
   git clone https://github.com/Mhiracul/NextJS_Assessment-Frontend.git

   1. Install all dependencies:

     yarn install

   2. Run the development server:


    npm run dev

    # or

    yarn dev

    # or

    pnpm dev
   ```

## Commit Standards

# Branches

dev -> Pull request to this branch for everything frontend related.
main -> Do not touch this branch; it represents what is running in production.

## Contributions

NextJS_Assessment is open to contributions. We recommend creating an issue or replying in a comment to let us know what you are working on first to avoid conflicts.

# Contribution Guidelines

1. Clone the repo:

git clone https://github.com/Mhiracul/NextJS_Assessment-Frontend.git

2. Open your terminal & set the origin branch:

git remote add origin https://github.com/Mhiracul/NextJS_Assessment-Frontend.git

3. Pull the dev branch:

git pull origin dev

4. Create a new branch for the task you were assigned to, e.g.:

git checkout -b feat-csv-parser

5. After making changes, stage them:

git add .

6. Commit your changes with a descriptive commit message:

git commit -m "commit message"

7. To ensure there are no conflicts, run:

git pull origin dev

8. Push changes to your new branch:

git push -u origin feat-csv-parser

9. Create a pull request to the dev branch (not main).

⚫ Ensure to describe your pull request.
⚫ If you've added code that should be tested, add some test examples.
