# Git Workflow & Branching Strategy

##  Git Flow Strategy 
We follow **Git Flow**, a branching model that ensures clean collaboration.

### ** Main Branches**
- **`main`**: Stable, production-ready code. **(Protected, no direct commits.)**
- **`develop`**: Default branch for active development.  

### ** Supporting Branches**
- **`feature/*`** → For new features  
- **`release/*`** → For preparing releases  
- **`hotfix/*`** → For urgent production bug fixes  

---

##  **Workflow Steps for Feature Development**
 **Start a New Feature**
```sh
git checkout develop
git pull origin develop
git checkout -b feature/your-feature-name
