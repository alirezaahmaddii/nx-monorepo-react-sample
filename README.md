# ReactMonorepo

# Create new folder

```shell
npx create-nx-workspace@latest folder-project-name --preset=react-monorepo
```

# Create new app 
```shell
npx nx g @nx/react:app app-name --directory=apps/app-name
```

# Create new lib 
```shell
nx g @nx/react:library share-name --directory=libs/share-name
```

# Run project
```shell
nx run project-name:serve
```

# Remove project 

```shell
nx g rm project-name
```

# Run graph
```shell
nx graph
```
