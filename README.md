My Account: https://github.com/Wim-Lotz

# Setup
- Create GitHub account https://github.com
- Create public project called `MyTasks`
- Clone locally I am using https://desktop.github.com
- Download and install  https://dotnet.microsoft.com/download/dotnet/3.1
- Download and install https://insomnia.rest/download
- Create .gitignore file and add `obj` and `bin`

# .NET Core Web API
1. Create API project called `MyTasksAPI`
2. CMD: `dotnet create new webapi --new MyTasksAPI`
3. CMD: `dotnet run`

# Test
- Browser https://localhost:5001 && http://localhost:5000

# Insomnia
1. Create request collection
2. Create new request `GET`: `https://localhost:5001`

# Commit Source
1. Hit `ctrl c` to stop api
2. CMD `git status` to see which files are ready for commit. **NB** ensure that `bin` and `obj` directories are not commited
3. Add files to source, commit and then push to your Github repo