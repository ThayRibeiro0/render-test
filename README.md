# example-render-app

Description: This is a simple example of how to render a scene with the Evr SDK.
Rendering / Deployment: Testing how to render a scene with the Evr SDK, where first we copy the folder and other place and open and run:

```bash
git init
git remote add origin <REPOSITORY_URL>
```

Then we can run git add, commit and push and it will be deployed to the Environment.

## Deploying to Render:

This website: https://dashboard.render.com/dashboard
The function of the Render is to render the scene and save it in the bucket, one alternative beside GitPages to render the scene online.
To this we create a account for free and we can do small projects, then for this one the Readme.md guide us to use the commands below to setting up the project on Render with the Build Command and Start Command:

```bash
npm run render-build
npm run start
```

After that we can see the result on the Render website, the link below the name of the project.
The result is the same as the GitPages, but with the advantage of being able to render the scene online.

## Usage

```bash
# Install dependencies
npm install

# Run the example
npm start
```

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.