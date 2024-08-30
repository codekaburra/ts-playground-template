# playground-solana# ts-playground-template


npx create-typescript-application

npm install --save-dev --save-exact prettier

npm install --save-dev husky lint-staged
npx husky init
node --eval "fs.writeFileSync('.husky/pre-commit','npx lint-staged\n')"