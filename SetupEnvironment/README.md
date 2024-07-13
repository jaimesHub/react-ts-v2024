# Setting up environment

## 1. Preparing something for React environment
1. Nodejs để run server react dưới local (`v22.3.0`)
2. VS code để code
   - Cài thêm extention Icon Theme cho VS code (`Material Icon Theme`)
   - Prettier để format code
   - ES Lint để quản lý tiêu chuẩn code
3. Trình duyệt Chrome với extension là React Developer Tool và Redux Dev Tool extension
4. Git: Tạo repo trên github để quản lý source code

## 2. Folder structure when using CRA
- [CRA](https://create-react-app.dev/docs/getting-started)
- `cd setup-env`
- `npm start`

## 3. How to use prettier & eslint
- Setting on VSCode
- `.editorconfig` file
- `.prettierrc` file
- Installing `devDependencies` for supporting eslint & prettier on terminal
   - `npm i prettier eslint-plugin-prettier eslint-config-prettier -D`
- `.eslintrc` for setting eslint
- Adding scripts to package.json
   - `npm run lint`: Kiểm tra lỗi eslint
   - `npm run lint:fix`: Fix lỗi liên quan eslint (đôi lúc có những lỗi bạn phải tự fix bằng tay)
   - `npm run prettier`: Kiểm tra lỗi prettier format
   - `npm run prettier:fix`: Tự fix lỗi prettier format

- Adding `.prettierignore`, `.eslintignore` for ignore files which you do not want to `prettier` or `eslint`
   - Same as `.gitignore`
   - `GitCanban.md`

## Setting CI/CD for deploying

## References
- [CaiDatMoiTruong](https://github.com/duocmmo/ReactJs-Super/blob/main/CaiDatMoiTruong/doc.md)