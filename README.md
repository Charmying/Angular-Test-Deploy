# TestAngularDeploy

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Deploy to GitHub Pages

1. 在 GitHub 中進入要進行部屬的專案 Repository 的 Setting 頁籤，在進入側邊欄的 Pages

2. 找到 Build and deployment，選好分支跟編譯完成的資料夾路徑後，點選 Save

3. 使用 `ng build --output-path=docs`，產生 docs 資料夾 (如果有 browser & server 資料夾，把 browser 資料夾內檔案拉出來再把 browser & server 資料夾全刪)

4. push 到 GitHub 上 (docs 資料夾也要)
