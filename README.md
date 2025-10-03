# 🚀 Full Stack Project

This is a full-stack application with separate frontend and backend components, each with their own PR templates.

## 📁 Project Structure

```
├── frontend/          # React frontend application
├── backend/           # Node.js backend API
├── .github/
│   ├── PULL_REQUEST_TEMPLATE/
│   │   ├── frontend.md    # Frontend PR template
│   │   └── backend.md     # Backend PR template
│   └── workflows/
│       └── pr-template.yml # Auto template selection
└── README.md
```

## 🎨 Frontend

- **Framework:** React with Vite
- **Location:** `frontend/`
- **PR Template:** `.github/PULL_REQUEST_TEMPLATE/frontend.md`

### Setup
```bash
cd frontend
npm install
npm run dev
```

## ⚙️ Backend

- **Framework:** Node.js with Express
- **Location:** `backend/`
- **PR Template:** `.github/PULL_REQUEST_TEMPLATE/backend.md`

### Setup
```bash
cd backend
npm install
npm run dev
```

## 📝 PR Templates

### How it works:
1. **Automatic Detection:** GitHub workflow detects if changes are in `frontend/` or `backend/` folders
2. **Template Selection:** Appropriate template is suggested based on file changes
3. **Manual Selection:** You can also manually choose template when creating PR

### Available Templates:
- **Frontend Template:** For UI/UX changes, React components, styling
- **Backend Template:** For API changes, database modifications, server logic

## 🔄 Workflow

1. Make changes in `frontend/` or `backend/` folder
2. Create PR - GitHub will suggest appropriate template
3. Fill out the template with your changes
4. Submit PR for review

## 🛠️ Development

### Frontend Development
- Focus on UI/UX improvements
- Browser compatibility testing
- Responsive design
- Component testing

### Backend Development
- API endpoint development
- Database schema changes
- Security considerations
- Performance optimization

## 📋 Contributing

1. Choose the appropriate branch for your changes
2. Make your changes in the relevant folder (`frontend/` or `backend/`)
3. Create PR using the suggested template
4. Fill out all required sections
5. Request review from team members
