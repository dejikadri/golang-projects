# Golang Projects

This repository contains various Golang projects organized by contributor folders.

## Branch Naming Convention

When creating a new branch, follow this naming convention:

```
username-feature-description
```

### Examples:
- `john-auth-system`
- `sarah-payment-integration`
- `mike-database-migration`
- `alice-api-endpoints`

## Project Organization

### Working Within Your Folder

1. **Only work within your assigned folder** - Each contributor has their own folder named after their username
2. **Create new projects/features as subfolders** under your personal folder
3. **Maintain clean organization** by keeping related code together

### Folder Structure Example:
```
golang-projects/
├── networking/
│   ├── bash/
│   │   └── tcp-echo-server/
│   ├── eno/
│   │   └── tcp-echo-server/
│   └── everistus/
│       └── tcp-echo-server/
└── README.md
```

### Creating a New Branch

1. **Switch to main branch:**
   ```bash
   git checkout main
   git pull origin main
   ```

2. **Create and switch to new branch:**
   ```bash
   git checkout -b username-feature-description
   ```

3. **Example:**
   ```bash
   git checkout -b john-user-authentication
   ```

### Working on New Projects/Features

1. **Navigate to your personal folder:**
   ```bash
   cd your-username/
   ```

2. **Create a new project folder:**
   ```bash
   mkdir new-project-name
   cd new-project-name
   ```

3. **Initialize your project:**
   ```bash
   go mod init github.com/your-username/project-name
   ```

4. **Start coding and commit regularly:**
   ```bash
   git add .
   git commit -m "Add initial project structure"
   git push origin username-feature-description
   ```

## Best Practices

- **Always create a branch** before starting work
- **Use descriptive branch names** that clearly indicate what you're working on
- **Keep your work organized** within your personal folder
- **Commit frequently** with meaningful commit messages
- **Test your code** before pushing to remote
- **Create pull requests** for code review when ready to merge

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd golang-projects
   ```

2. Create your personal folder if it doesn't exist:
   ```bash
   mkdir your-username
   ```

3. Start working on your projects following the guidelines above!

## Contributing

- Follow the branch naming convention
- Work only within your assigned folder
- Create meaningful commit messages
- Test your code before submitting
- Create pull requests for any changes to shared resources
