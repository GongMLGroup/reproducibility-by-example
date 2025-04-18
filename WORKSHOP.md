# Workshop: Improving Code Reproducibility

## Phase 1: Starting Point (`main` branch)

- **Goal**: Identify issues in the original code.  
- **Tasks**:  
1. Clone the repo: `git clone https://github.com/GongMLGroup/reproducibility-by-example.git`  
2. Run the code (intentionally fail due to missing dependencies).  
3. Discuss: "What makes this project hard to reproduce?"

---

## Phase 2: Dependency Handling (`dependencies` branch)

- **Goal**: Fix dependency management.  
- **Tasks**:  
1. Switch branch: `git checkout dependencies`  
2. Compare changes to `main`: `git diff main..dependencies`  
3. Explain tools like `requirements.txt`, or `uv`.  
4. Exercises:   
   1. Initialize the project `uv init project`  
   2. Add missing dependencies to `project.toml`.

---

## Phase 3: Organizing Folders (`structure` branch)

- **Goal**: Improve project structure.  
- **Tasks**:  
1. Switch branch: `git checkout structure`  
2. Discuss why folder structure matters (e.g., `notebooks/`, `data/`, `results/`).  
3. Exercises:  
   1. Move data into the `data/` directory and update paths.  
   2. Save results into the `results/` directory and update paths.

## 

---

## Phase 4: Documentation (`documentation` branch)

- **Goal**: Add documentation.  
- **Tasks**:  
1. Switch branch: `git checkout documentation`  
2. Explain writing effective `README.md` files and code comments.  
3. Exercises:  
   1. Document a function in the code  
   2. update the `README`.

---

## Phase 5: Final Version (`final` branch)

- **Goal**: Merge all improvements.  
- **Tasks**:  
1. Compare `final` to `main`: `git diff main..final`  
2. Discuss how reproducibility is now enforced.