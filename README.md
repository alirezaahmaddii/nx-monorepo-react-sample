# ReactMonorepo

## Create new folder
npx create-nx-workspace@latest folder-project-name --preset=react-monorepo
## Create new app 
npx nx g @nx/react:app app-name --directory=apps/app-name
## Create new lib 
nx g @nx/react:library share-name --directory=libs/share-name
## Run project
nx run project-name:serve
## Remove project 
nx g rm project-name
## Run graph
nx graph
