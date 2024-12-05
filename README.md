# mobile-app
git checkout -b feature/ui
git checkout -b feature/backend
git checkout -b feature/testing
git commit -m "Add basic UI structure"
git commit -m "Implement task addition feature"
git commit -m "Fix bug in task editing functionality"
git checkout main
git merge feature/ui
git merge feature/backend
git merge feature/testing