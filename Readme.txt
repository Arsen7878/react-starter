// ========== 01 ==========

npx create-react-app .
npm install --save-dev prettier eslint@"^7.11.0" husky lint-staged prop-types gh-pages

// ========== 02 [ Windows ] ==========

npx mrm@2 lint-staged

// ========== 02 [ MacOS і Linux ] ==========

npx mrm lint-staged

// ========== 03 ==========

Закидуємо файли у корінь проекту біля package.json, із підміною файлів:

.huskyrc
.prettierrc.yaml
.lintstagedrc
package.json 

// ========== 05 ==========

У файлі [ package.json ] замінюємо ВСІ назви [ your_github_name ] на свій github-name + назву репозиторію [ your_repository_name ] на свою.

Має получитись із цього:
"https://your_github_name.github.io/your_repository_name/"
Ось це:
"https://fosa1990.github.io/goit-react-hw-01-components/"

// ========== 06 ==========

npm start       <=== для тестового запуску, чи все працює
npm run deploy	<=== для того щоб на гіті появилась гілка gh-pages 

// ========== Notes ==========

URLs:
1)github-pages deployment, офіційна стаття:
https://create-react-app.dev/docs/deployment#github-pages

2)Деплой приложения на Github Pages
https://drive.google.com/file/d/1EOewQyS7V9SHsUbbycwgTNqB59jwhFnG/view

3)react-lint-staged-workshop
https://github.com/goitacademy/react-lint-staged-workshop