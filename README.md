
<div>
  <a href='https://mycooknook.com/'>
    <img src ='https://mycooknook.com/CooknookEmailHeader.png' width='300' alt='Cooknook Header'> </img>
  </a>
</div>
<br></br>

[https://mycooknook.com](https://www.mycooknook.com)

**Jacob Clarke**  
Founder & Developer of Cooknook
<br></br>
jacobclarke.swe@gmail.com
<br></br>
[LinkedIn](https://www.linkedin.com/in/jacob-clarke-developer/) | [Github](https://www.github.com/jacobclarke4/)

## TL;DR
- Production-grade cooking platform for creating, organizing, and sharing recipes. Built with Next.js (SSR), Firebase (Auth, Firestore), Firebase Cloud Functions, and AWS hosting. See architecture below.
- This repository is a curated showcase, the production codebase is private.

## Overview
CookNook helps home cooks create and save personalized recipes, track version history, build cookbooks, fork and collaborate on recipes, and use AI-powered ingredient substitution. Premium features (AI Chef, Cookbooks) are available via Stripe subscriptions.

## Key features
- Create and save personalized (private or public) recipes.
- View version history including changelogs for recipes.
- Build custom cookbooks using personal recipes and recipes from other users.
- Collaborate with others by “Forking” their recipe — create your own editable copy to tweak, experiment, or add a personal twist, while keeping the original intact and giving credit to its creator.
- Ask AI Chef (OpenAI) for ingredient substitutions to easily adapt any recipe to your preferences, dietary needs, or what you already have in your kitchen.
- Subscribe via Stripe to get access to premium features such as: AI Chef and Cookbooks

---
Create Beautiful Recipes with ease!
<img src='/example-images/RecipeExample.png' alt='Recipe Example'></img>
Version history timeline to view all previous iterations of a recipe!
<img src='/example-images/VersionHistoryExample.png' alt='Version History Example'></img>
Organize recipes into well-organized Cookbooks!
<div align='center'>
  <img src='/example-images/CookbookExample.gif' alt='Cookbook Example'></img>
</div>
Get Ingredient Substitutions based on user inputted needs or ingredient availability!
<img src='/example-images/IngredientSubstitutionExample.png' alt='Ingredient Substitution Example'></img>

## Database Design Structure
<img src='/database-structure/database-structure.png' alt='Database Structure'></img>


## System Architecture
<img src='/system-design/system-design.png' alt='System Design'></img>

| Category | Technology |
|-----------|-------------|
| Frontend | Next.js, React, TypeScript |
| Backend | Node.js, Firebase Cloud Functions |
| Database | Firestore, Firebase Storage |
| Hosting | AWS Amplify, Route 53 |
| CI/CD | GitHub Actions |
| Monitoring | AWS CloudWatch, Google Cloud Monitoring |
| Animations | Illustrator, After Effects, LottieFiles |
| Payments | Stripe |
| AI Integration | OpenAI API, Stripe API |
