# Setup

To run locally, install dependencies and start up both the server and client.
```
npm install
npm start
```

This application offers an intuitive interface to deconstruct and clarify complex code segments in any public repo on GitHub.

File Tree🎄
```bash
├── npm-shrinkwrap.json
├── package.json
├── server
│   ├── auth.mjs
│   ├── env.mjs
│   ├── index.mjs
│   ├── prisma
│   │   ├── client.mjs
│   │   ├── dev.db
│   │   ├── migrations
│   │   │   ├── 20221219191221_init
│   │   │   │   └── migration.sql
│   │   │   └── migration_lock.toml
│   │   └── schema.prisma
│   ├── routes.mjs
│   └── validators.mjs
├── src
│   ├── App.js
│   ├── components
│   │   ├── Header.js
│   │   ├── Hero.js
│   │   ├── auth
│   │   │   ├── AuthButtons.js
│   │   │   ├── SignInForm.js
│   │   │   └── SignUpForm.js
│   │   ├── editor
│   │   │   ├── Breadcrumbs.js
│   │   │   ├── Editor.js
│   │   │   ├── EditorPanel.js
│   │   │   ├── ExplanationList.js
│   │   │   └── ExplanationPopup.js
│   │   ├── forms
│   │   │   ├── Button.js
│   │   │   ├── Checkbox.js
│   │   │   ├── FormError.js
│   │   │   ├── Input.js
│   │   │   └── Label.js
│   │   ├── repositories
│   │   │   ├── RepositoriesListItem.js
│   │   │   ├── RepositoriesSummary.js
│   │   │   └── RepositoriesTable.js
│   │   ├── search
│   │   │   └── SearchBar.js
│   │   └── tree
│   │       ├── File.js
│   │       ├── FileIcon.js
│   │       ├── Folder.js
│   │       ├── TreeEntry.js
│   │       └── TreePanel.js
│   ├── hooks
│   │   ├── useEntry.js
│   │   ├── useExplanation.js
│   │   ├── useFile.js
│   │   ├── useRepositories.js
│   │   ├── useSignIn.js
│   │   ├── useSignOut.js
│   │   ├── useSignUp.js
│   │   └── useUser.js
│   ├── index.css
│   ├── index.js
│   ├── routes
│   │   ├── EditorRoute.js
│   │   ├── HomeRoute.js
│   │   ├── NotFoundRoute.js
│   │   ├── RepositoriesSearchRoute.js
│   │   ├── RootRoute.js
│   │   ├── SignInRoute.js
│   │   ├── SignOutRoute.js
│   │   ├── SignUpRoute.js
│   │   └── TestRoute.js
│   ├── setupTests.js
│   └── util
│       └── getLangFromPath.js
└── tailwind.config.js
```